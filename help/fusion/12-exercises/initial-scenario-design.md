---
title: Exercice initial de conception de scénario
description: Découvrez quelques conseils de navigation de base pour votre première connexion à Workfront Fusion, ainsi que pour la construction de votre premier scénario.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11038
thumbnail: KT11038.png
recommendations: noDisplay,noCatalog
exl-id: 8ecf4979-f291-4788-bdaa-ab5485fb0849
source-git-commit: a4e61514567ac8c2b4ad5c9ecacb87bd83947731
workflow-type: tm+mt
source-wordcount: '983'
ht-degree: 99%

---

# Exercice initial de conception de scénario

Découvrez quelques conseils de navigation de base pour votre première connexion à Workfront Fusion, ainsi que pour la construction de votre premier scénario.

## Conditions préalables

1. Cet exercice nécessite un lecteur de test Workfront. Vous pouvez en demander un en remplissant [ce formulaire](https://forms.office.com/r/f1J8HRGrNY). Si vous ne parvenez pas à accéder au formulaire, envoyez votre nom, votre adresse e-mail et le nom de votre entreprise à wfttstdr@adobe.com.
1. Les exercices avec Fusion supposent que vous ayez regardé la vidéo de démonstration correspondant à l’exercice. Dans le cas présent, il s’agit d’une [présentation de la conception initiale d’un scénario](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/fusion/understand-the-basics/initial-scenario-design-walkthrough.html?lang=fr).


## Vue d’ensemble de l’exercice

Créez un nouveau projet dans Workfront pour chaque ligne du fichier CSV de la liste des projets.

![Conception initiale de scénario Image 1](../12-exercises/assets/initial-scenario-design-1.png)

## Étapes à suivre

1. Créez un dossier dans la section Scénario intitulé « Exercices d’habilitation de Fusion ».
1. Cliquez dans le dossier, puis sur Créer un scénario.

   ![Conception initiale de scénario Image 2](../12-exercises/assets/initial-scenario-design-2.png)

1. Sur la page suivante, recherchez Workfront et sélectionnez cette application. Cliquez ensuite sur Continuer.
1. En haut à gauche de l’écran du concepteur de scénario, renommez votre scénario « Conception initiale de scénario ».
1. Cliquez sur le module déclencheur vide au centre de l’écran et sélectionnez l’application Workfront, puis le module Télécharger le document.

   **Authentifiez la connexion du module à votre compte Workfront.**

1. Pour créer une connexion pour la première fois, cliquez sur le bouton Ajouter.

   ![Conception initiale de scénario Image 3](../12-exercises/assets/initial-scenario-design-3.png)

1. Donnez un nom à la connexion, par exemple « Mon Workfront 2020 ».

   ![Conception initiale de scénario Image 4](../12-exercises/assets/initial-scenario-design-4.png)

1. Saisissez l’URL de **votre instance Workfront**, puis cliquez sur Suivant.

   ![Conception initiale de scénario Image 5](../12-exercises/assets/initial-scenario-design-5.png)

1. Saisissez votre mot de passe et cliquez sur Se connecter.

   **La connexion est établie. Saisissez maintenant l’identifiant du document que vous souhaitez télécharger à partir de Workfront.**

   ![Conception initiale de scénario Image 7](../12-exercises/assets/initial-scenario-design-7.png)

1. Retournez à Workfront. Dans le dossier « Fichiers d’exercice Fusion », sélectionnez « _Fusion2020_Project List.csv » et cliquez sur Détails du document dans le panneau de gauche. Copiez le numéro d’identifiant de document à partir de l’adresse URL (il s’agit du premier numéro long de l’URL).

   ![Conception initiale du scénario Image 8](../12-exercises/assets/initial-scenario-design-8.png)

1. Revenez à Fusion et collez le numéro dans le champ d’identifiant du document, puis cliquez sur OK.
1. Une bonne pratique consiste à renommer les modules au fur et à mesure que vous les créez. Cliquez avec le bouton droit de la souris sur le module Workfront et choisissez Renommer. Nommez le module « Obtenir la liste des projets ».

   **Ensuite, vous allez analyser le fichier CSV que vous venez de télécharger afin de pouvoir accéder à chaque ligne du fichier. Vous utiliserez ces informations lorsque vous créerez un projet à partir de chaque ligne.**

1. Cliquez sur le côté droit du module Workfront pour ajouter un autre module. Recherchez l’application CSV et sélectionnez le module Analyse CSV.
1. Configurez l’analyse CSV pour 6 colonnes, cochez CSV contient des en-têtes (CSV contains headers), définissez le type de délimiteur sur virgule (comma), et saisissez Données (Data) dans le champ CSV. Cliquez ensuite sur OK.

   ![Conception initiale du scénario Image 9](../12-exercises/assets/initial-scenario-design-9.png)

1. Renommez ce module « Analyser la liste de projets ».
1. Au bas du concepteur de scénarios, cliquez sur Enregistrer pour enregistrer votre scénario.
1. Cliquez sur Exécuter une fois pour afficher la sortie.

   >[!NOTE]
   >
   >Ignorez l’avertissement indiquant qu’un transformateur ne doit pas être le dernier module (c’est vrai, mais cela n’a pas d’importance pour ce test). Cliquez sur Exécuter quand même.

   ![Conception initiale du scénario Image 10](../12-exercises/assets/initial-scenario-design-10.png)

1. Ouvrez l&#39;inspecteur d’exécution dans le module Analyse CSV pour voir les entrées et les sorties du module. Il existe un bundle (un fichier CSV) en entrée et plusieurs bundles en sortie (un bundle pour chaque ligne du fichier CSV). Il devrait ressembler à ceci :

   ![Conception initiale du scénario Image 11](../12-exercises/assets/initial-scenario-design-11.png)

   **Ajoutez un module pour créer un projet pour chaque ligne du fichier CSV.**

1. Ajoutez un autre module. Sélectionnez l’application Workfront, en choisissant le module Créer un enregistrement.
1. Définissez le type d’enregistrement sur Projet.

   >[!TIP]
   >
   >Recherchez celui-ci en commençant par saisir quelques lettres, telles que *proj*, pour y accéder directement.

1. Utilisez ensuite Cmd/Ctrl+G pour trouver Nom (nom du projet). Cochez la case à côté de Nom : le champ apparaît en dessous.
1. Cochez maintenant les cases situées à côté de la date de début prévue et de la priorité.
1. Cliquez dans le champ Nom pour faire apparaître le panneau de mappage. Cliquez sur le champ Colonne 1 du module Analyse CSV pour l’ajouter au champ Nom. Il s’agit du nom du projet issu du fichier CSV.
1. Pour la date de début prévue, cliquez sur la colonne 5 du module Analyse CSV.
1. Pour la Priorité, sélectionnez Normale dans le menu déroulant.

   **Votre panneau de mappage devrait ressembler à ceci :**

   ![Conception initiale du scénario Image 12](../12-exercises/assets/initial-scenario-design-12.png)

1. Cliquez sur OK.

   >[!NOTE]
   >
   >Si vous ne cliquez pas sur OK et que vous revenez accidentellement dans le concepteur, votre travail ne sera pas sauvegardé et vous devrez recommencer le mappage.

1. Cliquez avec le bouton droit de la souris sur le module Workfront et renommez-le en « Créer des projets Workfront ».
1. Enregistrez votre scénario et cliquez sur le bouton Exécuter une fois.
1. Cliquez sur l’Inspecteur d’exécution en haut à droite du dernier module.

   + Vous pourrez voir que 20 opérations ont été effectuées. Chaque opération a pris un bundle, c’est-à-dire une ligne, du fichier CSV en tant qu’entrée, et a sorti un bundle, constitué d’un projet créé dans Workfront. L’ID du projet créé apparaît avec le bundle de sortie.

   ![Conception initiale du scénario Image 13](../12-exercises/assets/initial-scenario-design-13.png)

   **Utilisation des notes**

1. Les notes permettent de créer plus de visibilité dans la conception du scénario. Pour ajouter une note au module Créer des projets Workfront, cliquez avec le bouton droit de la souris et sélectionnez Ajouter une note. Un panneau situé à droite de la fenêtre du concepteur s’ouvre pour vous permettre d’ajouter une note au module. Saisissez « Créer un projet avec le nom, la date de début prévue et la priorité mappés à partir du fichier CSV ».
1. Ajoutez une autre note pour décrire ce que fait le module déclencheur (le premier module Workfront).
1. Fermez le panneau des notes en cliquant sur le X dans le coin supérieur droit.

   + Accédez à nouveau aux notes en cliquant sur le bouton Notes dans la barre d’outils inférieure ou en cliquant avec le bouton droit de la souris sur un module et en ajoutant une nouvelle note.
   + Les notes sont triées par ordre chronologique inverse.
   + Un point orange apparaît sur le bouton Notes lorsque des notes sont ajoutées.

   ![Conception initiale du scénario Image 14](../12-exercises/assets/initial-scenario-design-14.png)

1. Enregistrez le scénario en cliquant sur le bouton Enregistrer dans la barre d’outils des commandes.
1. Vous pouvez afficher les projets créés dans votre instance Workfront.
