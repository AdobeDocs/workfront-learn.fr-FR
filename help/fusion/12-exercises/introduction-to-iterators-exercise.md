---
title: Présentation de l’exercice d’itérateurs
description: Découvrez comment utiliser des applications de type itération et exécuter des actions sur chaque lot d’informations.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11046
thumbnail: KT11046.png
recommendations: noDisplay,noCatalog
exl-id: 8d751885-372a-4716-9542-079cc3d36caf
source-git-commit: a4e61514567ac8c2b4ad5c9ecacb87bd83947731
workflow-type: tm+mt
source-wordcount: '388'
ht-degree: 100%

---

# Présentation de l’exercice d’itérateurs

Découvrez comment utiliser des applications de type itération et exécuter des actions sur chaque lot d’informations.

## Vue d’ensemble de l’exercice

Examinez un projet spécifique dans Workfront, puis toutes les tâches de ce projet. Vous utiliserez le module d’outil d’incrémentation pour compter le nombre de tâches dans le projet. Enfin, vous utiliserez le module Définir la variable pour soustraire le Nombre d’enfants du Nombre de problèmes en cours afin de produire une valeur numérique pour chacun des lots de tâches.

![Présentation des itérateurs image 1](../12-exercises/assets/introduction-to-iterators-walkthrough-1.png)

## Étapes à suivre

**Lisez un projet et les tâches associées.**

1. Démarrez un nouveau scénario. Nommez-le « Introduction à l’itération ».
1. Sélectionnez Workfront comme module déclencheur, Lire un enregistrement.
1. Pour Type d’enregistrement, sélectionnez Projet.
1. Pour les sorties, choisissez ID, Nom et Description.
1. Dans le champ ID, indiquez l’ID du projet « Northstar Fashion Exhibitors Booth » à partir de votre instance de lecteur de test Workfront.
1. Renommez ce module « Rechercher des projets WF ».
1. Ajouter un autre module Workfront pour lire les tâches liées à ce projet. Sélectionnez le module Lire les enregistrements associés.
1. Pour Type d’enregistrement, sélectionnez Projet.
1. Pour l’identifiant d’enregistrement parent, sélectionnez l’identifiant dans le module Lire un enregistrement.
1. Pour Collections, sélectionnez Tâches.
1. Pour les sorties, sélectionnez ID, Nom, Description, Nombre d’enfants, Nombre de problèmes en cours et Travail.
1. Renommez ce module « Lire les tâches du projet ».
1. Enregistrez le scénario puis cliquez sur Exécuter une fois pour afficher les sorties.

   + Cliquez sur l’Inspecteur d’exécution : vous voyez un lot en entrée (le projet) et 28 lots en sortie (les tâches).

   **Comptez et traitez les lots itérés.**

1. Ajoutez un autre module après Lire les enregistrements associés. Choisissez un module d’outils de fonction Incrémenter.

   + Laissez le champ Réinitialiser une valeur sur Jamais et cliquez sur OK.

1. Renommez ce module « Compter le nombre de tâches ».
1. Ajoutez un module Définir la variable. Définissez le nom de la variable sur « Math aléatoire ».
1. Dans le champ Valeur de la variable, soustrayez le nombre d’enfants ouverts du nombre d’Optasks ouvertes.

   **Il doit ressembler à ceci :**

   ![Présentation des itérateurs image 2](../12-exercises/assets/introduction-to-iterators-walkthrough-2.png)

1. Renommez ce module « Math aléatoire ».
1. Enregistrez le scénario et cliquez sur Exécuter une fois.

Pour chacune des tâches produites par le module itérateur Lire les enregistrements associés, Workfront Fusion a effectué 28 exécutions. Ces 28 lots continueront à être traités tout au long du scénario, sauf si un agrégateur est ajouté pour fermer la boucle.
