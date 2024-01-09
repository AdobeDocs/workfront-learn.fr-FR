---
title: Créer une vue de base
description: Découvrez ce qu’est une vue, comment créer une vue et comment partager une vue avec d’autres utilisateurs dans Workfront.
activity: use
feature: Reports and Dashboards
thumbnail: 335148.jpeg
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
last-substantial-update: 2023-06-20T00:00:00Z
jira: KT-8854
exl-id: ba3c0e10-dcf1-4a7b-bf11-ccfed9040e6d
doc-type: video
source-git-commit: 6a155c50d31e789381c1151e9ee9c091e62c909e
workflow-type: tm+mt
source-wordcount: '827'
ht-degree: 1%

---

# Créer une vue de base

Dans cette vidéo, vous apprendrez :

* Présentation d’une vue dans Workfront
* Création et modification d’une vue
* Comment partager une vue avec d’autres utilisateurs de Workfront

>[!VIDEO](https://video.tv.adobe.com/v/335148/?quality=12&learn=on)

## Activité 1 : Création d’une vue d’état de tâche

En tant que chef de projet, chef d’équipe ou responsable des ressources, vous souhaitez suivre l’avancement des tâches. Avec cette vue, vous obtenez plusieurs indicateurs d’état d’une tâche tous sur une ligne de la liste ou du rapport.

Créez une vue de tâche nommée &quot;Vue d’état de la tâche&quot; avec les colonnes suivantes :

* [!UICONTROL Task Name]
* [!UICONTROL Affectations]
* [!UICONTROL Durée]
* [!UICONTROL Pourcentage terminé]
* [!UICONTROL État]
* [!UICONTROL État de progression]
* [!UICONTROL Icônes d’état]

## Réponse de l’activité 1

![Image de l’écran pour créer une vue d’état de tâche](assets/view-exercise.png)

1. Dans un rapport de liste de tâches, accédez au **[!UICONTROL Affichage]** menu déroulant et sélectionnez **[!UICONTROL Nouvelle vue]**.
1. Nommez votre vue &quot;Affichage de l’état de la tâche&quot;.
1. Supprimez ces colonnes : [!UICONTROL Heures de planification], [!UICONTROL Prédécesseurs], [!UICONTROL Démarrer le], et [!UICONTROL Échéance activée].
1. Cliquez sur **[!UICONTROL Ajouter une colonne]**.
1. Dans le [!UICONTROL Afficher dans cette colonne] , saisissez &quot;status&quot;, puis sélectionnez &quot;Status&quot; sous la propriété [!UICONTROL Tâche] source du champ.
1. Cliquez sur **[!UICONTROL Ajouter une colonne]** encore une fois.
1. Dans le [!UICONTROL Afficher dans cette colonne] , saisissez &quot;status&quot;, puis sélectionnez &quot;Etat d’avancement&quot; sous [!UICONTROL Tâche] source du champ.
1. Cliquez sur **[!UICONTROL Ajouter une colonne]** encore une fois.
1. Dans le [!UICONTROL Afficher dans cette colonne] , saisissez &quot;status&quot;, puis sélectionnez &quot;Status Icons&quot; sous la source du champ Tâche .
1. Cliquer sur **[!UICONTROL Enregistrer]**.

Passez la souris sur chacune des icônes du [!UICONTROL Icônes d’état] pour voir ce qu’ils représentent. Si elles sont grisées, cela signifie que la tâche n&#39;a pas de notes, de documents, de processus de validation, etc. Si une icône s’affiche en couleur, au moins un de ces éléments est associé à la tâche. Vous pouvez cliquer sur les icônes de note ou de document pour accéder à cet élément.

## Activité 2 : création d’une vue de jalon

Si vous utilisez des jalons, cette vue est la méthode la plus simple pour afficher les jalons par nom et les ajouter ou les modifier à l’aide de la modification en ligne.

Créez une vue de tâche nommée &quot;Vue Milestone&quot; avec les colonnes suivantes :

* [!UICONTROL Task Name]
* [!UICONTROL Affectations]
* [!UICONTROL Durée]
* [!UICONTROL Heures de planification]
* [!UICONTROL Milestone : Nom]
* [!UICONTROL Démarrer le]
* [!UICONTROL Échéance activée]
* [!UICONTROL Pourcentage terminé]


## Réponse de l’activité 2

![Image de l’écran pour créer une vue de jalon](assets/view-milestone-exercise-1.png)

1. Dans la liste des tâches d’un projet, accédez au **[!UICONTROL Affichage]** menu déroulant et sélectionnez **[!UICONTROL Nouvelle vue]**.
1. Nommez votre vue &quot;Vue Milestone&quot;.
1. Cliquez sur le bouton [!UICONTROL Prédécesseurs] pour la sélectionner.
1. Dans le [!UICONTROL Afficher dans cette colonne] , cliquez sur l’icône X dans le champ [!UICONTROL Tâche > Prédécesseurs] champ, puis saisissez &quot;[!UICONTROL nom du jalon]&quot; et cliquez sur &quot;[!UICONTROL Nom]&quot; dans la liste.
1. Cliquer sur **[!UICONTROL Enregistrer]**.

![Image d’une liste de tâches utilisant une vue de jalon](assets/view-milestone-exercise-2.png)

## Activité 3 : créez un affichage des types de durée et des contraintes de tâche.

Cette vue vous permet d’examiner et de modifier tous les types de durée et les contraintes de tâche dans votre projet.

Créez une vue de tâche nommée &quot;Vue Types de durée et contraintes de tâche&quot; avec les colonnes suivantes :

* [!UICONTROL Task Name]
* [!UICONTROL Affectations]
* [!UICONTROL Durée]
* [!UICONTROL Durée planifiée]
* [!UICONTROL Heures de planification]
* [!UICONTROL Prédécesseurs]
* [!UICONTROL Démarrer le]
* [!UICONTROL Échéance activée]
* [!UICONTROL Type de durée]
* [!UICONTROL Contrainte de tâche]
* [!UICONTROL Date de contrainte]

Modifiez la variable [!UICONTROL Format du champ] sur le [!UICONTROL Démarrer le] et [!UICONTROL Échéance activée] pour afficher la date et l’heure.

## Réponse de l’activité 3

![Une image de l’écran montrant la vue des types de durée et des contraintes de tâche](assets/view-activity-3.png)

1. Dans la liste des tâches d’un projet, accédez au **[!UICONTROL Affichage]** menu déroulant et sélectionnez **[!UICONTROL Nouvelle vue]**.
1. Nommez votre vue &quot;Types de durée et contraintes de tâche&quot;.
1. Supprimez le [!UICONTROL % terminé] colonne .
1. Cliquez sur **[!UICONTROL Ajouter une colonne]**.
1. Dans le [!UICONTROL Afficher dans cette colonne] champ, type [!UICONTROL &quot;duration&quot;] puis sélectionnez [!UICONTROL &quot;Durée planifiée&quot;] sous le [!UICONTROL Tâche] source du champ.
1. Déplacer cette colonne entre les [!UICONTROL Durée] et la variable [!UICONTROL Heures de planification] colonnes.
1. Cliquez sur **[!UICONTROL Ajouter une colonne]** encore une fois.
1. Dans le [!UICONTROL Afficher dans cette colonne] champ, type [!UICONTROL &quot;type de durée&quot;] puis sélectionnez [!UICONTROL &quot;Type de durée&quot;] sous le [!UICONTROL Tâche] source du champ.
1. Cliquez sur **[!UICONTROL Ajouter une colonne]** encore une fois.
1. Dans le [!UICONTROL Afficher dans cette colonne] champ, type [!UICONTROL &quot;contrainte&quot;] puis sélectionnez [!UICONTROL &quot;Contrainte de tâche&quot;] sous la source du champ Tâche .
1. Cliquez sur **[!UICONTROL Ajouter une colonne]** encore une fois.
1. Dans le [!UICONTROL Afficher dans cette colonne] champ, type [!UICONTROL &quot;contrainte&quot;] puis sélectionnez [!UICONTROL &quot;Date de contrainte&quot;] sous la source du champ Tâche .
1. Sélectionnez la variable [!UICONTROL Démarrer le] , puis cliquez sur [!UICONTROL Options avancées].
1. Sous , [!UICONTROL Format du champ] menu déroulant [!UICONTROL &quot;10/17/60 3 heures&quot;].
1. Sélectionnez la variable [!UICONTROL Échéance activée] , puis cliquez sur [!UICONTROL Options avancées].
1. Sous , [!UICONTROL Format du champ] menu déroulant [!UICONTROL &quot;10/17/60 3 heures&quot;].
1. Cliquer sur **[!UICONTROL Enregistrer]**.

## Activité 4 : création d’un modèle de projet en mode d’état actif

Quiconque gère des modèles de projet apprécie l’état actif (Vrai ou Faux) de chaque modèle dans une liste. Mieux encore : le champ est modifiable en ligne.

Créez une vue de modèle de projet nommée &quot;État actif du modèle de projet&quot; avec les colonnes suivantes :

* [!UICONTROL Nom]
* [!UICONTROL Propriétaire]
* [!UICONTROL Durée]
* [!UICONTROL Heures planifiées]
* [!UICONTROL Coût planifié]
* [!UICONTROL Indicateurs]
* [!UICONTROL Nom du groupe]
* [!UICONTROL Est actif]


## Réponse de l’activité 4

![Image de l’écran d’affichage de l’état actif d’un modèle de projet](assets/view-activity-4.png)

1. Dans la liste d’un modèle de projet, accédez au **[!UICONTROL Affichage]** menu déroulant et sélectionnez **[!UICONTROL Nouvelle vue]**.
1. Nommez votre vue &quot;Standard+état actif&quot;.
1. Cliquez sur **[!UICONTROL Ajouter une colonne]**.
1. Dans le [!UICONTROL Afficher dans cette colonne] , saisissez &quot;is&quot;, puis sélectionnez &quot;Is Active&quot; sous le champ [!UICONTROL Modèle] source du champ.
1. Cliquez sur **[!UICONTROL Enregistrer la vue]**.
