---
title: Exercice sur les filtres
description: Découvrez comment utiliser le filtre entre les modules pour n’autoriser que certains types de bundles.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11040
thumbnail: KT1101.png
recommendations: noDisplay,catalog
exl-id: d2cec1ea-7ff9-48ae-8bfb-0c767d346079
source-git-commit: f033b210268e8979ee15abe812e6ad85673eeedb
workflow-type: ht
source-wordcount: '0'
ht-degree: 100%

---

# Exercice sur les filtres

Découvrez comment utiliser le filtre entre les modules pour n’autoriser que certains types de bundles.

## Vue d’ensemble de l’exercice

Ajoutez un filtre entre les deux modules dans le scénario Au-delà du mappage de base pour créer uniquement des projets dont la couleur de projet est « Rouge » dans le fichier CSV.

![Image de Filtres 1](../12-exercises/assets/filters-walkthrough-1.png)

## Étapes à suivre

1. Créez un clone du scénario « Au-delà du mappage de base » et nommez-le « Utilisation du filtre puissant ».

   **Ajoutez un filtre avant le module Créer des projets Workfront afin de n’autoriser la création que de projets rouges.**

   ![Image de Filtres 2](../12-exercises/assets/filters-walkthrough-2.png)

1. Ajoutez un filtre en cliquant sur la ligne pointillée reliant les modules ou en cliquant sur la clé à molette et en sélectionnant Configurer un filtre.
1. Utilisez le champ Libellé pour nommer le filtre « Projets rouges uniquement ».
1. Dans le champ Condition, mappez le champ Couleur du projet (colonne 3 dans le fichier CSV). Sélectionnez l’opérateur Égal à (non sensible à la casse), puis saisissez « rouge ».
1. Cliquez sur OK.

   ![Image de Filtres 3](../12-exercises/assets/filters-walkthrough-3.png)

   **Testez le filtre et vérifiez les résultats.**

1. Cliquez sur Enregistrer pour enregistrer le scénario, puis sur Exécuter une fois.
1. Cliquez sur l’Inspecteur d’exécution relatif au filtre afin de voir comment chaque bundle a été traité par le filtre et s’il a pu être déplacé ou non vers le module Créer des projets Workfront.

   ![Image de Filtres 4](../12-exercises/assets/filters-walkthrough-4.png)

1. Recherchez les projets créés dans votre instance Workfront.
