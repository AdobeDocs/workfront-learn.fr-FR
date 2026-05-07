---
title: Exercice sur le module Switch
description: Découvrez comment utiliser le module Switch lorsque vous devez effectuer des transformations de données plus complexes ou dynamiques.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11052
thumbnail: KT11052.png
recommendations: noDisplay,catalog
exl-id: 1b810168-582d-4d7d-b061-d152af546bc8
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
autotag-review: '2026-05-06T16:40:26.747Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 327
ht-degree: 100%

---

# Exercice sur le module Switch

Découvrez comment utiliser le module Switch lorsque vous devez effectuer des transformations de données plus complexes ou dynamiques.

## Vue d’ensemble de l’exercice

Recherchez des projets de publipostage direct dans votre lecteur de test, puis modifiez le nom de chaque projet en fonction d’une valeur sélectionnée dans un champ personnalisé associé au projet.

![Module Switch image 1](../12-exercises/assets/switch-module-walkthrough-1.png)

## Étapes à suivre

1. Créez un scénario et nommez-le « Utilisation du module Switch ».
1. Pour le module déclencheur, utilisez le module Recherche de Workfront.
1. Configurez votre connexion Workfront et définissez le type d’enregistrement sur Projet.
1. Dans les critères de recherche, indiquez que vous souhaitez uniquement afficher les projets ayant une valeur dans le champ personnalisé Canal.
1. Pour les sorties, sélectionnez ID, Nom, Numéro de référence et le champ personnalisé Canal.

   ![Module Switch image 2](../12-exercises/assets/switch-module-walkthrough-2.png)

1. Ajoutez le module Switch à partir des outils.
1. Pour le champ de saisie, mappez le champ personnalisé Canal à partir du module Recherche.

   ![Module Switch image 3](../12-exercises/assets/switch-module-walkthrough-3.png)

1. Ajoutez ensuite des cas pour chaque valeur possible provenant du champ personnalisé Canal. La valeur possible est indiquée dans le champ Motif. Il est préférable que le champ de sortie contienne un code à 3 lettres spécifique, suivi du numéro de référence du projet, puis du nom du projet.

   **Votre panneau de mappage doit ressembler à ceci :**

   ![Module Switch image 4](../12-exercises/assets/switch-module-walkthrough-4.png)

1. Vous pouvez ajouter autant de cas supplémentaires que vous le souhaitez. Remarquez le champ Autres au bas de la page. Il sera utilisé si la valeur d’entrée ne correspond à aucun des cas.

   **Mettez à jour le nom du projet dans Workfront.**

   ![Module Switch image 5](../12-exercises/assets/switch-module-walkthrough-5.png)

1. Ajoutez un module d’enregistrement de mise à jour Workfront.
1. Dans le champ ID, mappez à l’ID à partir du module de déclenchement.
1. Définissez le Type d’enregistrement sur Projet.
1. Sélectionnez le champ Nom dans la section Sélectionner les champs à mapper, puis mappez-le à la sortie du module Switch.
1. Enregistrez votre scénario et exécutez-le une fois. Affichez les noms de projet mis à jour dans votre lecteur de test.
