---
title: Exercice sur les modèles de routage
description: Renforcez votre concept de routage et d’itinéraires d’abandon sans utiliser d’autres API.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11044
thumbnail: KT11044.png
recommendations: noDisplay,catalog
exl-id: d8218115-5180-4e64-8ec1-d2d6afc88d23
source-git-commit: f033b210268e8979ee15abe812e6ad85673eeedb
workflow-type: ht
source-wordcount: '0'
ht-degree: 100%

---

# Exercice sur les modèles de routage

Renforcez votre concept de routage et d’itinéraires d’abandon sans utiliser d’autres API.

## Vue d’ensemble de l’exercice

Utilisez le module Définir la variable pour envoyer un nombre à travers plusieurs chemins afin de voir comment se comportent les filtres et les abandons lors du routage.

![Modèles de routage, image 1](../12-exercises/assets/routing-patterns-walkthrough-1.png)

## Étapes à suivre

1. Créez un nouveau scénario et appelez-le « Modèles de routage et abandons ».
1. Pour le déclencheur, ajoutez le module d’outils Définir la variable. Saisissez « Mon numéro » pour le nom de la variable, laissez la durée de vie de la variable sur Un cycle, puis définissez le champ Variable sur « 75 ».

   ![Modèles de routage, image 2](../12-exercises/assets/routing-patterns-walkthrough-2.png)

1. Ajoutez un autre module et choisissez le module Routeur. Pour les deux chemins, sélectionnez l’outil de fonction Incrémenter et cliquez sur OK sans apporter de modifications pour aucun d’eux.

   + Pour le premier chemin, créez un filtre, nommez-le « Inférieur à 100 », puis définissez la condition de [Mon numéro] sur Inférieur à 100.

   + Pour le deuxième chemin, créez un filtre, nommez-le « Inférieur à 1000 » et définissez la condition de [Mon numéro] sur Inférieur à 1000. Veillez à utiliser l’opérateur numérique pour les deux.

   ![Modèles de routage, image 3](../12-exercises/assets/routing-patterns-walkthrough-3.png)

   ![Modèles de routage, image 4](../12-exercises/assets/routing-patterns-walkthrough-4.png)

1. Cliquez sur Exécuter une fois et regardez le bundle transmettre le chemin « Inférieur à 100 ».
1. Remplacez ensuite le champ du module Définir la variable sur 950 et cliquez à nouveau sur Exécuter une fois. Regardez-le parcourir le deuxième chemin.
1. Cliquez sur le routeur et ajoutez un chemin supplémentaire. Ajoutez le module d’outil de la fonction Incrémenter. Pour le filtre, cliquez sur la case à cocher « Itinéraire d’abandon ». Notez comment la flèche pointant vers ce chemin se transforme en accent circonflexe, indiquant qu’il s’agit de l’itinéraire d’abandon.

   ![Modèles de routage, image 5](../12-exercises/assets/routing-patterns-walkthrough-5.png)

1. Modifiez le numéro de Définir la variable en 9500 et cliquez sur Exécuter une fois. Comme le nombre n’est pas inférieur à 100 ou à 1000, le bundle emprunte l’itinéraire d’abandon.

Si vous ajoutez un chemin supplémentaire à l’aide d’un module d’outil de la fonction Incrémenter, mais que vous ne définissez aucun filtre, que se passera-t-il lorsque vous cliquerez à nouveau sur Exécuter une fois ? Un bundle pourra-t-il emprunter l’itinéraire d’abandon avec le quatrième itinéraire ajouté ?

+ Non, car sans filtre défini, chaque bundle va toujours suivre ce chemin au lieu de l’itinéraire d’abandon.
