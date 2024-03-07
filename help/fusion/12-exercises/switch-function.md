---
title: Exercice sur la fonction Switch
description: Découvrez comment utiliser la fonctionnalité Switch à l’aide de la fonction Switch.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11051
thumbnail: KT1101.png
recommendations: noDisplay,noCatalog
exl-id: 3142fae2-5210-4f63-9d2c-66dec58867fa
source-git-commit: a4e61514567ac8c2b4ad5c9ecacb87bd83947731
workflow-type: ht
source-wordcount: '238'
ht-degree: 100%

---

# Exercice sur la fonction Switch

Découvrez comment utiliser la fonctionnalité Switch à l’aide de la fonction Switch.

## Vue d’ensemble de l’exercice

Pour de simples modifications de données, utilisez la fonction Switch pour transformer une valeur en une autre dans un champ de module. Dans cet exercice, remplacez la clé à deux lettres par le nom réel du statut de la progression du projet à envoyer dans un e-mail.

![Fonction switch Image 1](../12-exercises/assets/switch-function-walkthrough-1.png)

## Étapes à suivre

1. Clonez le scénario nommé « Partage de variables entre les chemins de routage ».
1. Nommez le nouveau scénario « Partage de variables entre les chemins de routage - Switch ».
1. Cliquez sur le module de déclenchement et ajoutez Statut de la progression à la section Sorties.
1. Dans le module Envoyer un e-mail, ajoutez Statut de progression au champ Contenu.

   + Si vous mappez simplement la valeur provenant du module de recherche, il existe un code à deux lettres pour le statut de progression.
   + Pour « changer » le code en nom complet de chaque statut de progression possible, utilisez la fonction « switch » de l’onglet Fonctions générales.

1. La fonction switch utilise la valeur ou l’expression Statut de la progression comme clé, puis renvoie la valeur de sortie en fonction de cette clé.

   + Une valeur clé est définie dans la première position après le statut de la progression (« LT ») avec la sortie correspondante définie dans la seconde position (« En retard »).
   + La valeur de la clé suivante est définie à la troisième position, la sortie correspondante étant définie à la quatrième position, etc., pour autant de clés que vous le souhaitez.

     ![Fonction switch Image 2](../12-exercises/assets/switch-function-walkthrough-2.png)
