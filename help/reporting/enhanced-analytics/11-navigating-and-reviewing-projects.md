---
title: Présentation de la navigation et de la révision des projets dans [!UICONTROL Analytics amélioré]
description: Découvrez comment lire le diagramme du plan de vol dans Workfront.
activity: use
feature: Reports and Dashboards
thumbnail: 335047.png
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
kt: 8729
exl-id: 1409a1af-3bdb-40f7-af01-f9de2357b602
doc-type: video
source-git-commit: 65bd26fefb280d12ec44a4923f6d96ac8d88d6fb
workflow-type: tm+mt
source-wordcount: '474'
ht-degree: 0%

---

# Présentation de la navigation et de la révision des projets dans [!UICONTROL Analytics amélioré]

Dans cette vidéo, vous apprendrez :

* Comment lire le plan de vol

>[!VIDEO](https://video.tv.adobe.com/v/335047/?quality=12&learn=on)

## Graphique du plan de vol

![Une image d’un graphique du plan de vol avec des nombres correspondant aux balles ci-dessous](assets/section-2-1.png)

Sur le graphique, vous voyez :

1. Les noms des projets se trouvent à gauche.
1. Les dates sont affichées en bas.
1. La ligne bleue verticale indique la date spécifique à laquelle la souris survole.
1. Les lignes bleues horizontales indiquent les dates de début et de fin prévues du projet.
1. Les lignes vertes indiquent que le projet est Sur Target.
1. Des lignes orange indiquent que le projet est En danger.
1. Les lignes rouges indiquent que le projet est en danger.

L’affichage de ces informations sur vos projets vous aide à déterminer les éléments suivants :

* Les événements étendent un projet au-delà de la date d’achèvement prévue.
* Lorsqu’un projet commence à rencontrer des problèmes.
* Nombre de projets ouverts au cours de la même période.
* Combien de projets sont principaux ?
* Les projets qui nécessitent une attention ou un soutien supplémentaire.

## La condition est basée sur l’état de progression

La condition du projet est une représentation visuelle de l’avancement du projet. Workfront détermine la condition en fonction de l’état d’avancement des tâches dans le projet.

![Image des états de progression possibles](assets/section-2-2.png)

La condition d’un projet peut être définie :

* **Manuellement**, par les utilisateurs ayant accès à la gestion du projet, lorsque le type de condition du projet est défini sur manuel. Vous pouvez ainsi définir la condition du projet indépendamment du chemin critique.
* **Automatiquement**, par Workfront, lorsque le type de condition du projet est défini sur État de progression.

Workfront recommande de définir le type de condition sur État de progression afin que vous ayez une indication claire de l’état d’avancement réel du projet, en fonction de l’état d’avancement de vos tâches.

![Image des états de progression possibles](assets/section-2-3.png)

Lorsqu’elle est définie sur État de progression, la condition du projet peut être :

* **Sur Target**: lorsque l’état d’avancement de la dernière tâche sur le chemin critique est Activé, la condition du projet est Activé Target. Le projet est en bonne voie pour se terminer selon le calendrier.
* **À risque**—Lorsque l’état d’avancement de la dernière tâche sur le chemin critique est Derrière ou En danger, la condition du projet est En danger. Le projet est en bonne voie pour se terminer tard mais n&#39;est pas encore en retard.
* **En difficulté**: lorsque l’état d’avancement de la dernière tâche sur le chemin critique est En retard, la condition du projet est En problème. La date butoir est passée et le projet est maintenant en retard.

>[!NOTE]
>
>Les conditions peuvent être personnalisées pour votre environnement. Vous pouvez donc trouver plus de trois options ou les noms peuvent être différents de ceux ci-dessus. Pour plus d’informations sur la personnalisation des conditions, voir l’article [Création ou modification d’une condition personnalisée](https://experienceleague.adobe.com/docs/workfront/using/administration-and-setup/customize/custom-conditions/create-edit-custom-conditions.html?lang=en).
