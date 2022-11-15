---
title: Comprendre le mode de texte de base pour les regroupements
description: Découvrez le mode texte, la casse des chameaux et le mode texte de base "plug and play" que vous pouvez utiliser dans vos regroupements dans Workfront.
activity: use
feature: Reports and Dashboards
thumbnail: 336820.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
kt: 11369
exl-id: 5f45c64f-a22b-4983-91fd-9a1939f99fb1
source-git-commit: 818ee105af32589cb0e297e6f419a4a449a60052
workflow-type: tm+mt
source-wordcount: '267'
ht-degree: 0%

---

# Comprendre le mode de texte de base pour les regroupements

>[!IMPORTANT]
>
>Conditions préalables :
>
>* Présentation des éléments de reporting
>* Présentation des composants de création de rapports
>* Créer un groupement de base


>[!TIP]
>
>* Pour mieux comprendre le mode texte, nous vous recommandons de regarder l’événement webinaire enregistré. [Demander à l’expert - Présentation du reporting en mode texte](https://experienceleague.adobe.com/docs/workfront-events/events/reporting-and-dashboards/introduction-to-text-mode-reporting.html?lang=en), qui dure une heure.
>* Pour en savoir plus sur le mode texte, nous vous recommandons de regarder la [Rapports avancés](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/advanced-reporting/welcome-to-advanced-reporting.html?lang=en) les tutoriels qui, ensemble, durent cinq heures et demie.


Dans cette vidéo, vous apprendrez :

* Quel mode de texte ?
* Quelle casse de chameau ?
* Un mode de texte &quot;plug and play&quot; de base que vous pouvez utiliser dans vos regroupements.

>[!VIDEO](https://video.tv.adobe.com/v/3410641/?quality=12)

## Tâche - Groupement 4 parents

Le mode de texte suivant regroupe les tâches en fonction de quatre niveaux de parents au maximum et laisse les parents qui n’existent pas vides.

```
textmode=true
group.0.name=Parents
group.0.valueexpression=CONCAT({parent}.{parent}.{parent}.{parent}.{name},IF(ISBLANK({parent}.{parent}.{parent}.{parent}.{name}),"",", "),{parent}.{parent}.{parent}.{name},IF(ISBLANK({parent}.{parent}.{parent}.{name}),"",", "),{parent}.{parent}.{name},IF(ISBLANK({parent}.{parent}.{name}),"",", "),IF(ISBLANK({parent}.{name}),"No parent",{parent}.{name}))
group.0.linkedname=parent
group.0.namekeyargkey.0=parent
group.0.namekeyargkey.1=name
group.0.valueformat=string
```

![Image d’écran montrant les tâches du projet regroupées par 4 parents](assets/4-parents-grouping.png)


## Tâche - Regroupement en pourcentage terminé

Le mode de texte suivant regroupe les tâches en fonction de leur pourcentage d’achèvement. Les tâches sont regroupées dans l’une des catégories suivantes :

* 0%
* 1 % à 25 %
* 26 % à 50 %
* 51 à 75 %
* 76 % à 99 %
* 100 %

```
group.0.linkedname=direct
group.0.namekey=percentComplete
group.0.valueexpression=IF({percentComplete}<1,"0%",IF({percentComplete}<26,"1% to 25%",IF({percentComplete}<51,"26% to 50%",IF({percentComplete}<76,"51% to 75%",IF({percentComplete}<100,"76% to 99%",IF({percentComplete}=100,"100","***"))))))
group.0.valueformat=doubleAsString
textmode=true
```

![Image d’écran montrant les tâches du projet regroupées par pourcentage de réalisation](assets/percent-complete-grouping.png)

## Task - statusEquatesWith, puis status

Le mode de texte suivant regroupe les tâches par statusEquatesWith, puis par status.

```
group.0.enumclass=com.attask.common.constants.TaskStatusEnum
group.0.enumtype=TASK
group.0.linkedname=direct
group.0.name=State
group.0.type=enum
group.0.valuefield=statusEquatesWith
group.0.valueformat=val
group.1.enumclass=com.attask.common.constants.TaskStatusEnum
group.1.enumtype=TASK
group.1.linkedname=direct
group.1.namekey=status
group.1.type=enum
group.1.valuefield=status
group.1.valueformat=val
textmode=true
```

![Image d’écran montrant les tâches de projet regroupées par statusEquatesWith](assets/status-equates-with.png)


## Approbation de BAT - Groupe par nom de projet

```
group.0.valueformat=HTML
group.0.valuefield=documentVersion:document:project:name
group.0.displayname=Project Name
```

![Image d&#39;écran montrant les validations du BAT regroupées par nom de projet](assets/proof-approvals-grouped-by-project-name.png)

