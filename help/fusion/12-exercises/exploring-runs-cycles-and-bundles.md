---
title: Exploration des exécutions, des cycles et des lots
description: Comprendre le comportement des exécutions, des cycles et des lots à l’aide de l’historique d’exécution d’un scénario.
feature: Workfront Fusion
role: User
level: Beginner
kt: 11050
thumbnail: KT1101.png
source-git-commit: c348222464180e994e7b414d1b84e07f58b6b2ae
workflow-type: tm+mt
source-wordcount: '325'
ht-degree: 0%

---


# Exploration des exécutions, des cycles et des lots

Comprendre le comportement des exécutions, des cycles et des lots à l’aide de l’historique d’exécution d’un scénario.

## Présentation de l’exercice

Effectuez des exercices avec différentes configurations de scénario pour explorer l’utilisation d’exécutions et de cycles.

![Exploration des cycles et des lots Image 1](../12-exercises/assets/exploring-runs-cycles-and-bundles-walkthrough-1.png)

## Étapes à suivre

1. Cloner le scénario nommé &quot;Partage de variables entre les chemins de routage&quot;. Nommez le nouveau scénario &quot;Partage de variables entre les chemins de routage - Test Cycles&quot;.
1. Supprimez le module Envoyer un email , car il n’est pas nécessaire pour ce test.

   **Configurez votre scénario pour traiter 3 cycles par exécution. Traitez 5 projets dans chaque cycle.**

1. Cliquez sur le module de déclenchement et définissez le champ Maximal sur 5, de sorte que seuls 5 projets sont traités dans chaque cycle.
1. Dans les critères de recherche, supprimez le second filtre qui limite la recherche à un seul projet.
1. Cliquez sur OK.

1. Dans la barre d’outils Fusion, ouvrez les paramètres du scénario et modifiez le champ Nombre max. de cycles de 1 à 3.
1. Cliquez sur OK.

   ![Exploration des cycles et des lots Image 1](../12-exercises/assets/exploring-runs-cycles-and-bundles-walkthrough-1.png)


   **Planifiez l’exécution du scénario toutes les minutes.**

1. Cliquez sur l’icône de l’horloge en regard du module de déclenchement et définissez le champ Minutes sur 1 minute.

   ![Exploration des cycles et des lots Image 2](../12-exercises/assets/exploring-runs-cycles-and-bundles-walkthrough-2.png)

1. Ensuite, basculez la bascule Planification sur Activé sous le bouton Exécuter une fois . Enregistrez votre scénario.

   ![Exploration des cycles et des lots Image 3](../12-exercises/assets/exploring-runs-cycles-and-bundles-walkthrough-3.png)

1. Accédez à Historique d’exécution pour le scénario et observez un nouvel enregistrement d’historique s’afficher dans la minute suivante. Vous devrez peut-être actualiser la page.

   ![Exploration des cycles et des lots Image 1](../12-exercises/assets/exploring-runs-cycles-and-bundles-walkthrough-4.png)

1. Cliquez sur le bouton Détails d’une exécution. Cliquez sur le lien Connexion simple dans le panneau de droite, comme vous l’avez fait dans la partie Historique d’exécution de la formation Workfront Fusion.
1. Les enregistrements des opérations traitées sont divisés en cycles.

   ![Exploration des cycles et des lots Image 5](../12-exercises/assets/exploring-runs-cycles-and-bundles-walkthrough-5.png)

1. Un menu déroulant en haut à droite de la fenêtre vous permet de sélectionner l’un des trois cycles que vous configurez pour qu’il s’exécute à chaque fois.

   ![Exploration des cycles et des lots Image 6](../12-exercises/assets/exploring-runs-cycles-and-bundles-walkthrough-6.png)
