---
title: Définir/Obtenir des variables
description: Découvrez comment utiliser les modules Set et Get Variable pour utiliser les champs disponibles dans un chemin d’accès différent.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11045
thumbnail: KT11045.png
exl-id: 225f0090-0428-40e2-8a4b-9c6b18b205d2
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '628'
ht-degree: 0%

---

# Définir/Obtenir des variables

Découvrez comment utiliser les modules Set et Get Variable pour utiliser les champs disponibles dans un chemin d’accès différent.

## Présentation de l’exercice

Recherchez des informations sur un projet dans Workfront et envoyez un courrier électronique contenant des informations connexes.

![Définition de la variable Get Image 1](../12-exercises/assets/set-get-variables-walkthrough-1.png)

## Étapes à suivre

1. Créez un scénario et nommez-le &quot;Partage de variables entre les chemins de routage&quot;.
1. Pour le déclencheur, sélectionnez le module de recherche dans l’application Workfront.

   + Définissez le Type d’enregistrement sur Projet.
   + Pour le jeu de résultats, sélectionnez Tous les enregistrements correspondants.
   + Pour les critères de recherche, définissez-les sur Status Equal to CUR.
   + Pour les sorties, choisissez ID, Nom, Description et Identifiant du parrain.

   ![Définition de la variable Get Image 2](../12-exercises/assets/set-get-variables-walkthrough-2.png)

   ![Définition de la variable Get image 3](../12-exercises/assets/set-get-variables-walkthrough-3.png)

1. Cliquez sur OK et renommez ce module &quot;Rechercher les projets en cours&quot;.
1. Ajoutez un autre module et sélectionnez le module Lecture d’enregistrement Workfront .

   + Dans le champ Type d’enregistrement, choisissez Utilisateur.
   + Pour Output, choisissez Name.
   + Faites correspondre l’identifiant du parrain du module de recherche au champ Identifiant.

1. Cliquez sur OK.
1. Renommez le module &quot;Rechercher le nom du sponsor&quot;.

   ![Définition de la variable Get Image 4](../12-exercises/assets/set-get-variables-walkthrough-4.png)

1. Enregistrez le scénario et cliquez sur Exécuter une fois.

   Si vous recevez une erreur sur le module Lecture d’un enregistrement , cela est probablement dû au fait que le module Recherche a trouvé un projet sans qu’un sponsor soit répertorié.

   **Pour éviter cette erreur, créez deux chemins : l’un pour les projets qui ont un ID de sponsor et l’autre pour les projets qui n’en ont pas.**

1. Ajoutez un routeur entre les deux modules en cliquant sur l&#39;icône de clé à molette entre le routeur et le module Lire un enregistrement . Configurez un filtre nommé &quot;Le parrain existe&quot; et définissez la condition sur Existe l’identifiant du parrain.

   ![Définition de la variable Get Image 5](../12-exercises/assets/set-get-variables-walkthrough-5.png)

1. Cliquez sur le routeur pour créer un autre chemin. Ajoutez un module Envoyer un courrier électronique à partir de l’application de messagerie.

   + Indiquez votre propre adresse électronique dans le champ À .
   + Dans le champ Objet , saisissez &quot;Informations actuelles sur le projet&quot;.
   + Dans le champ Contenu , indiquez le nom, la description et le sponsor du projet.
   + Vous ne pouvez pas extraire la sortie du nom du sponsor du module Lire un enregistrement . Vous ne pouvez accéder à l&#39;identifiant du sponsor qu&#39;à partir du module de recherche avant le routeur. Vous devrez trouver un moyen d’accéder au nom du sponsor à partir de l’autre chemin du routeur.

   ![Définition de la variable Get Image 6](../12-exercises/assets/set-get-variables-walkthrough-6.png)

1. Cliquez sur OK pour l’instant et renommez ce module &quot;Envoyer les informations du projet&quot;.

   **Utilisez les variables Set/Get pour partager des données entre différents chemins.**

1. Après le module Rechercher le nom du sponsor , ajoutez un module d’outil Définir la variable .

   + Placez &quot;Nom du parrain&quot; comme nom de variable.
   + Laissez la durée de vie de la variable sur Un cycle.
   + Mappez le champ avec la sortie de nom du module Rechercher le nom du sponsor .

1. Cliquez sur OK, puis renommez le module &quot;Définir le nom du parrain&quot;.

   ![Définition de la variable Get Image 7](../12-exercises/assets/set-get-variables-walkthrough-7.png)

1. Cliquez ensuite avec le bouton droit de la souris entre le routeur et le module Envoyer un email pour ajouter un module d&#39;outil Get variable . Saisissez &quot;Nom du parrain&quot; dans le champ Nom de la variable .
1. Cliquez sur OK. Renommez le module &quot;Obtenir le nom du parrain&quot;.

   ![Définition de la variable Get Image 8](../12-exercises/assets/set-get-variables-walkthrough-8.png)

1. Revenez dans le module Envoyer un email et mappez la valeur du module Obtenir le nom du parrain dans le champ de contenu. Cliquez sur OK.

   ![Définition de la variable Get Image 8](../12-exercises/assets/set-get-variables-walkthrough-8.png)

   >[!IMPORTANT]
   >
   >Avant de tester le scénario, nous vous recommandons de limiter le nombre de projets que vous traitez afin d’éviter d’obtenir un déluge d’emails.

1. Accédez à votre programme de test Workfront et localisez le projet Northstar Fashion exposants Booth . Il s’agit d’un projet en cours qui a un sponsor. Copiez l’ID de projet de l’URL.

   ![Définition de l’image Get variables 10](../12-exercises/assets/set-get-variables-walkthrough-10.png)

1. Dans votre scénario, cliquez sur le module Rechercher les projets en cours . Ajoutez une autre condition aux critères de recherche en cliquant sur le bouton vert &quot;Ajouter une règle AND&quot;. Indiquez que l’ID doit être égal à l’ID de projet que vous avez copié. Cliquez sur OK.
1. Enregistrez votre scénario et cliquez sur Exécuter une fois.
1. Examinez les inspecteurs d’exécution et le courrier électronique que vous recevez.

   ![Définition de l’image Get variables 11](../12-exercises/assets/set-get-variables-walkthrough-11.png)
