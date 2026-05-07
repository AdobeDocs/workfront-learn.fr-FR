---
title: Comprendre la navigation et la révision des projets
description: Découvrez comment lire le graphique du plan de vol dans [!UICONTROL Analytique améliorée].
activity: use
feature: Reports and Dashboards
thumbnail: 335047.png
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
jira: KT-8729
recommendations: noDisplay,catalog
exl-id: 1409a1af-3bdb-40f7-af01-f9de2357b602
doc-type: video
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
subfeature_v2:
  - id: db1e0ccb-6619-410a-84d6-6b80ac783274
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
autotag-review: '2026-05-06T14:11:51.971Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 475
ht-degree: 100%

---

# Comprendre la navigation et la révision des projets

Dans cette vidéo, vous apprendrez :

* Comment lire le graphique du plan de vol

>[!VIDEO](https://video.tv.adobe.com/v/335047/?quality=12&learn=on&enablevpops=1)

## Graphique du plan de vol

![Image d’un graphique de plan de vol avec des nombres correspondant aux puces ci-dessous](assets/section-2-1.png)

Sur le graphique, vous voyez :

1. Les noms des projets à gauche.
1. Les dates dans la partie inférieure.
1. La ligne bleue verticale indique la date spécifique que votre souris survole.
1. Les lignes bleues horizontales indiquent les dates de début et de fin prévues du projet.
1. Les lignes vertes indiquent que le projet est Dans les temps.
1. Des lignes orange indiquent que le projet est À risque.
1. Les lignes rouges indiquent que le projet est En difficulté.

L’affichage de ces informations sur vos projets vous aide à déterminer les éléments suivants :

* Les événements qui prolongent un projet au-delà de la date d’achèvement prévue.
* Lorsqu’un projet commence à rencontrer des problèmes.
* Le nombre de projets ouverts au cours de la même période.
* Le nombre de projets actifs.
* Les projets qui nécessitent une attention ou un soutien supplémentaire.

## La condition est basée sur le statut de la progression

La condition du projet est une représentation visuelle de le la progression du projet. Workfront détermine la condition en fonction du statut de la progression des tâches dans le projet.

![Image des statuts de progression possibles](assets/section-2-2.png)

La condition d’un projet peut être définie :

* **Manuellement**, par les utilisateurs et utilisatrices ayant accès à la gestion du projet, lorsque le type de condition du projet est défini comme manuel. Vous pouvez ainsi définir la condition du projet indépendamment du chemin critique.
* **Automatiquement**, par Workfront, lorsque le type de condition du projet est défini sur Statut de la progression.

Workfront recommande de définir le type de condition sur Statut de la progression afin que vous ayez une indication claire de la progression réelle du projet en fonction de la progression de vos tâches.

![Image des statuts de progression possibles](assets/section-2-3.png)

Lorsqu’elle est définie sur Statut de la progression, la condition du projet peut être :

* **Dans les temps** : lorsque le statut de la progression de la dernière tâche sur le chemin critique est Dans les temps, la condition du projet est En bonne voie. Le projet est parti pour terminer dans les délais prévus.
* **À risque** : lorsque le statut de la progression de la dernière tâche du chemin critique est En retard ou À risque, la condition du projet est À risque. Le projet est parti pour terminer en retard mais n’est pas encore en retard.
* **En difficulté** : lorsque le statut de la progression de la dernière tâche du chemin critique est En retard, la condition du projet est En difficulté. La date butoir est passée et le projet est désormais en retard.

>[!NOTE]
>
>Les conditions peuvent être adaptées à votre environnement, il se peut donc que vous trouviez plus de trois options ou que les noms soient différents de ceux indiqués ci-dessus. Pour plus d’informations sur la personnalisation des conditions, voir l’article [Création ou modification d’une condition personnalisée](https://experienceleague.adobe.com/docs/workfront/using/administration-and-setup/customize/custom-conditions/create-edit-custom-conditions.html?lang=fr).
