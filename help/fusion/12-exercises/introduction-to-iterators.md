---
title: Présentation des itérateurs
description: Découvrez comment utiliser des applications de type itération et exécuter des actions sur chaque lot d’informations.
feature: Workfront Fusion
role: User
level: Beginner
kt: 11046
thumbnail: KT11046.png
source-git-commit: f367e016498d5c1814cab79e19e6e9001db2851f
workflow-type: tm+mt
source-wordcount: '381'
ht-degree: 0%

---


# Présentation des itérateurs

Découvrez comment utiliser des applications de type itération et exécuter des actions sur chaque lot d’informations.

## Présentation de l’exercice

Examinez un projet spécifique dans Workfront, puis toutes les tâches qu’il contient. Vous utiliserez le module d’outil d’incrémentation pour compter le nombre de tâches dans le projet. Enfin, vous utiliserez le module Définir la variable pour soustraire le Nombre d’enfants du Nombre de problèmes en cours afin de produire une valeur numérique pour chacun des lots de tâches.

![Présentation des itérateurs Image 1](../12-exercises/assets/introduction-to-iterators-walkthrough-1.png)

## Étapes à suivre

**Lisez un projet et les tâches associées.**

1. Démarrez un nouveau scénario. Nommez-le &quot;Introduction à l’itération&quot;.
1. Sélectionnez Workfront comme module déclencheur, Lire un enregistrement.
1. Pour Type d’enregistrement, sélectionnez Projet.
1. Pour les sorties, choisissez ID, Nom et Description.
1. Dans le champ ID , indiquez l’ID du projet Northstar Fashion exposants Booth à partir de votre instance de lecteur de test Workfront.
1. Renommez ce module &quot;Rechercher des projets WF&quot;.
1. Ajoutez un autre module Workfront pour lire les tâches liées à ce projet. Sélectionnez le module Lecture des enregistrements associés .
1. Pour Type d’enregistrement, sélectionnez Projet.
1. Pour l’identifiant d’enregistrement parent, sélectionnez l’identifiant dans le module Lire un enregistrement .
1. Pour Collections, sélectionnez Tâches.
1. Pour les sorties, sélectionnez ID, Nom, Description, Nombre d’enfants, Nombre de problèmes en cours et Travail.
1. Renommez ce module &quot;Lire les tâches du projet&quot;.
1. Enregistrez le scénario, puis cliquez sur Exécuter une fois pour afficher les sorties.

   + Cliquez sur l’Inspecteur d’exécution et vous voyez un lot comme entrée (le projet) et 28 lots comme sortie (les tâches).

   **Comptez et traitez les lots itérés.**

1. Ajoutez un autre module après Lire les enregistrements associés. Choisissez un module d’outils de fonction Incrémenter .

   + Laissez le champ Réinitialiser une valeur sur Jamais et cliquez sur OK.

1. Renommez ce module &quot;Comptez le nombre de tâches&quot;.
1. Ajoutez un module Définir la variable . Définissez le nom de la variable sur &quot;Random Math&quot;.
1. Dans le champ Valeur de la variable , soustrayez le nombre d’enfants ouverts du nombre de tâches publiques ouvertes.

   **Il doit ressembler à ceci :**

   ![Présentation des itérateurs Image 2](../12-exercises/assets/introduction-to-iterators-walkthrough-2.png)

1. Renommez ce module &quot;Mathématiques aléatoires&quot;.
1. Enregistrez le scénario et cliquez sur Exécuter une fois.

Pour chacune des tâches générées par le module d’itérateur Read Related Records, Workfront Fusion a effectué 28 exécutions. Ces 28 lots continueront à être traités tout au long du scénario, sauf si un agrégateur est ajouté pour fermer la boucle.