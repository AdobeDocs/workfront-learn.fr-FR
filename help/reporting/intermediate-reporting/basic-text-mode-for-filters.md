---
title: Comprendre le mode texte de base pour les filtres
description: Apprenez ce qu’est le mode texte, ce qu’est le camel case, et quelques modes texte de base « plug and play » que vous pouvez utiliser dans vos filtres de rapport dans Workfront.
activity: use
feature: Text Mode Reporting
thumbnail: 336820.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
last-substantial-update: 2024-10-04T00:00:00Z
jira: KT-9086
exl-id: b3f16468-b720-468d-887a-b313fc32bd89
doc-type: video
source-git-commit: 7c2fb562c6f65eeeed7908d0c6f2f071ac176c33
workflow-type: tm+mt
source-wordcount: '426'
ht-degree: 95%

---

# Comprendre le mode texte de base pour les filtres

>[!PREREQUISITES]
>
>* [Comprendre les éléments de reporting](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/reporting-elements.html?lang=fr)
>* [Comprendre les composants de reporting](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/reporting-components.html?lang=fr)
>* [Créer un filtre de base](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/intermediate-reporting/basic-text-mode-for-filters.html?lang=fr)


>[!TIP]
>
>* Pour mieux comprendre le mode texte, nous vous recommandons de regarder le webinaire enregistré [Ask the Expert - Présentation de la création de rapports en mode texte](https://experienceleague.adobe.com/docs/workfront-events/events/reporting-and-dashboards/introduction-to-text-mode-reporting.html?lang=fr), d’une durée d’une heure.
>* Pour en savoir plus sur le mode texte, nous vous recommandons de regarder les tutoriels [Reporting avancé](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/advanced-reporting/welcome-to-advanced-reporting.html?lang=fr), qui durent cinq heures et demie en tout.
>* Cliquez ici pour accéder à l’[[!UICONTROL Explorateur d’API]](https://developer.adobe.com/workfront/api-explorer/).


Dans cette vidéo, vous apprendrez :

* En quoi consiste le mode texte
* En quoi consiste le camel case
* Quelques modes texte de base « plug and play » que vous pouvez utiliser dans vos filtres de rapport :

>[!VIDEO](https://video.tv.adobe.com/v/336820/?quality=12&learn=on)


## Tâche - Filtrer les tâches marquées « J’ai fait ma part ».

Le mode texte suivant exclut les tâches marquées « J’ai fait ma part ». Il vous suffit de créer un filtre de tâche, d’ajouter les règles de filtrage de votre choix, puis de passer en mode texte et de coller le code ci-dessous après tout mode texte que vous voyez dans le filtre.


>[!WARNING]
>
> Cette opération n’est pas destinée à être utilisée dans les filtres du calendrier.

```
EXISTS:1:$$OBJCODE=ASSGN  
EXISTS:1:taskID=FIELD:ID  
EXISTS:1:status=DN  
EXISTS:1:status_Mod=notin  
EXISTS:1:assignedToID=$$USER.ID 
```

## Tâche - Afficher toutes les tâches en attente d’approbation

```
approvalProcessID_Mod=notblank
currentUserApproversMM:ID=$$USER.ID
currentUserApproversMM:ID_Mod=in
currentUserApproversMM_Join=allowingnull
```

## Tâche - Afficher toutes les tâches que j’ai approuvées

Créez un rapport de tâche avec les filtres que vous souhaitez, puis allez dans l’onglet Filtre et cliquez sur Passer en mode texte. Ajoutez ce code à ce qui existe déjà :

```
approvalProcessID_Mod=notblank
approverStatuses:approvedByID=$$USER.ID
approverStatuses:approvedByID_Mod=in
```

## Tâche - Afficher toutes les tâches qui ont au moins un prédécesseur inter-projets

```
predecessorsMM:ID_Mod=notblank
predecessorsMM:projectID=FIELD:projectID
predecessorsMM:projectID_Mod=ne
```

## Tâche - Afficher toutes les tâches que j’ai assignées à d’autres personnes

Créez un rapport de tâche avec les filtres que vous souhaitez, puis allez dans l’onglet Filtre et cliquez sur Passer en mode texte. Ajoutez ce code à ce qui existe déjà :

>[!WARNING]
> 
> Cette opération n’est pas destinée à être utilisée dans les filtres du calendrier.

```
EXISTS:1:$$OBJCODE=ASSGN
EXISTS:1:taskID=FIELD:ID
EXISTS:1:assignedByID=$$USER.ID
```

Cela vous montrera toutes les tâches pour lesquelles la personne connectée a assigné au moins l’une des personnes assignées actuelles. Si les personnes assignées ont été assignées par plusieurs personnes, seul le nom de la première personne qui a assigné une personne apparaîtra comme « Demandé par » sur la page de destination de la tâche.

## Tâche - Afficher toutes les tâches qui sont terminées - En attente d’approbation

```
status=CPL:A
status_Mod=in
```


## Problème - Afficher tous les problèmes qui sont terminés - En attente d’approbation

```
status=CPL:A
status_Mod=in
```


## Projet - Afficher tous les projets qui sont terminés - En attente d’approbation

```
status=CPL:A
status_Mod=in
```


## Note - Afficher tous les commentaires dans lesquels je fais l’objet d’un balise

```
tags:userID=$$USER.ID
tags:userID_Mod=in
```


## Rapport sur les paramètres/champs personnalisés - Afficher les champs personnalisés qui ne sont pas liés à un formulaire personnalisé (très utile pour les efforts de nettoyage)

```
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:$$OBJCODE=CTGYPA
EXISTS:A:parameterID=FIELD:ID
```
