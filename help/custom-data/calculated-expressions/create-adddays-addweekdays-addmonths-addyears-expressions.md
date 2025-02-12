---
title: Créer les expressions ADDDAYS, ADDWEEKDAY, ADDMONTHES, ADDYEARS
description: Découvrez comment utiliser et créer des expressions ADD dans un champ calculé dans Adobe  [!DNL Workfront].
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
source-git-commit: d17df7162ccaab6b62db34209f50131927c0a532
workflow-type: tm+mt
source-wordcount: '281'
ht-degree: 100%

---

# Créer les expressions ADDDAYS, ADDWEEKDAY, ADDMONTHES, ADDYEARS

Dans cette vidéo, vous apprendrez :

* Le calcul des expressions ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR
* Comment créer une expression de données ADDWEEKDAYS dans un champ calculé

>[!VIDEO](https://video.tv.adobe.com/v/335175/?quality=12&learn=on&enablevpops)

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
