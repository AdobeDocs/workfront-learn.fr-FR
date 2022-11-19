---
title: Filtres
description: Découvrez comment utiliser le filtre entre les modules pour n’autoriser que certains types de lots par le biais de .
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
kt: 11040
thumbnail: KT1101.png
exl-id: d2cec1ea-7ff9-48ae-8bfb-0c767d346079
source-git-commit: 58a545120b29a5f492344b89b77235e548e94241
workflow-type: tm+mt
source-wordcount: '223'
ht-degree: 0%

---

# Filtres

Découvrez comment utiliser le filtre entre les modules pour n’autoriser que certains types de lots par le biais de .

## Présentation de l’exercice

Ajoutez un filtre entre les deux modules dans le scénario de mappage de base Beyond , afin de créer uniquement les projets dont la couleur de projet &quot;Rouge&quot; figure dans le fichier CSV.

![Filtres Image 1](../12-exercises/assets/filters-walkthrough-1.png)

## Étapes à suivre

1. Créez un clone du scénario &quot;Beyond basic mapping&quot; et nommez-le &quot;Utilisation du puissant filtre&quot;.

   **Ajoutez un filtre avant le module Créer des projets Workfront afin de n’autoriser la création que des projets rouges.**

   ![Filtres Image 2](../12-exercises/assets/filters-walkthrough-2.png)

1. Ajoutez un filtre en cliquant sur la ligne pointillée reliant les modules ou en cliquant sur la clé à molette et en sélectionnant Configurer un filtre.
1. Utilisez le champ Libellé pour nommer le filtre &quot;Projets rouges uniquement&quot;.
1. Dans le champ Condition , mappez le champ Couleur du projet (Colonne 3 dans le fichier CSV). Sélectionnez l’opérateur Egal à (non-respect de la casse), puis saisissez &quot;rouge&quot;.
1. Cliquez sur OK.

   ![Filtres Image 3](../12-exercises/assets/filters-walkthrough-3.png)

   **Testez le filtre et vérifiez les résultats.**

1. Cliquez sur Enregistrer pour enregistrer le scénario, puis sur Exécuter une fois.
1. Cliquez sur l’Inspecteur d’exécution pour le filtre afin de voir comment chaque lot a été examiné par le filtre et transmis ou n’a pas pu passer au module Créer des projets Workfront .

   ![Filtres Image 4](../12-exercises/assets/filters-walkthrough-4.png)

1. Recherchez les projets créés dans votre instance Workfront.
