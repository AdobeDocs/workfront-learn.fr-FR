---
title: Présentation du mode de texte de base pour les filtres
description: Découvrez le mode texte, la casse des chameaux et le mode texte de base "plug and play" que vous pouvez utiliser dans vos filtres de rapports dans Workfront.
activity: use
feature: Reports and Dashboards
thumbnail: 336820.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
kt: 9086
exl-id: b3f16468-b720-468d-887a-b313fc32bd89
doc-type: video
source-git-commit: d39754b619e526e1a869deedb38dd2f2b43aee57
workflow-type: tm+mt
source-wordcount: '416'
ht-degree: 0%

---

# Présentation du mode de texte de base pour les filtres

>[!IMPORTANT]
>
>Conditions préalables :
>
>* Présentation des éléments de reporting
>* Présentation des composants de création de rapports
>* Création d’un filtre de base


>[!TIP]
>
>* Pour mieux comprendre le mode texte, nous vous recommandons de regarder l’événement webinaire enregistré. [Demander à l’expert - Présentation du reporting en mode texte](https://experienceleague.adobe.com/docs/workfront-events/events/reporting-and-dashboards/introduction-to-text-mode-reporting.html?lang=en), qui dure une heure.
>* Pour en savoir plus sur le mode texte, nous vous recommandons de regarder la [Rapports avancés](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/advanced-reporting/welcome-to-advanced-reporting.html?lang=en) les tutoriels qui, ensemble, durent cinq heures et demie.



Dans cette vidéo, vous apprendrez :

* Quel mode de texte ?
* Quelle casse de chameau ?
* Un mode de texte de &quot;plug and play&quot; de base que vous pouvez utiliser dans les filtres de rapport

>[!VIDEO](https://video.tv.adobe.com/v/336820/?quality=12)


## Tâche - Filtrez les tâches où j’ai marqué &quot;Terminé avec ma part&quot;

Le mode de texte suivant exclut les tâches pour lesquelles un utilisateur a marqué &quot;Terminé avec mon article&quot;. Il vous suffit de créer un filtre de tâche, d’ajouter les règles de filtrage de votre choix, puis de passer en mode texte et de coller le code ci-dessous après tout mode texte que vous voyez dans le filtre.

```
EXISTS:1:$$OBJCODE=ASSGN  
EXISTS:1:taskID=FIELD:ID  
EXISTS:1:status=DN  
EXISTS:1:status_Mod=notin  
EXISTS:1:assignedToID=$$USER.ID 
```

## Tâche : affichez-moi toutes les tâches en attente de mon approbation

```
approvalProcessID_Mod=notblank
currentUserApproversMM:ID=$$USER.ID
currentUserApproversMM:ID_Mod=in
currentUserApproversMM_Join=allowingnull
```

## Tâche - Afficher toutes les tâches que j’ai approuvées

Créez un rapport de tâche avec les filtres de votre choix, puis accédez à l’onglet Filtre et cliquez sur Passer en mode Texte. Ajoutez ce code à ce qui existe déjà :

```
approvalProcessID_Mod=notblank
approverStatuses:approvedByID=$$USER.ID
approverStatuses:approvedByID_Mod=in
```

## Tâche : affichez-moi toutes les tâches ayant au moins un prédécesseur de projet croisé.

```
predecessorsMM:ID_Mod=notblank
predecessorsMM:projectID=FIELD:projectID
predecessorsMM:projectID_Mod=ne
```

## Tâche - Afficher toutes les tâches que j’ai assignées aux autres

Créez un rapport de tâche avec les filtres de votre choix, puis accédez à l’onglet Filtre et cliquez sur Passer en mode Texte. Ajoutez ce code à ce qui existe déjà :

```
EXISTS:1:$$OBJCODE=ASSGN
EXISTS:1:taskID=FIELD:ID
EXISTS:1:assignedByID=$$USER.ID
```

Vous verrez alors toutes les tâches pour lesquelles l’utilisateur connecté a attribué au moins l’un des personnes actuellement désignées. Si des personnes désignées ont été affectées par plusieurs personnes, seul le nom de la première personne qui a affecté une personne apparaît comme &quot;Demandé par&quot; sur la page d’entrée de la tâche.

## Tâche : affichez-moi toutes les tâches terminées - Autorisation en attente

```
status=CPL:A
status_Mod=in
```


## Problème : affichez-moi tous les problèmes terminés - Autorisation en attente

```
status=CPL:A
status_Mod=in
```


## Projet : affichez-moi tous les projets terminés - En attente d’approbation

```
status=CPL:A
status_Mod=in
```


## Remarque : affichez-moi tous les commentaires sur lesquels je suis balisé.

```
tags:userID=$$USER.ID
tags:userID_Mod=in
```


## Rapport de champs personnalisés/de paramètres : affichez-moi les champs personnalisés qui ne sont pas associés à un formulaire personnalisé (très utile dans les efforts de nettoyage).

```
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:$$OBJCODE=CTGYPA
EXISTS:A:parameterID=FIELD:ID
```
