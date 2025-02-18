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
jira: KT-9082
exl-id: 0f7db4eb-a062-4eb3-99ca-c40d8e266943
doc-type: video
source-git-commit: 88c2161e897f23587ccc1d0e867b6f8961927a0f
workflow-type: tm+mt
source-wordcount: '247'
ht-degree: 71%

---

# Créer des filtres avec des caractères génériques basés sur la date

Dans cette vidéo, vous apprendrez à :

* Présentation des caractères génériques basés sur la date
* Comprenez la différence entre Workfront et deux caractères génériques basés sur la date
* Ajouter un caractère générique basé sur la date à un filtre
* Créer une date personnalisée à l’aide de caractères génériques, d’attributs, d’opérateurs et de modificateurs
* Créer une période personnalisée à l’aide de caractères génériques

>[!VIDEO](https://video.tv.adobe.com/v/336812/?quality=12&learn=on)


## Création de filtres avec des activités de caractères génériques basées sur la date

Pour télécharger un fichier PDF de cette page, [cliquez ici](/help/assets/create-filters-with-date-based-wildcards-activities.pdf).

### Questions d’activité

1. Quelle serait la règle de filtrage pour que les problèmes aient une échéance à la date d’hier ou d’aujourd’hui ?
1. Quelle serait la règle de filtrage pour trouver les projets arrivés à échéance la semaine dernière ?
1. Les règles de filtrage suivantes font partie d’un rapport de tâches que vous utilisez régulièrement. Quel type de résultats obtiendriez-vous de ce rapport ?

![Une image de l’écran de création d’un filtre de tâche avec un caractère générique basé sur la date](assets/date-wildcard-answer-1.png)

### Réponses

1. Filtrage de la date d’achèvement prévue du problème entre [!UICONTROL $$TODAY-1d] et [!UICONTROL $$TODAY].
1. Filtrage de la date de fin prévue du projet entre [!UICONTROL $$TODAYb-1w] et [!UICONTROL $$TODAYe-1w].
1. Ce rapport recherche les tâches qui vous sont affectées et qui ne sont pas encore terminées (en d&#39;autres termes, dont le pourcentage d&#39;achèvement est inférieur à 100), et qui sont en retard ou dues aujourd&#39;hui. La règle de filtrage pour la date d&#39;achèvement prévue des tâches indique d&#39;examiner les tâches dont la date d&#39;échéance est égale ou antérieure à la date d&#39;aujourd&#39;hui.
