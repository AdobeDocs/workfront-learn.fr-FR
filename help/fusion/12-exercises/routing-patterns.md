---
title: Modèles de routage
description: Renforcer votre concept d’acheminement et d’itinéraires de secours sans réellement traiter avec d’autres API.
feature: Workfront Fusion
role: User
level: Beginner
kt: 11044
thumbnail: KT11044.png
source-git-commit: c348222464180e994e7b414d1b84e07f58b6b2ae
workflow-type: tm+mt
source-wordcount: '344'
ht-degree: 0%

---


# Modèles de routage

Renforcer votre concept d’acheminement et d’itinéraires de secours sans réellement traiter avec d’autres API.

## Présentation de l’exercice

Utilisez le module Set Variable (Définir la variable) pour envoyer un nombre à travers plusieurs chemins afin de visualiser le comportement des filtres et des secours lors du routage.

![Modèles de routage Image 1](../12-exercises/assets/routing-patterns-walkthrough-1.png)

## Étapes à suivre

1. Créez un nouveau scénario et appelez-le &quot;Modèles de routage et abandons&quot;.
1. Pour le déclencheur, ajoutez le module d’outil Définir la variable . Saisissez &quot;Mon numéro&quot; pour le nom de la variable, laissez la durée de vie de la variable comme un cycle, puis définissez le champ Variable sur &quot;75&quot;.

   ![Modèles de routage Image 2](../12-exercises/assets/routing-patterns-walkthrough-2.png)

1. Ajoutez un autre module et choisissez le module routeur. Pour les deux chemins, sélectionnez l’outil de fonction Incrémenter et cliquez sur OK sans apporter de modifications pour chacun d’eux.

   + Pour le premier chemin, créez un filtre, nommez-le &quot;Inférieur à 100&quot;, puis définissez la condition sur [Mon numéro] Moins de 100.

   + Pour le deuxième chemin, créez un filtre, nommez-le &quot;Inférieur à 1 000&quot;, puis définissez la condition sur [Mon numéro] Moins de 1000. Veillez à utiliser l’opérateur Numérique pour les deux.

   ![Modèles de routage Image 3](../12-exercises/assets/routing-patterns-walkthrough-3.png)

   ![Modèles de routage Image 4](../12-exercises/assets/routing-patterns-walkthrough-4.png)

1. Cliquez une fois sur Exécuter et regardez le lot transmettre le chemin &quot;Moins de 100&quot;.
1. Définissez ensuite le champ Définir la variable sur 950 et Exécutez à nouveau. Regardez-le courir le long du deuxième chemin.
1. Cliquez sur le routeur et ajoutez un autre chemin. Ajoutez le module d’outil de fonction Incrémenter . Pour le filtre, cliquez sur la case à cocher &quot;L’itinéraire de secours&quot;. Notez comment la flèche pointant vers ce chemin se transforme en accent circonflexe, indiquant qu’il s’agit de l’itinéraire de secours.

   ![Modèles de routage Image 5](../12-exercises/assets/routing-patterns-walkthrough-5.png)

1. Définissez le numéro de variable sur 9500 et Exécutez une fois. Comme le nombre n’est pas inférieur à 100 ou moins de 1 000, le lot emprunte l’itinéraire de secours.

Si vous ajoutez un autre chemin avec un module d’outil de fonction d’incrémentation, mais ne définissez aucun filtre, que se passera-t-il lorsque vous cliquerez de nouveau sur Exécuter ? Un lot sera-t-il un jour sur l’itinéraire de secours avec le quatrième itinéraire ajouté ?

+ Non, car sans filtre défini, chaque lot va toujours suivre ce chemin au lieu de l’itinéraire de secours.
