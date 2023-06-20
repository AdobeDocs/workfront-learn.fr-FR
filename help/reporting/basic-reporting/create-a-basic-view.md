---
title: Création d’une vue de base
description: Découvrez ce qu’est une vue, comment créer une vue et comment partager une vue avec d’autres utilisateurs dans Workfront.
activity: use
feature: Reports and Dashboards
thumbnail: 335148.jpeg
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
last-substantial-update: 2023-06-20T00:00:00Z
kt: 8854
exl-id: ba3c0e10-dcf1-4a7b-bf11-ccfed9040e6d
doc-type: video
source-git-commit: f7e6fa6a728699c307fbba926d1bdaa697ba4894
workflow-type: tm+mt
source-wordcount: '434'
ht-degree: 6%

---

# Création d’une vue de base

Dans cette vidéo, vous apprendrez :

* Présentation d’une vue dans Workfront
* Création et modification d’une vue
* Comment partager une vue avec d’autres utilisateurs de Workfront

>[!VIDEO](https://video.tv.adobe.com/v/335148/?quality=12&learn=on)

## Activité 1 : Création d’une vue d’état de tâche

En tant que chef de projet, chef d’équipe ou responsable des ressources, vous souhaitez suivre l’avancement des tâches. Avec cette vue, vous obtenez plusieurs indicateurs d’état d’une tâche tous sur une ligne de la liste ou du rapport.

Créez une vue de tâche nommée &quot;Vue d’état de la tâche&quot; avec les colonnes suivantes :

* [!UICONTROL Nom de la tâche]
* [!UICONTROL Affectations]
* [!UICONTROL Durée]
* [!UICONTROL Pourcentage d&#39;achèvement]
* [!UICONTROL Statut]
* [!UICONTROL Statut de progression]
* [!UICONTROL Icônes de statut]

## Réponse d’activité 1

![Image de l’écran pour créer une vue d’état de tâche](assets/view-exercise.png)

1. Dans un rapport de liste de tâches, accédez au **[!UICONTROL Affichage]** menu déroulant, puis sélectionnez **[!UICONTROL Nouvelle vue]**.
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

## Activité 2 : Création d’une vue de jalon

Si vous utilisez des jalons, cette vue est le moyen le plus simple d’afficher les jalons par nom et de les ajouter ou de les modifier à l’aide de la modification en ligne.

Créez une vue de tâche nommée &quot;Vue Milestone&quot; avec les colonnes suivantes :

* [!UICONTROL Nom de la tâche]
* [!UICONTROL Affectations]
* [!UICONTROL Durée]
* [!UICONTROL Hrs Prév]
* [!UICONTROL Milestone : Nom]
* [!UICONTROL Démarré le]
* [!UICONTROL Dû le]
* [!UICONTROL Pourcentage d&#39;achèvement]


## Réponse de l’activité 2

![Image de l’écran pour créer une vue de jalon](assets/view-milestone-exercise-1.png)

1. Dans la liste des tâches d’un projet, accédez au **[!UICONTROL Affichage]** menu déroulant, puis sélectionnez **[!UICONTROL Nouvelle vue]**.
1. Nommez votre vue &quot;Vue Milestone&quot;.
1. Cliquez sur le bouton [!UICONTROL Prédécesseurs] pour la sélectionner.
1. Dans le [!UICONTROL Afficher dans cette colonne] , cliquez sur l’icône X dans le champ [!UICONTROL Tâche > Prédécesseurs] champ, puis saisissez &quot;[!UICONTROL nom du jalon]&quot; et cliquez sur &quot;[!UICONTROL Nom]&quot; dans la liste.
1. Cliquer sur **[!UICONTROL Enregistrer]**.

![Image d’une liste de tâches utilisant une vue de jalon](assets/view-milestone-exercise-2.png)
