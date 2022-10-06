---
title: Fonction Switch
description: Découvrez comment utiliser la fonctionnalité de commutation à l’aide de la fonction Switch .
feature: Workfront Fusion
role: User
level: Beginner
kt: 11051
thumbnail: KT1101.png
source-git-commit: f367e016498d5c1814cab79e19e6e9001db2851f
workflow-type: tm+mt
source-wordcount: '234'
ht-degree: 0%

---


# Fonction Switch

Découvrez comment utiliser la fonctionnalité de commutation à l’aide de la fonction Switch .

## Présentation de l’exercice

Pour de simples modifications de données, utilisez la fonction Switch afin de transformer une valeur en une autre au sein d’un champ de module. Dans cet exercice, remplacez la clé à deux lettres par le nom réel de l’état d’avancement du projet à envoyer dans un courrier électronique.

![Changer de fonction Image 1](../12-exercises/assets/switch-function-walkthrough-1.png)

## Étapes à suivre

1. Cloner le scénario nommé &quot;Partage de variables entre les chemins de routage&quot;.
1. Nommez le nouveau scénario &quot;Partage de variables entre chemins de routage - Changement&quot;.
1. Cliquez sur le module de déclenchement et ajoutez État de progression à la section Sorties .
1. Dans le module Envoyer un email, ajoutez Etat d&#39;avancement au champ Contenu .

   + Si vous mappez simplement la valeur provenant du module de recherche, il existe un code à deux lettres pour l’état de progression.
   + Pour &quot;changer&quot; le code pour le nom complet de chaque état de progression possible, utilisez la fonction &quot;changer&quot; de l&#39;onglet Fonctions générales .

1. La fonction switch utilise la valeur ou l’expression Etat de progression comme clé, puis renvoie la valeur de sortie en fonction de cette clé.

   + Une valeur clé est définie dans la première position après l’état de progression (&quot;LT&quot;) avec la sortie correspondante définie dans la seconde position (&quot;En retard&quot;).
   + La valeur de la clé suivante est définie à la troisième position, la sortie correspondante étant définie à la quatrième position, etc., pour autant de clés que vous le souhaitez.

      ![Changer de fonction Image 2](../12-exercises/assets/switch-function-walkthrough-2.png)