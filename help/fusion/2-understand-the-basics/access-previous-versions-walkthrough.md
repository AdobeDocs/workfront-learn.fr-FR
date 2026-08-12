---
title: Accéder à la présentation des versions précédentes
description: Découvrez comment restaurer les versions précédentes après avoir apporté des modifications à votre scénario et les avoir enregistrées dans  [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-9009
exl-id: dd2cc2a2-e5af-41cc-bc0d-6be1efd996d9
last-substantial-update: '2026-08-12T00:00:00.000Z'
recommendations: noDisplay,catalog
doc-type: video
product_v2: id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2: id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
subfeature_v2: id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
autotag-review: '2026-05-06T16:39:17.503Z'
source-git-commit: 4b419797e3014599bffd64f576d8eeb196c8c153
workflow-type: tm+mt
source-wordcount: 280
ht-degree: 78%

---

# Accéder à la présentation des versions précédentes

Dans cette vidéo, vous allez :

* Découvrez comment restaurer des versions précédentes après avoir modifié votre scénario et enregistré plusieurs fois.

## Accéder à la présentation des versions précédentes

Workfront recommande de regarder la vidéo de présentation de l’exercice avant d’essayer de recréer l’exercice dans votre propre environnement.

>[!VIDEO](https://video.tv.adobe.com/v/335268/?quality=12&learn=on&enablevpops=1)

>[!NOTE]
>
>Après avoir enregistré votre scénario, Workfront Fusion conserve la version précédente du scénario pendant 60 jours. La période de conservation d’une version commence lorsque cette version est remplacée par une version plus récente, et non lors de sa création initiale.
>Pour conserver l’historique des versions du scénario au-delà de 60 jours à des fins d’audit, enregistrez et archivez un plan directeur du scénario à un emplacement convenu.


## Compléter votre terminologie

![Une image d’un enregistrement de veille et d’un module de webhook personnalisé](assets/understand-the-basics-3.png)

### Modules déclencheurs

Les modules de déclencheur ne peuvent être utilisés qu’en tant que premier module et peuvent renvoyer zéro, un ou plusieurs bundles. Ils seront traités individuellement dans les modules suivants, à moins qu’ils ne soient agrégés.

**Déclencheur d’attente active (déclencheur avec horloge)** : fonction spéciale permettant de garder la trace du dernier enregistrement traité.

**Déclencheur instantané (déclencheur avec éclair)** : déclenchement immédiat sur la base d’un webhook.

![Une image d’un enregistrement de création et d’un module de recherche](assets/understand-the-basics-4.png)

### Actions et modules de recherche

**Action** : utilisée pour effectuer des opérations CRUD (création, lecture, mise à jour et suppression).

**Recherches** : permet de rechercher zéro, un ou plusieurs enregistrements et de les renvoyer sous forme de bundles, qui seront traités individuellement dans les modules suivants, à moins qu’ils ne soient agrégés.

## Vous voulez en savoir plus ? Nous recommandons ce qui suit :

[Documentation de Workfront Fusion](https://experienceleague.adobe.com/fr/docs/workfront-fusion/using/get-started-with-fusion/understand-workfront-fusion/workfront-fusion-overview)
