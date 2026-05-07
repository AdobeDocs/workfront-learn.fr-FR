---
title: Créer des filtres avec des caractères génériques basés sur la date
description: Découvrez comment et à quel moment utiliser des caractères génériques basés sur la date et comment créer un filtre basé sur la date actuelle.
activity: use
feature: Reports and Dashboards
thumbnail: 336812.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
last-substantial-update: '2025-06-27T00:00:00.000Z'
jira: KT-9082
exl-id: 0f7db4eb-a062-4eb3-99ca-c40d8e266943
doc-type: video
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
subfeature_v2:
  - id: ceb4d94a-32ed-4fea-9724-1339d684b0bc
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
autotag-review: '2026-05-06T13:57:08.996Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 246
ht-degree: 100%

---

# Créer des filtres avec des caractères génériques basés sur la date

Dans cette vidéo, vous apprendrez à :

* Présentation des caractères génériques basés sur la date
* Comprendre la différence entre les deux caractères génériques Workfront basés sur la date
* Ajouter un caractère générique basé sur la date à un filtre
* Créer une date personnalisée à l’aide de caractères génériques, d’attributs, d’opérateurs et de modificateurs
* Créer une période personnalisée à l’aide de caractères génériques

>[!VIDEO](https://video.tv.adobe.com/v/3412660/?captions=fre_fr&quality=12&learn=on&enablevpops=0)


## Activité Créer des filtres avec des caractères génériques basés sur la date


### Questions d’activité

1. Quelle serait la règle de filtrage pour que les problèmes aient une échéance à la date d’hier ou d’aujourd’hui ?
1. Quelle serait la règle de filtrage pour trouver les projets arrivés à échéance la semaine dernière ?
1. Les règles de filtrage suivantes font partie d’un rapport de tâches que vous utilisez régulièrement. Quel type de résultats obtiendriez-vous de ce rapport ?

![Une image de l’écran de création d’un filtre de tâche avec un caractère générique basé sur la date](assets/date-wildcard-answer-1.png)

### Réponses

1. Filtrage de la date d’achèvement prévue du problème entre [!UICONTROL $$TODAY-1d] et [!UICONTROL $$TODAY].
1. Filtrage de la date de fin prévue du projet entre [!UICONTROL $$TODAYb-1w] et [!UICONTROL $$TODAYe-1w].
1. Ce rapport recherche les tâches qui vous ont été affectées et qui ne sont pas encore terminées (en d’autres termes, dont le pourcentage de réalisation est inférieur à 100), et qui sont en retard ou qui doivent être terminées aujourd’hui. La règle de filtrage de la date d’achèvement prévue des tâches indique d’examiner les tâches dont la date d’échéance est égale ou antérieure à la date du jour.
