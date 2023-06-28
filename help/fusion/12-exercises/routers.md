---
title: Routeurs
description: Comprenez l’importance des routeurs et comment ils peuvent être utilisés pour traiter de manière conditionnelle différents modules.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11043
thumbnail: KT11043.png
exl-id: f2a60273-c19b-4423-b354-8cff0dd7bd6b
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '732'
ht-degree: 0%

---

# Routeurs

Comprenez l’importance des routeurs et comment ils peuvent être utilisés pour traiter de manière conditionnelle différents modules.

## Présentation de l’exercice

Utilisez un routeur pour transmettre les lots Pokemon et superhéros vers le chemin approprié, puis créez une tâche pour chaque caractère.

![Routeurs Image 1](../12-exercises/assets/routers-walkthrough-1.png)

## Étapes à suivre

1. Cloner le scénario Utilisation des connecteurs universels de l’exercice précédent. Nommez-le &quot;Création de chemins différents à l’aide de routeurs&quot;.

   **Créez un nouveau chemin pour les super-héros en clonant les modules et en ajoutant un routeur.**

   ![Routeurs Image 2](../12-exercises/assets/routers-walkthrough-2.png)

1. Cliquez avec le bouton droit sur le module Get Pokemon info et sélectionnez Clone. Une fois le clonage effectué, faites-le glisser et connectez-le à la ligne entre le nouveau module HTTP et le module CSV Parse.

   >[!NOTE]
   >
   > Remarquez comment il ajoute automatiquement un routeur avec deux chemins.

1. Nommez ce module &quot;Obtenir l’apparence de superhéros&quot;.
1. Cloner ce module, déplacer le clone vers la droite, et le nommer &quot;Obtenir des capacités de super-héros&quot;.
1. Cloner le module Outils et le déplacer à la fin du deuxième chemin.
1. Cliquez sur l’icône de baguette (bouton Alignement automatique ) dans la barre d’outils.

   **Votre scénario doit se présenter comme suit :**

   ![Image 3 des routeurs](../12-exercises/assets/routers-walkthrough-3.png)

   **Ensuite, vous allez modifier les valeurs mappées dans les nouveaux modules clonés.**

1. Accédez à <https://www.superheroapi.com/> et utilisez votre compte Facebook pour obtenir un jeton d’accès.

   >[!NOTE]
   >
   >Si vous rencontrez des problèmes pour accéder à votre propre jeton superhero, vous pouvez utiliser ce jeton partagé : 10110256647253588. Veuillez tenir compte du nombre de fois que vous appelez à l’API superhero pour que ce jeton partagé continue à fonctionner pour tout le monde.

1. Ouvrez les paramètres de l’apparence Get superhero et modifiez l’URL en `https://www.superheroapi.com/api/[access- token]/332/appearance`. Veillez à inclure votre jeton d’accès dans l’URL. Cliquez sur OK.
1. Ouvrez les paramètres des fonctionnalités Get superhero et remplacez l’URL par `https://www.superheroapi.com/api/[access- token]/332/powerstats`. Veillez à inclure votre jeton d’accès dans l’URL. Cliquez sur OK.
1. Cliquez avec le bouton droit de la souris sur chaque module superhero et sélectionnez Exécuter ce module uniquement. Cela génère la structure de données que vous devez afficher pour le mappage.
1. Après avoir exécuté les deux, remplacez le nombre &quot;332&quot; dans chaque champ d’URL par la colonne 4 mappée à partir du module Parse CSV.

   ![Image 4 des routeurs](../12-exercises/assets/routers-walkthrough-4.png)

   **Vous pouvez maintenant cliquer sur le module Définir plusieurs variables dans le chemin d’accès du superhéros et mettre à jour le nom, la taille, le poids et les capacités.**

1. Mettez à jour les champs Nom et Capacités du module Get superhero abilities—Module 8.

   ![Routeurs Image 5](../12-exercises/assets/routers-walkthrough-5.png)

1. Mettez à jour les champs Hauteur et Poids à partir du module Get superhero apparence (Module 6).

   ![Routeurs Image 6](../12-exercises/assets/routers-walkthrough-6.png)

   **Lorsque vous avez terminé, vos variables doivent ressembler à ceci. Notez que les numéros de module apparaissent dans les valeurs de champ.**

   ![Routeurs Image 7](../12-exercises/assets/routers-walkthrough-7.png)

1. Cliquez sur OK, puis enregistrez votre scénario.

   **Créez un autre chemin pour créer une tâche par caractère.**

1. Dans Workfront, créez un projet vide. Nommez-le &quot;Projet de manifeste d’expédition&quot; et copiez l’ID de projet à partir de l’URL.
1. Revenez à Workfront Fusion et cliquez au centre du routeur pour créer un autre chemin.

   ![Routeurs Image 8](../12-exercises/assets/routers-walkthrough-8.png)

1. Cliquez au centre du module vide qui s’affiche et ajoutez un module Créer un module d’enregistrement à partir de l’application Workfront.
1. Définissez le Type d’enregistrement sur Tâche et sélectionnez ID de projet dans la section Champs à mapper .
1. Collez l’ID de projet que vous avez copié à partir de Workfront dans le champ ID de projet .
1. Sélectionnez maintenant le champ Nom dans la section Champs à mapper .
1. Nommez la tâche &quot;[Caractère] de [Franchise],&quot; en utilisant le nom de caractère et le nom de la franchise du fichier CSV. La colonne 3 est le nom du caractère et la colonne 2 est le nom de la franchise.

   ![Routeurs Image 9](../12-exercises/assets/routers-walkthrough-9.png)

1. Cliquez sur OK, puis renommez ce module en &quot;Créer une tâche pour chaque caractère&quot;.

   **Ajoutez des filtres pour que le scénario puisse s’exécuter sans erreur. Vous souhaitez que seuls les caractères Pokemon suivent le chemin supérieur, seuls les caractères superhéros suivent le chemin du milieu et tous les caractères suivent le chemin du bas.**

1. Cliquez sur la ligne pointillée à gauche du module Get Pokemon info pour créer le premier filtre. Nommez-le &quot;Pokemon character&quot; (caractère pokemon).
1. Pour la condition, autorisez uniquement les enregistrements dont la franchise (Colonne 2) est égale à &quot;Pokemon&quot;. Sélectionnez l’opérateur de texte &quot;Egal à&quot;.
1. Cliquez sur la ligne pointillée à gauche du module Get superhero apparence pour créer le filtre suivant. Nommez-le &quot;Caractère Superhero&quot;.
1. Comme les super-héros peuvent provenir de diverses franchises, utilisez le champ Superhero ID (Colonne 4) pour déterminer si un personnage est un super-héros ou non.

   **Vos filtres doivent se présenter comme suit :**

   ![Image 11 des routeurs](../12-exercises/assets/routers-walkthrough-11.png)

   ![Image 10 des routeurs](../12-exercises/assets/routers-walkthrough-10.png)

1. Enregistrez le scénario et cliquez sur Exécuter une fois. Utilisez les inspecteurs d’exécution pour vérifier que toutes les opérations ont réussi et vérifiez les tâches qui ont été créées dans votre projet Workfront.

   ![Image 12 des routeurs](../12-exercises/assets/routers-walkthrough-12.png)
