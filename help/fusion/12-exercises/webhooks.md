---
title: Webhooks
description: Découvrez comment créer, déclencher et gérer des scénarios lancés par webhook.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
kt: 11053
thumbnail: KT11053.png
exl-id: d6a62a26-a8ab-477c-a8f2-98f3b9ff5edf
source-git-commit: 58a545120b29a5f492344b89b77235e548e94241
workflow-type: tm+mt
source-wordcount: '647'
ht-degree: 0%

---

# Webhooks

Découvrez comment créer, déclencher et gérer des scénarios lancés par webhook.

## Présentation de l’exercice

L’objectif de ce scénario est de créer une application à vendre aux épiceries afin qu’elles puissent facilement déterminer si un client est assez âgé pour acheter de l’alcool. Le caissier doit simplement publier le nom et la date de naissance du client sur une URL qui lui a été fournie. Cette publication déclenchera le scénario qui calculera la réponse et la renverra au demandeur.

1. Le scénario se compose de trois webhooks.
1. Le module déclencheur est un webhook personnalisé qui écoute une publication.
1. Lorsqu’il reçoit une publication, il la génère vers l’un des modules suivants.
1. Le module suivant renvoie une réponse au demandeur.

   ![Image 1 de Webhooks](../12-exercises/assets/webhooks-walkthrough-1.png)

## Étapes à suivre

**Configurez le déclencheur webhook.**

1. Créez un scénario et nommez-le &quot;Utilisation de webhooks&quot;.
1. Pour le déclencheur, ajoutez le module webhook personnalisé à partir de l’application Webhooks.
1. Cliquez sur Ajouter pour créer un nouvel webhook.
1. Saisissez le nom du webhook &quot;Application pour la période de boisson&quot;.
1. Laissez les restrictions d’IP vides, ce qui signifie que n’importe qui peut y envoyer des données.
1. Cliquer sur Enregistrer.


   ![Webhooks Image 2](../12-exercises/assets/webhooks-walkthrough-2.png)

1. De retour dans le panneau de mappage des webhooks, une URL a été créée pour ce webhook spécifique. Cliquez sur &quot;Copier l’adresse dans le Presse-papiers&quot; pour copier cette URL.
1. Cliquez sur OK.
1. Cliquez une fois sur Exécuter.
1. Utilisez l’URL de Postman pour envoyer un nom et une date d’anniversaire à votre webhook personnalisé. Pour plus d’informations sur la configuration de Postman, voir [Présentation détaillée de Webhooks](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/fusion/beyond-basic-modules/webhooks-walkthrough.html?lang=en) tutoriel .

   **Le panneau du module Webhooks doit se présenter comme suit :**

   ![Image Webhooks 3](../12-exercises/assets/webhooks-walkthrough-3.png)

   **Le webhook est maintenant dans un état où il écoute les données pour déterminer la structure des données.**

1. Vous pouvez définir la structure de données de la payload que vous prévoyez d’obtenir (les structures de données seront discutées ultérieurement). Si vous ne définissez pas de structure de données, Fusion détermine automatiquement la structure de données lors de l’envoi de la publication.
1. Du côté Postman, vous souhaitez envoyer à l’URL copiée. La publication doit inclure des données de formulaire de base. Pour cet exemple, vous avez besoin de trois champs : Nom, date de naissance et clientToken.

   ![Image 4 de Webhooks](../12-exercises/assets/webhooks-walkthrough-4.png)

1. Une fois que vous avez cliqué sur Envoyer depuis Postman , vous devriez recevoir une indication que la publication a été acceptée.
1. C’est à ce stade que votre scénario indique que la structure de données a été correctement déterminée.
1. Vous pouvez constater que les données ont été reçues lors de l’ouverture de l’Inspecteur d’exécution.

   ![Webhooks Image 5](../12-exercises/assets/webhooks-walkthrough-5.png)

   **Configurez le routage pour les jetons client.**

1. Ajoutez un routeur au module déclencheur.
1. Dans le chemin supérieur, ajoutez un module de réponse Webhook. Il s’agit de notre chemin d’accès lorsque le jeton client ne correspond pas.
1. Définissez l’état sur 401.
1. Définissez Body sur {&quot;error&quot; : &quot;Échec de l’authentification de la requête. Vérifiez votre clientToken&quot;}.

   ![Webhooks Image 6](../12-exercises/assets/webhooks-walkthrough-6.png)

1. Créez un filtre entre le routeur et le module de réponse Webhook. Nommez-le &quot;Le jeton client ne correspond pas&quot;.
1. Pour la condition, utilisez le champ clientToken du module déclencheur et effectuez une comparaison numérique &quot;Différent de&quot; avec le nombre 5121933.

   ![Webhooks Image 7](../12-exercises/assets/webhooks-walkthrough-7.png)

1. Dans le chemin d’accès inférieur, ajoutez un autre module de réponse Webhook. Il s’agit de notre chemin d’accès lorsque le jeton client correspond.
1. Définissez le statut sur 200.
1. Lors de la configuration du corps, utilisez les fonctions du panneau de mappage pour tester si la personne a 21 ans ou plus. Si c&#39;est le cas, retournez &quot;Vous êtes assez vieux pour boire !&quot;, sinon retournez &quot;Vous n&#39;avez pas de chance...&quot;.

   ![Webhooks Image 9](../12-exercises/assets/webhooks-walkthrough-9.png)

1. Créez un filtre entre le routeur et le module de réponse Webhook sur le chemin inférieur. Nommez-le &quot;Le jeton client correspond bien&quot;.
1. Pour la condition, utilisez le champ clientToken du module de déclenchement et effectuez une comparaison numérique &quot;Egal à&quot; avec le nombre 5121933.


   ![Webhooks Image 8](../12-exercises/assets/webhooks-walkthrough-8.png)

1. Cliquez sur le bouton Planification sous Exécuter une fois pour activer votre scénario afin qu’à chaque fois qu’une nouvelle publication est publiée, elle soit reçue, que vous empruntiez l’un des chemins d’accès et que vous génériez une réponse.
