---
title: Créer les expressions ADDDAYS, ADDWEEKDAY, ADDMONTHES, ADDYEARS
description: Découvrez comment utiliser et créer des expressions ADD dans un champ calculé dans Adobe [!DNL Workfront].
feature: Custom Forms
type: Tutorial
role: Admin, Leader, User
level: Experienced
activity: use
team: Technical Marketing
thumbnail: 335175.png
jira: KT-8912
exl-id: f194fbc8-99b3-4fed-9fc5-a2f5fa4593d2
doc-type: video
TQID: 'https://experienceleague.adobe.com/22KjuMtDdhm9A6JohWlThfOHwKcegLwT3nuFO--70N4'
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
    internal-label: Leader
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
source-git-commit: 54883ad8c8df3aaee06ba8f8dca64227594c1c77
workflow-type: tm+mt
source-wordcount: '275'
ht-degree: 94%
---
# Créer les expressions ADDDAYS, ADDWEEKDAY, ADDMONTHES, ADDYEARS

Dans cette vidéo, vous apprendrez :

* Le calcul des expressions ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR
* Comment créer une expression de données ADDWEEKDAYS dans un champ calculé

>[!VIDEO](https://video.tv.adobe.com/v/3416189/?captions=fre_fr&quality=12&learn=on&enablevpops=1)

## Exemples supplémentaires

Vous trouverez ci-dessous quelques expressions ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR supplémentaires que les clientes et clients Adobe Workfront ont créées.

**Aurait dû être terminé le**

La personne souhaitait savoir quand la tâche aurait dû être terminée sur la base de la date de début effectif et de la durée prévue. Dans ce cas, la date d’achèvement prévue ne fonctionnera pas, car elle peut changer si la tâche est en retard et la date d’achèvement prévue n’est pas utile en cas de retards dans les tâches antérieures.

L’expression créée était ADDDAYS({actualStartDate},{durationMinutes}/480).

Le temps figurant dans le champ Durée est enregistré en minutes. Dans cette expression, le champ Durée ne peut donc pas être isolé si le temps doit être exprimé en jours. Pour ce faire, la durée doit être divisée par 480 minutes (480 minutes = 8 heures = 1 jour).

C’est pourquoi l’emplacement de la seconde valeur contient (Durée/480).


**Date d’achèvement de la facture**

Cet exemple comprend non seulement l’utilisation de l’expression ADDDAYS, mais également la création et l’enregistrement d’un champ personnalisé dans le formulaire personnalisé.

La personne capture la date d’envoi d’une facture via un champ de date personnalisé intitulé « Date d’envoi de la facture ».

Une fois envoyée, la facture doit être complétée et déposée dans les 30 jours. Pour produire automatiquement cette date d’achèvement et de dépôt, un champ calculé ADDDAYS est utilisé avec le champ personnalisé « Date d’envoi de la facture ». L’expression ressemble à ceci :

ADDDAYS({DE:Invoice Submission Date},30)
