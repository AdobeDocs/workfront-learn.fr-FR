---
title: Au-delà du mappage de base
description: Découvrez comment utiliser les formules du panneau de mappage pour manipuler ou convertir le ou les champs envoyés à un module.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11039
thumbnail: KT11039.png
exl-id: 979d794d-b936-402e-b07c-71e999f40780
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '302'
ht-degree: 0%

---

# Au-delà du mappage de base

Découvrez comment utiliser les formules du panneau de mappage pour manipuler ou convertir le ou les champs envoyés à un module.

## Présentation de l’exercice

Modifiez le nom du projet, la date de début planifiée et la priorité des exercices de présentation Beyond Basic Mapping à l’aide des formules du panneau de mappage.

![Au-delà de l’image de mappage de base 1](../12-exercises/assets/beyond-basic-mapping-walkthrough-1.png)

## Étapes à suivre

**Effectuez un clone de votre scénario de conception de scénario initial .**

1. Sélectionnez l’option Cloner à droite de la conception du scénario initial dans la section du scénario, comme illustré ci-dessous. Nommez-le &quot;Au-delà du mappage de base&quot;.

   ![Au-delà de l’image de mappage de base 2](../12-exercises/assets/beyond-basic-mapping-walkthrough-2.png)

   **Nous allons maintenant utiliser le panneau de mappage dans le module Créer des projets Workfront pour configurer le nom du projet, la date de début prévue et les champs de priorité.**

1. Cliquez sur le module Créer des projets Workfront pour modifier les paramètres. À l’aide du panneau de mappage, modifiez le champ Nom pour qu’il soit &quot;[Mon nom de projet] par [Sponsor].&quot;

   + Le [Mon nom de projet] est la colonne 1 du module CSV Parse et [Sponsor] correspond à la colonne 6. Le mot &quot;by&quot; est simplement tapé entre les deux.

1. Accédez ensuite à la Date de début planifiée et utilisez la formule addDays pour ajouter 15 jours au champ, comme décrit dans la vidéo Présentation du mappage de base Beyond .
1. Recherchez le champ Priorité et faites basculer le bouton Mapper en haut à droite du champ. Le menu de liste de sélection prend la forme d’un nombre. Créez une instruction if pour étiqueter un projet comme priorité Haute(4) si la note de confiance du fichier CSV est inférieure à 100, sinon elle peut être Normale(2).

   + La note de confiance est indiquée dans la colonne 4.

   **À ce stade, le panneau de mappage doit ressembler à ceci :**

   ![Au-delà de l’image de mappage de base 3](../12-exercises/assets/beyond-basic-mapping-walkthrough-3.png)

1. Cliquez sur OK, puis sur Exécuter une fois.
1. Recherchez le projet dans votre instance Workfront pour vous assurer que tout a été correctement mappé.
1. Enregistrez votre scénario.
