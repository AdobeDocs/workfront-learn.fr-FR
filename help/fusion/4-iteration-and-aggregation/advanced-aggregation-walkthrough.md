---
title: Présentation de l’agrégation avancée
description: Découvrez comment appeler un service Web pour renvoyer des détails sur plusieurs pays et identifier la population, regroupée par sous-région, le tout dans [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
kt: Jira ticket
exl-id: c79250d0-7341-4a25-83dc-de99ce5c6dc4
source-git-commit: 58a545120b29a5f492344b89b77235e548e94241
workflow-type: tm+mt
source-wordcount: '277'
ht-degree: 0%

---

# Présentation de l’agrégation avancée

## Vue d’ensemble

Appelez un service Web pour renvoyer les détails sur plusieurs pays et identifier la population totale de tous les pays, regroupée par sous-région.

![Une image du scénario Fusion](assets/iteration-and-aggregation-3.png)

## Présentation de l’agrégation avancée

Workfront recommande de regarder la vidéo de présentation de l’exercice avant d’essayer de recréer l’exercice dans votre propre environnement.

>[!VIDEO](https://video.tv.adobe.com/v/335281/?quality=12)

## URL d’exercice

* `https://restcountries.com/v2/lang/es`
* `https://restcountries.com/v2/name/{country name}`

>[!TIP]
>
>Pour obtenir des instructions détaillées sur la manière d’effectuer la présentation, accédez à la section [Présentation de l’agrégation avancée](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/fusion/exercises/advanced-aggregation.html?lang=en) exercice.

## Renforcement du principe d&#39;agrégation

Chaque fois qu’un module génère plusieurs lots, chaque module qui suit exécute chaque lot.

Pour éviter cela, ajoutez un agrégateur après un module qui produit potentiellement plusieurs lots.

Vous verrez une ombre entourant un segment dans votre scénario à partir d’un **start-iterator** au **ending-aggator**. Cela permet de repérer facilement ces segments dans votre scénario Workfront Fusion.

## Votre tour

>[!NOTE]
>
>Les exercices pratiques sont facultatifs et ne sont pas nécessaires pour terminer la formation sur la fusion.

Cet exercice repose sur ce que vous avez appris dans la présentation, mais la solution n’est pas fournie.

Créez un nouveau scénario pour additionner toutes les heures consignées dans les tâches des projets du portefeuille marketing. Ensuite, envoyez un e-mail indiquant que &quot;votre équipe de projet {Project Name} a enregistré {summed hours} du total {scheduled hours} heures, ce qui vous place à {pourcentage} du plan.&quot;

**Défi :** Voyez si vous pouvez faire la même chose, sauf pour les heures enregistrées cette année uniquement.

## Vous souhaitez en savoir plus ? Nous vous recommandons ce qui suit :

[Documentation de Workfront Fusion](https://experienceleague.adobe.com/docs/workfront/using/adobe-workfront-fusion/workfront-fusion-2.html?lang=en)
