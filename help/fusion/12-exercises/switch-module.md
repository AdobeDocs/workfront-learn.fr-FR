---
title: Module Switch
description: Découvrez comment utiliser le module Switch lorsque vous devez effectuer des transformations de données plus complexes ou dynamiques.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11052
thumbnail: KT11052.png
exl-id: 1b810168-582d-4d7d-b061-d152af546bc8
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '319'
ht-degree: 0%

---

# Module Switch

Découvrez comment utiliser le module Switch lorsque vous devez effectuer des transformations de données plus complexes ou dynamiques.

## Présentation de l’exercice

Recherchez des projets de courrier dans votre lecteur de test, puis modifiez le nom de chaque projet en fonction d’une valeur sélectionnée dans un champ personnalisé associé au projet.

![Image 1 du module Switch](../12-exercises/assets/switch-module-walkthrough-1.png)

## Étapes à suivre

1. Créez un scénario et nommez-le &quot;Utilisation du module Switch&quot;.
1. Pour le module déclencheur, utilisez le module Workfront Search.
1. Configurez votre connexion Workfront et définissez le type d’enregistrement sur Projet.
1. Dans les critères de recherche, indiquez que vous souhaitez uniquement afficher les projets ayant une valeur dans le champ personnalisé Canal .
1. Pour les sorties, sélectionnez ID, Nom, Numéro de référence et le champ personnalisé Canal .

   ![Image 2 du module Switch](../12-exercises/assets/switch-module-walkthrough-2.png)

1. Ajoutez le module Switch à partir des outils.
1. Pour le champ de saisie, mappez le champ personnalisé Canal à partir du module Recherche .

   ![Image du module Switch 3](../12-exercises/assets/switch-module-walkthrough-3.png)

1. Ajoutez ensuite des cas pour chaque valeur possible provenant du champ personnalisé Canal . La valeur possible est placée dans le champ Modèle. Vous souhaitez que le champ de sortie contienne un code à 3 lettres spécifique, suivi du numéro de référence du projet, puis du nom du projet.

   **Votre panneau de mappage doit ressembler à ceci :**

   ![Image 4 du module Switch](../12-exercises/assets/switch-module-walkthrough-4.png)

1. Vous pouvez ajouter autant de cas supplémentaires que vous le souhaitez. Remarquez le champ Sinon en bas. Elle sera utilisée si la valeur d’entrée ne correspond à aucun des cas.

   **Mettez à jour le nom du projet dans Workfront.**

   ![Image du module Switch 5](../12-exercises/assets/switch-module-walkthrough-5.png)

1. Ajoutez un module d’enregistrement de mise à jour Workfront.
1. Dans le champ ID , mappez à l’ID à partir du module de déclenchement.
1. Définissez le Type d’enregistrement sur Projet.
1. Sélectionnez le champ Nom dans la section Sélectionner les champs à mapper , puis mappez-le à la sortie du module Switch .
1. Enregistrez votre scénario et exécutez une fois. Affichez les noms de projet mis à jour dans votre lecteur de test.
