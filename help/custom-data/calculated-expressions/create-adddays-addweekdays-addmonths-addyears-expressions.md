---
title: Créez des expressions ADDDAYS, ADDWEEKDAY, ADDMONTHES, ADDYEARS
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
source-git-commit: 409147f9a62302d28e14b834981992a0421d4e4b
workflow-type: tm+mt
source-wordcount: '273'
ht-degree: 0%

---

# Créez des expressions ADDDAYS, ADDWEEKDAY, ADDMONTHES, ADDYEARS

Dans cette vidéo, vous apprendrez :

* Ce que calculent les expressions ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR
* Comment créer une expression de données ADDWEEKDAYS dans un champ calculé

>[!VIDEO](https://video.tv.adobe.com/v/335175/?quality=12&learn=on)

## Exemples supplémentaires

Vous trouverez ci-dessous quelques expressions ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR supplémentaires que les clients Adobe Workfront ont créées.

**Aurait dû être fait par**

Le client souhaitait savoir quand la tâche devait être terminée en fonction de la date de début réelle et de la durée planifiée. Dans ce cas, la date de fin prévue ne fonctionnera pas, car elle peut se déplacer si la tâche est en retard et la date de fin planifiée n’est pas utile en cas de retards dans les tâches antérieures.

L’expression créée était ADDDAYS({actualStartDate},{durationMinutes}/480)

Le temps dans le champ Durée est stocké en minutes. Ainsi, dans cette expression, le champ Durée ne peut pas être autonome si le temps doit être reflété en jours. Pour ce faire, la durée doit être divisée par 480 minutes (480 minutes = 8 heures = 1 jour).

C’est pourquoi l’emplacement de la seconde valeur contient (Durée/480).


**Date de fin de la facture**

Cet exemple comprend non seulement l’utilisation de l’expression ADDDAYS, mais également la création et l’enregistrement d’un champ personnalisé dans le formulaire personnalisé.

Le client capture la date d’envoi d’une facture via un champ de date personnalisé intitulé &quot;Date d’envoi de la facture&quot;.

Une fois envoyée, la facture doit être complétée et déposée dans les 30 jours. Pour générer automatiquement cette date de fin et de classement, un champ calculé ADDDAYS est utilisé avec le champ personnalisé &quot;Date d’envoi de la facture&quot;. L’expression ressemble à ceci :

ADDDAYS({DE:Invoice Submission Date},30)
