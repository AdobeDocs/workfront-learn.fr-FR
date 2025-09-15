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
source-git-commit: dfcca5f02a6d9f7ee44a1e894106ae48259eea91
workflow-type: tm+mt
source-wordcount: '238'
ht-degree: 90%

---

# Présentation des agrégations avancées

Appelez un service web pour obtenir des informations sur plusieurs pays et identifiez la population totale de tous les pays, regroupés par sous-région.

![Image du scénario Fusion](assets/iteration-and-aggregation-3.png)

## Présentation des agrégations avancées

Workfront recommande de regarder la vidéo de présentation de l’exercice avant d’essayer de recréer l’exercice dans votre propre environnement.

>[!VIDEO](https://video.tv.adobe.com/v/335281/?quality=12&learn=on&enablevpops)

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

Créez un nouveau scénario pour additionner toutes les heures enregistrées sur les tâches des projets du porfolio marketing. Ensuite, envoyez un e-mail indiquant « L’équipe de projet de votre {Project Name} a enregistré {summed hours} du nombre total d’heures prévues {planned hours}, ce qui vous place au {percentage} du plan ».

**Défi :** voyez si vous pouvez faire la même chose mais pour les heures enregistrées cette année seulement.

## Vous voulez en savoir plus ? Nous recommandons ce qui suit :

[Documentation sur Workfront Fusion](https://experienceleague.adobe.com/fr/docs/workfront-fusion/using/get-started-with-fusion/understand-workfront-fusion/workfront-fusion-overview)
