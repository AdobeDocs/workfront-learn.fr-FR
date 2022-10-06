---
title: Créez des expressions ADDDAYS, ADDWEEKDAY, ADDMONTHES, ADDYEARS
description: Découvrez comment utiliser et créer des expressions ADD dans un champ calculé dans Adobe [!DNL Workfront].
feature: System Setup and Administration
type: Tutorial
role: Admin, Leader, User
level: Experienced
activity: use
team: Technical Marketing
thumbnail: 335175.png
kt: 8912
exl-id: f194fbc8-99b3-4fed-9fc5-a2f5fa4593d2
source-git-commit: 2b9a31b45ff94222a77c05292ee5b9d8229f5f0b
workflow-type: tm+mt
source-wordcount: '271'
ht-degree: 0%

---

# Créez des expressions ADDDAYS, ADDWEEKDAY, ADDMONTHES, ADDYEARS

Dans cette vidéo, vous apprendrez :

* Ce que calculent les expressions ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR
* Comment créer une expression de données ADDWEEKDAYS dans un champ calculé

>[!VIDEO](https://video.tv.adobe.com/v/335175/?quality=12)

## Exemples supplémentaires

Vous trouverez ci-dessous quelques autres Adobes d’expressions ADDDAYS/ADDWEEKDAY/ADDMONTHS/ADDYEAR [!DNL Workfront] les clients ont créé.

**Aurait dû être fait par**

Le client souhaitait savoir quand la tâche devait être terminée en fonction de la date de début réelle et de la durée planifiée. Dans ce cas, la date de fin prévue ne fonctionnera pas, car elle peut se déplacer si la tâche est en retard et la date de fin planifiée n’est pas utile en cas de retards dans les tâches antérieures.

L’expression créée était ADDDAYS(Date de début réelle,(Durée/480))

Le temps dans le champ Durée est stocké en minutes. Ainsi, dans cette expression, le champ Durée ne peut pas être autonome si le temps doit être reflété en jours. Pour ce faire, la durée doit être divisée par 480 minutes (480 minutes = 8 heures = 1 jour).

C’est pourquoi l’emplacement de la seconde valeur contient (Durée/480).


**Date de fin de la facture**

Cet exemple inclut un autre champ calculé, déjà créé et enregistré dans le système, dans l’expression.

Le client capturait la date d’envoi de la facture dans un champ de date personnalisé, intitulé &quot;Date d’envoi de la facture&quot;, dans le formulaire personnalisé. Une fois envoyées, elles disposent de 30 jours pour remplir et déposer la facture. Pour générer automatiquement cette date de fin et de soumission, ils ont créé un champ calculé à l’aide des champs ADDDAYS et Date d’envoi de la facture . L’expression ressemblait à ceci :

ADDDAYS(Date d’envoi de la facture,30)
