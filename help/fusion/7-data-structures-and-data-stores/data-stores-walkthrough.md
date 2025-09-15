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
source-git-commit: dfcca5f02a6d9f7ee44a1e894106ae48259eea91
workflow-type: tm+mt
source-wordcount: '393'
ht-degree: 99%

---

# Présentation des magasins de données

Dans cet exercice, nous utilisons un magasin de données pour synchroniser les noms d’entreprise entre une liste d’entreprises et Workfront.

Il s’agit d’une partie d’une synchronisation unidirectionnelle des entreprises dans Workfront et dans un autre système. Pour l’instant, la synchronisation n’a lieu qu’entre un fichier CSV et Workfront. Mais cela maintient également une table dans un magasin de données qui garde la trace de l’ID Workfront (WFID) et de l’ID de l’entreprise dans le fichier CSV (CID) pour chaque entreprise. Cela nous permet d’en faire une synchronisation bidirectionnelle à un moment ou à un autre.

![Une image d’un scénario Fusion](assets/data-structures-and-data-stores-2.png)

## Présentation des magasins de données

Workfront recommande de regarder la vidéo de présentation de l’exercice avant d’essayer de recréer l’exercice dans votre propre environnement.

>[!VIDEO](https://video.tv.adobe.com/v/335296/?quality=12&learn=on&enablevpops)



## Note finale

Maintenant que vous en savez plus sur les structures de données et les magasins de données, vous vous demandez peut-être : « quand devrais-je les utiliser ? »

Les structures de données servent le plus souvent à sérialiser ou analyser des formats de données tels que JSON, XML, CSV, etc. Les structures de données vous permettent de contrôler la structure de vos données et même de les valider. La raison la plus courante pour laquelle vous utilisez une structure de données est de créer des données valides à envoyer à une API qui attend du JSON ou du XML. Dans ce cas, vous souhaiterez utiliser l’application JSON ou XML avec votre structure de données pour vous assurer que les données sont au bon format.

Les magasins de données ne doivent être utilisés que pour stocker des données persistantes auxquelles plusieurs exécutions de scénarios doivent pouvoir accéder. Par exemple, vous pouvez stocker des métadonnées sur le dernier enregistrement traité pour des cas d’utilisation avancés nécessitant un contrôle précis du traitement.

Les magasins de données ne sont pas conçus pour servir d’entrepôt de données ou de système de journalisation. Les magasins de données ne sont pas accessibles en dehors de Workfront Fusion. De plus, la plupart des interactions avec les magasins de données se font à travers un scénario Workfront Fusion. Par conséquent, il est impossible de connecter un magasin de données à un outil d’analyse ou de reporting, comme on pourrait s’y attendre dans les cas d’utilisation d’entrepôts de données et de journalisation. Le rôle de Workfront Fusion dans de tels cas d’utilisation serait de renseigner un système approprié pour l’organisation et le stockage des données (SQL, MariaDB, par exemple).

## Vous voulez en savoir plus ? Nous recommandons ce qui suit :

[Documentation sur Workfront Fusion](https://experienceleague.adobe.com/fr/docs/workfront-fusion/using/get-started-with-fusion/understand-workfront-fusion/workfront-fusion-overview)
