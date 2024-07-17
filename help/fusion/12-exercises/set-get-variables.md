---
title: Exercice sur les variables Set/Get
description: Découvrez comment utiliser les modules Définir et Obtenir la variable pour utiliser les champs disponibles dans un chemin au sein d’un chemin différent.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11045
thumbnail: KT11045.png
recommendations: noDisplay,noCatalog
exl-id: 225f0090-0428-40e2-8a4b-9c6b18b205d2
source-git-commit: a4e61514567ac8c2b4ad5c9ecacb87bd83947731
workflow-type: tm+mt
source-wordcount: '641'
ht-degree: 100%

---

# Exercice sur les variables Set/Get

Découvrez comment utiliser les modules Définir et Obtenir la variable pour utiliser les champs disponibles dans un chemin au sein d’un chemin différent.

## Vue d’ensemble de l’exercice

Recherchez des informations sur un projet dans Workfront et envoyez un e-mail contenant des informations connexes.

![Définir et Obtenir des variables Image 1](../12-exercises/assets/set-get-variables-walkthrough-1.png)

## Étapes à suivre

1. Créez un scénario et nommez-le « Partage de variables entre des chemins de routage ».
1. Pour le déclencheur, sélectionnez le module de recherche dans l’application Workfront.

   + Définissez le Type d’enregistrement sur Projet.
   + Pour le jeu de résultats, sélectionnez Tous les enregistrements correspondants.
   + Pour les critères de recherche, définissez-les sur Statut égal à actuel.
   + Pour les sorties, choisissez ID, Nom, Description et Identifiant du sponsor.

   ![Définir et Obtenir des variables Image 2](../12-exercises/assets/set-get-variables-walkthrough-2.png)

   ![Définir et Obtenir des variables Image 3](../12-exercises/assets/set-get-variables-walkthrough-3.png)

1. Cliquez sur OK et renommez ce module « Rechercher les projets en cours ».
1. Ajoutez un autre module et sélectionnez le module Workfront Lire un enregistrement.

   + Dans le champ Type d’enregistrement, choisissez Utilisateur ou utilisatrice.
   + Pour Sorties, choisissez Nom.
   + Mappez l’ID du sponsor du module de recherche sur le champ ID.

1. Cliquez sur OK.
1. Renommez le module « Rechercher le nom du sponsor ».

   ![Définir et Obtenir des variables Image 4](../12-exercises/assets/set-get-variables-walkthrough-4.png)

1. Enregistrez le scénario et cliquez sur Exécuter une fois.

   Si vous recevez une erreur à propos du module Lire un enregistrement , cela est probablement dû au fait que le module Rechercher a trouvé un projet sans qu’un sponsor soit répertorié.

   **Pour éviter cette erreur, créez deux chemins : un pour les projets qui ont un ID de sponsor et un autre pour les projets qui n’en ont pas.**

1. Ajoutez un routeur entre les deux modules en cliquant sur l’icône de la clé à molette entre le routeur et le module Lire un enregistrement. Configurez un filtre nommé « Sponsor présent » et définissez la condition sur ID de sponsor présent.

   ![Définir et Obtenir des variables Image 5](../12-exercises/assets/set-get-variables-walkthrough-5.png)

1. Cliquez sur le routeur pour créer un autre chemin. Ajoutez un module Envoyer un e-mail à partir de l’application de messagerie.

   + Indiquez votre propre adresse e-mail dans le champ À.
   + Dans le champ Objet, saisissez « Informations sur le projet actuel ».
   + Dans le champ Contenu, indiquez le nom, la description et le sponsor du projet.
   + Il n’est pas possible d’extraire le nom du sponsor du module Lire un enregistrement. Vous ne pouvez accéder à l’ID du sponsor qu’à partir du module de recherche avant le routeur. Vous devrez trouver un moyen d’accéder au nom du sponsor à partir de l’autre chemin du routeur.

   ![Définir et ibtenir des variables Image 6](../12-exercises/assets/set-get-variables-walkthrough-6.png)

1. Cliquez sur OK pour l’instant, puis renommez ce module « Envoyer les informations du projet ».

   **Utilisez Définir/Obtenir des variables pour partager des données entre différents chemins.**

1. Après le module Trouver le nom du sponsor, ajoutez un module d’outil Définir la variable.

   + Placez « Nom du sponsor » comme Nom de variable.
   + Laissez la durée de vie de la variable sur Un cycle.
   + Mappez le champ sur la sortie de nom du module Trouver le nom du sponsor.

1. Cliquez sur OK, puis renommez le module « Définir le nom du sponsor ».

   ![Définir et obtenir des variables Image 7](../12-exercises/assets/set-get-variables-walkthrough-7.png)

1. Ensuite, cliquez avec le bouton droit de la souris entre le routeur et le module Envoyer un e-mail pour ajouter un module d’outil Obtenir la variable. Saisissez « Nom du sponsor » dans le champ Nom de la variable.
1. Cliquez sur OK. Renommez le module « Obtenir le nom du sponsor ».

   ![Définir et obtenir des variables Image 8](../12-exercises/assets/set-get-variables-walkthrough-8.png)

1. Retournez dans le module Envoyer un e-mail et mappez la valeur du module Obtenir le nom du sponsor dans le champ de contenu. Cliquez sur OK.

   ![Définir et obtenir des variables Image 8](../12-exercises/assets/set-get-variables-walkthrough-8.png)

   >[!IMPORTANT]
   >
   >Avant de tester le scénario, nous vous recommandons de limiter le nombre de projets que vous traitez afin d’éviter d’obtenir un déluge d’e-mails.

1. Accédez à votre lecteur de test Workfront et localisez le projet Northstar Fashion Exhibitors Booth. Il s’agit d’un projet en cours qui a un sponsor. Copiez l’ID de projet de l’URL.

   ![ Image 10 - Définition des variables GET](../12-exercises/assets/set-get-variables-walkthrough-10.png)

1. Dans votre scénario, cliquez sur le module Rechercher les projets en cours. Ajoutez une autre condition aux critères de recherche en cliquant sur le bouton vert « Ajouter une règle AND ». Précisez que l’ID doit correspondre à l’ID du projet que vous avez copié. Cliquez sur OK.
1. Enregistrez votre scénario et cliquez sur Exécuter une fois.
1. Examinez les inspecteurs d’exécution et prenez connaissance de l’e-mail que vous avez reçu.

   ![ Image 11 - Définition des variables GET](../12-exercises/assets/set-get-variables-walkthrough-11.png)
