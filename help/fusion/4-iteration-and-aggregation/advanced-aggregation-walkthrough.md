---
title: Présentation des agrégations avancées
description: Découvrez comment appeler un service web pour obtenir des informations sur plusieurs pays et identifier la population, regroupés par sous-région, le tout dans  [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-9040
exl-id: c79250d0-7341-4a25-83dc-de99ce5c6dc4
recommendations: noDisplay,catalog
doc-type: video
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
autotag-review: '2026-05-06T16:33:27.197Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 258
ht-degree: 100%

---

# Présentation des agrégations avancées

Appelez un service web pour obtenir des informations sur plusieurs pays et identifiez la population totale de tous les pays, regroupés par sous-région.

![Image du scénario Fusion](assets/iteration-and-aggregation-3.png)

## Présentation des agrégations avancées

Workfront recommande de regarder la vidéo de présentation de l’exercice avant d’essayer de recréer l’exercice dans votre propre environnement.

>[!VIDEO](https://video.tv.adobe.com/v/3417303/?captions=fre_fr&quality=12&learn=on&enablevpops=1)

## URL d’exercice

* `https://restcountries.com/v2/lang/es`
* `https://restcountries.com/v2/name/{country name}`



## Renforcement du principe d’agrégation

Chaque fois qu’un module génère plusieurs bundles, chaque module qui suit exécute chaque bundle.

Pour éviter cela, ajoutez un agrégateur après un module qui produit potentiellement plusieurs bundles.

Vous verrez une ombre entourer les segments de votre scénario, de l’**itérateur de début** à l’**agrégateur de fin**. Cela permet de repérer facilement ces segments dans votre scénario Workfront Fusion.

## À vous

>[!NOTE]
>
>Les exercices pratiques et les défis sont facultatifs et ne sont pas nécessaires pour terminer la formation Fusion.

Cet exercice repose sur ce que vous avez appris dans la présentation, mais la solution n’est pas fournie.

Créez un nouveau scénario pour additionner toutes les heures enregistrées sur les tâches des projets du porfolio marketing. Envoyez ensuite un e-mail indiquant : « Votre équipe de projet {Project Name} a enregistré {summed hours} heures sur les {planned hours} heures prévues au total, ce qui vous place à {percentage} du plan ».

**Défi :** voyez si vous pouvez faire la même chose mais pour les heures enregistrées cette année seulement.

## Vous voulez en savoir plus ? Nous recommandons ce qui suit :

[Documentation de Workfront Fusion](https://experienceleague.adobe.com/fr/docs/workfront-fusion/using/get-started-with-fusion/understand-workfront-fusion/workfront-fusion-overview)
