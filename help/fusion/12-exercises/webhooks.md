---
title: Exercice sur les webhooks
description: Découvrez comment créer, déclencher et gérer des scénarios lancés par webhook.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11053
thumbnail: KT11053.png
recommendations: noDisplay,noCatalog
exl-id: d6a62a26-a8ab-477c-a8f2-98f3b9ff5edf
source-git-commit: a4e61514567ac8c2b4ad5c9ecacb87bd83947731
workflow-type: tm+mt
source-wordcount: '654'
ht-degree: 100%

---

# Exercice sur les webhooks

Découvrez comment créer, déclencher et gérer des scénarios lancés par webhook.

## Vue d’ensemble de l’exercice

L’objectif de ce scénario est de créer une application destinée à être vendue aux magasins de proximité afin de facilement déterminer si un client ou une cliente a l’âge requis pour acheter de l’alcool. Il suffit au caissier ou à la caissière d’afficher le nom et la date de naissance du client ou de la cliente à l’adresse URL qui lui a été fournie. Cette publication déclenche le scénario qui permet de calculer la réponse et de la renvoyer au demandeur ou à la demandeuse.

1. Le scénario se compose de trois webhooks.
1. Le module déclencheur est un webhook personnalisé qui écoute une publication.
1. Lorsqu’il reçoit une publication, il la transmet à l’un des modules suivants.
1. Le module suivant renvoie une réponse au demandeur ou à la demandeuse.

   ![ Image 1 - Webhooks](../12-exercises/assets/webhooks-walkthrough-1.png)

## Étapes à suivre

**Configurer le webhook du déclencheur.**

1. Créez un scénario et nommez-le « Utiliser les webhooks ».
1. Pour le déclencheur, ajoutez le module webhook personnalisé à partir de l’application Webhooks.
1. Cliquez sur Ajouter pour créer un webhook.
1. Saisissez le nom du webhook « Application pour l’âge de la consommation d’alcool ».
1. Laissez les restrictions d’IP vides, ce qui signifie que n’importe qui peut envoyer des données.
1. Cliquer sur Enregistrer.


   ![Image 2 - Webhooks](../12-exercises/assets/webhooks-walkthrough-2.png)

1. Dans le panneau de mappage des webhooks, une URL a été créée pour ce webhook spécifique. Cliquez sur « Copier l’adresse dans le presse-papiers » pour copier l’URL.
1. Cliquez sur OK.
1. Cliquez sur Exécuter une fois.
1. Utilisez l’URL dans Postman pour envoyer un nom et une date de naissance à votre webhook personnalisé. Pour obtenir des instructions sur la configuration de Postman, consultez le tutoriel [Présentation détaillée des webhooks](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/fusion/beyond-basic-modules/webhooks-walkthrough.html?lang=fr).

   **Le panneau du module Webhooks devrait ressembler à celui-ci :**

   ![Image 3 - Webhooks](../12-exercises/assets/webhooks-walkthrough-3.png)

   **Le webhook est maintenant à l’écoute des données pour déterminer la structure de celles-ci.**

1. Vous pouvez définir la structure de données de la charge utile que vous souhaitez obtenir (les structures de données seront abordées ultérieurement). Si vous ne définissez pas de structure de données, Fusion la déterminera automatiquement lors de l’envoi de la publication.
1. Du côté de Postman, envoyez l&#39;URL copiée. La publication doit contenir des données du formulaire de base. Pour cet exemple, vous avez besoin de trois champs : Nom, Date de naissance et ClientToken.

   ![Image 4 - Webhooks](../12-exercises/assets/webhooks-walkthrough-4.png)

1. Une fois que vous avez cliqué sur Envoyer depuis Postman , vous devriez recevoir une indication que la publication a été acceptée.
1. C’est à ce stade que votre scénario montrera que la structure des données a été déterminée avec succès.
1. Vous pouvez constater que les données ont été reçues lors de l’ouverture de l’inspecteur d’exécution.

   ![Image 5 - Webhooks](../12-exercises/assets/webhooks-walkthrough-5.png)

   **Configurez le routage pour les jetons clients.**

1. Ajoutez un routeur au module déclencheur.
1. Dans le chemin supérieur, ajoutez un module de réponse webhook. Il s’agit de notre chemin d’accès lorsque le jeton client ne correspond pas.
1. Définissez le statut sur 401.
1. Définissez le corps sur {&quot;error&quot;: &quot;Échec de l’authentification de la requête. Vérifiez votre clientToken&quot;}.

   ![Image 6 - Webhooks](../12-exercises/assets/webhooks-walkthrough-6.png)

1. Créez un filtre entre le routeur et le module de réponse webhook. Nommez-le « Le jeton client ne correspond pas ».
1. Pour la condition, utilisez le champ clientToken du module déclencheur et effectuez une comparaison numérique « N’est pas égal à » avec le nombre 5121933.

   ![Image 7 - Webhooks](../12-exercises/assets/webhooks-walkthrough-7.png)

1. Dans le chemin du bas, ajoutez un autre module de réponse webhook. Il s’agit de notre chemin d’accès lorsque le jeton client correspond.
1. Définissez le statut sur 200.
1. Lors de la mise en place du corps, utilisez les fonctions du panneau de mappage pour vérifier si la personne est âgée d’au moins 18 ans. Si c’est le cas, renvoyez « Vous avez l’âge de boire ! », sinon renvoyez « Pas de chance... ».

   ![Webhooks Image 9](../12-exercises/assets/webhooks-walkthrough-9.png)

1. Créez un filtre entre le routeur et le module de réponse Webhook sur le chemin inférieur. Nommez-le « Le jeton client ne correspond pas. »
1. Pour la condition, utilisez le champ Jeton client du module de déclenchement et effectuez une comparaison numérique « Est égal à » avec le nombre 5 121 933.


   ![Webhooks Image 8](../12-exercises/assets/webhooks-walkthrough-8.png)

1. Cliquez sur le bouton Planification sous Exécuter une fois pour activer votre scénario, de sorte qu’à chaque publication d’un nouveau billet, celui-ci soit reçu, suive l’un ou l’autre des chemins et génère une réponse.
