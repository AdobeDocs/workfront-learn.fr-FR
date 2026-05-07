---
title: Présentation des magasins de données
description: Découvrez comment utiliser un magasin de données pour synchroniser les noms d’entreprise entre une liste d’entreprises et Workfront à l’aide de  [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-9055
exl-id: e96fd109-2463-4702-b1bf-b42a6dcd7fc4
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
autotag-review: '2026-05-06T16:18:10.872Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 411
ht-degree: 100%

---

# Présentation des magasins de données

Dans cet exercice, nous utilisons un magasin de données pour synchroniser les noms d’entreprise entre une liste d’entreprises et Workfront.

Il s’agit d’une partie d’une synchronisation unidirectionnelle des entreprises dans Workfront et dans un autre système. Pour l’instant, la synchronisation n’a lieu qu’entre un fichier CSV et Workfront. Mais cela maintient également une table dans un magasin de données qui garde la trace de l’ID Workfront (WFID) et de l’ID de l’entreprise dans le fichier CSV (CID) pour chaque entreprise. Cela nous permet d’en faire une synchronisation bidirectionnelle à un moment ou à un autre.

![Une image d’un scénario Fusion](assets/data-structures-and-data-stores-2.png)

## Présentation des magasins de données

Workfront recommande de regarder la vidéo de présentation de l’exercice avant d’essayer de recréer l’exercice dans votre propre environnement.

>[!VIDEO](https://video.tv.adobe.com/v/3417969/?captions=fre_fr&quality=12&learn=on&enablevpops=1)



## Note finale

Maintenant que vous en savez plus sur les structures de données et les magasins de données, vous vous demandez peut-être : « quand devrais-je les utiliser ? »

Les structures de données servent le plus souvent à sérialiser ou analyser des formats de données tels que JSON, XML, CSV, etc. Les structures de données vous permettent de contrôler la structure de vos données et même de les valider. La raison la plus courante pour laquelle vous utilisez une structure de données est de créer des données valides à envoyer à une API qui attend du JSON ou du XML. Dans ce cas, vous souhaiterez utiliser l’application JSON ou XML avec votre structure de données pour vous assurer que les données sont au bon format.

Les magasins de données ne doivent être utilisés que pour stocker des données persistantes auxquelles plusieurs exécutions de scénarios doivent pouvoir accéder. Par exemple, vous pouvez stocker des métadonnées sur le dernier enregistrement traité pour des cas d’utilisation avancés nécessitant un contrôle précis du traitement.

Les magasins de données ne sont pas conçus pour servir d’entrepôt de données ou de système de journalisation. Les magasins de données ne sont pas accessibles en dehors de Workfront Fusion. De plus, la plupart des interactions avec les magasins de données se font à travers un scénario Workfront Fusion. Par conséquent, il est impossible de connecter un magasin de données à un outil d’analyse ou de reporting, comme on pourrait s’y attendre dans les cas d’utilisation d’entrepôts de données et de journalisation. Le rôle de Workfront Fusion dans de tels cas d’utilisation serait de renseigner un système approprié pour l’organisation et le stockage des données (SQL, MariaDB, par exemple).

## Vous voulez en savoir plus ? Nous recommandons ce qui suit :

[Documentation de Workfront Fusion](https://experienceleague.adobe.com/fr/docs/workfront-fusion/using/get-started-with-fusion/understand-workfront-fusion/workfront-fusion-overview)
