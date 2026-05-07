---
title: Au-delà de l’exercice sur le mappage de base
description: Découvrez comment utiliser les formules du panneau de mappage pour manipuler ou convertir le ou les champs envoyés à un module.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11039
thumbnail: KT11039.png
recommendations: noDisplay,catalog
exl-id: 979d794d-b936-402e-b07c-71e999f40780
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
subfeature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
autotag-review: '2026-05-06T16:44:57.573Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 314
ht-degree: 100%

---

# Au-delà de l’exercice sur le mappage de base

Découvrez comment utiliser les formules du panneau de mappage pour manipuler ou convertir le ou les champs envoyés à un module.

## Vue d’ensemble de l’exercice

Modifiez le nom du projet, la date de début prévue et la priorité à partir des exercices « Au-delà du mappage de base » en utilisant les formules du panneau de mappage.

![Image 1 - Au-delà du mappage de base.](../12-exercises/assets/beyond-basic-mapping-walkthrough-1.png)

## Étapes à suivre

**Faites un clone de votre conception initiale du scénario.**

1. Sélectionnez l’option Cloner à droite de la conception initiale du scénario dans la section des scénarios, comme indiqué ci-dessous. Nommez-le « Au-delà du mapping de base ».

   ![Image 2 - Au-delà du mappage de base](../12-exercises/assets/beyond-basic-mapping-walkthrough-2.png)

   **Nous allons maintenant utiliser le panneau de mappage du module Créer des projets Workfront pour configurer le nom du projet, la date de début prévue et les champs de priorité.**

1. Cliquez sur le module Créer des projets Workfront pour modifier les paramètres. À l’aide du panneau de mappage, remplacez le champ Nom « [Nom de mon projet] par [Sponsor] ».

   + Le [Nom de mon projet] correspond à la colonne 1 du module Analyse CSV et le [Sponsor] à la colonne 6. Le mot « par » est simplement tapé entre les deux.

1. Passez ensuite à la date de début prévue et utilisez la formule addDays pour ajouter 15 jours au champ, comme décrit dans la vidéo de présentation Au-delà du mappage de base.
1. Recherchez le champ Priorité et activez le bouton Mapper en haut à droite du champ. Le menu de la liste de sélection se transforme en numéro. Créez une instruction If pour qualifier un projet de priorité élevée (4) si l’indice de confiance du fichier CSV est inférieur à 100, sinon il peut être considéré comme normal (2).

   + La cote de confiance figure dans la colonne 4.

   **À ce stade, votre panneau de mappage doit ressembler à celui-ci :**

   ![Image 3 - Au-delà du mappage de base](../12-exercises/assets/beyond-basic-mapping-walkthrough-3.png)

1. Cliquez sur OK, puis sur Exécuter une fois.
1. Recherchez le projet dans votre instance Workfront pour vérifier que tout a été correctement mappé.
1. Enregistrez votre scénario.
