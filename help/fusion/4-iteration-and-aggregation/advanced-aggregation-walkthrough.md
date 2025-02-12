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
source-git-commit: d17df7162ccaab6b62db34209f50131927c0a532
workflow-type: tm+mt
source-wordcount: '245'
ht-degree: 100%

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

Créez un nouveau scénario pour additionner toutes les heures enregistrées sur les tâches des projets du porfolio marketing. Envoyez ensuite un e-mail disant : « Votre équipe de projet {Project Name} a enregistré {summed hours} du total des {planned hours} heures prévues, ce qui vous place à {percentage} du plan ».

**Défi :** voyez si vous pouvez faire la même chose mais pour les heures enregistrées cette année seulement.

## Vous voulez en savoir plus ? Nous recommandons ce qui suit :

[Documentation sur Workfront Fusion](https://experienceleague.adobe.com/docs/workfront/using/adobe-workfront-fusion/workfront-fusion-2.html?lang=fr)
