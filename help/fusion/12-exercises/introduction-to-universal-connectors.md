---
title: Présentation des connecteurs universels
description: Développez votre compréhension de l’utilisation des connecteurs universels REST et de l’utilisation des données renvoyées.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11042
thumbnail: KT11042.png
exl-id: eb442c3e-26f3-44b7-9937-ed4eeba39fb1
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 0%

---

# Présentation des connecteurs universels

Développez votre compréhension de l’utilisation des connecteurs universels REST et de l’utilisation des données renvoyées.

## Présentation de l’exercice

À l’aide d’un caractère Pokemon dans une feuille de calcul, appelez l’API Poke via un connecteur HTTP pour collecter et publier plus d’informations sur ce caractère.

![Présentation des connecteurs universels Image 1](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-1.png)

## Étapes à suivre

**Téléchargez le fichier CSV depuis Workfront.**

1. Dans le dossier Workfront &quot;Fusion Exercise Files&quot;, sélectionnez &quot;_Fusion2020_Shipping Manifest.csv&quot; et cliquez sur Document Details.
1. Copiez le premier numéro d’identifiant de l’adresse URL.
1. Créez un scénario dans Workfront Fusion. Nommez-le &quot;Utilisation de connecteurs universels&quot;.
1. Commencez par télécharger le module de document à partir de l’application Workfront.
1. Configurez votre connexion Workfront et incluez l’ID de document que vous avez copié à partir de l’URL Workfront.
1. Renommez ce module &quot;Télécharger le manifeste d’expédition&quot;.

   ![Présentation des connecteurs universels Image 9](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-9.png)

   **Analysez les données du manifeste d’expédition.**

1. Ajoutez un autre module, en sélectionnant Parse CSV (Analyse CSV).
1. Configurez l’analyse CSV pour 11 colonnes. Cochez la case CSV contient des en-têtes . Sélectionnez le type de délimiteur virgule, puis indiquez les données du module Télécharger le document dans le champ CSV.

   ![Présentation des connecteurs universels Image 2](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-2.png)

1. Renommez ce module &quot;Analyse du manifeste d’expédition&quot;.
1. Enregistrez le scénario et cliquez une fois sur Exécuter pour afficher les données du fichier CSV aux étapes suivantes.

   **Obtenez les données Pokemon à l’aide du connecteur universel.**

1. Ajoutez un module HTTP Make a Request .
1. Dans le champ URL , utilisez `https://pokeapi.co/api/v2/pokemon/[Character]`où [Caractère] est mappé à la colonne 3 à partir du module CSV Parse.
1. Cochez la case Parse response .
1. Sélectionnez Afficher les paramètres avancés, puis cochez la case en regard de &quot;Évaluer tous les états en tant qu’erreurs&quot;.
1. Cliquez sur OK et renommez le module &quot;Get Pokemon info&quot;.

   **Votre panneau de mappage doit ressembler à ceci :**

   ![Présentation des connecteurs universels Image 3](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-3.png)

   **Dans cette partie de l’exercice, vous ne souhaitez traiter que la ligne 1 du fichier CSV.**

1. Ajoutez un filtre avant votre module Get Pokemon info . Nommez-le &quot;Seule la ligne 1&quot;.
1. Définissez la condition de manière à autoriser uniquement la transmission de l’ID 1. L’ID 1 se trouve à la ligne 1 et le champ ID se trouve à la colonne 1 du fichier CSV.

   ![Présentation des connecteurs universels Image 4](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-4.png)

1. Enregistrez le scénario.
1. Cliquez sur Exécuter une fois et observez le message d’erreur que vous recevez dans le module HTTP Make a request.

   >[!IMPORTANT]
   >
   >Notez que dans le champ d’URL des données d’entrée, le nom du caractère est en majuscules. Cela ne fonctionnera pas pour effectuer cet appel API, car les noms de caractères doivent être en minuscules.

   ![Présentation des connecteurs universels Image 5](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-5.png)

1. Utilisez le panneau de mappage dans le champ HTTP Make a request URL (Lancer une URL de requête) pour effectuer l’opération [Caractère] toutes les lettres minuscules en utilisant la propriété **lower** fonction .

   ![Présentation des connecteurs universels Image 6](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-6.png)

   **Mappez les informations de l’API à l’aide du module Définir plusieurs variables .**

1. Ajoutez le module Définir plusieurs variables après Obtenir les informations sur Pokemon . Nom, hauteur, poids et capacités de la carte.
1. Comme le champ Fonctionnalités est un tableau, pensez à utiliser la fonction map pour accéder au nom de chaque fonctionnalité du tableau.

   ![Présentation des connecteurs universels Image 7](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-7.png)

   **Exécutez le scénario sans le filtre pour découvrir une autre erreur.**

1. Pour traiter toutes les lignes du fichier CSV, supprimez le filtre nommé Seule ligne 1 :

   + Cliquez sur l&#39;icône de filtrage pour l&#39;éditer.
   + Supprimez le libellé du filtre.
   + Supprimez la condition.
   + Cliquez sur OK.

1. Enregistrez le scénario et cliquez sur Exécuter une fois.
1. Une erreur se produit dans le module Get Pokemon info. Vous voyez qu’un caractère superhero a été transmis à l’API Pokemon.

   >[!NOTE]
   >
   >Dans la présentation des routeurs, vous verrez comment résoudre cette erreur en créant un chemin distinct pour traiter les super-héros.

   ![Présentation des connecteurs universels Image 8](../12-exercises/assets/introduction-to-universal-connectors-walkthrough-8.png)
