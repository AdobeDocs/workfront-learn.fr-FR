---
title: Comprendre les alertes par e-mail et les notifications de BAT
description: Comprenez la différence entre les alertes par e-mail et les notifications de BAT dans  [!DNL  Workfront].
feature: Workfront Proof
type: Tutorial
role: User
level: Beginner
thumbnail: email-alert-vs-proof-notifications.png
jira: KT-10174
last-substantial-update: 2024-01-24T00:00:00Z
exl-id: 51423110-960c-46ed-8b4e-6e73c67c42e0
source-git-commit: 30748311c14fb8aa6b10c03a74e83f46bdb5dfbf
workflow-type: tm+mt
source-wordcount: '306'
ht-degree: 100%

---

# Comprendre les alertes par e-mail et les notifications de BAT

Les alertes par e-mail sont différentes des e-mails de notification d’épreuves. Vous recevrez un e-mail de notification de BAT lorsqu’un nouveau BAT vous est affecté, lorsqu’un BAT est en retard ou lorsqu’il existe une nouvelle version du BAT que vous pouvez consulter.

![Une image d’un e-mail de notification d’épreuve indiquant qu’il existe un nouveau BAT à consulter.](assets/email-alert-1.png)

Si vous désactivez l’option de notification lors du chargement d’un BAT, personne ne recevra de communication de la part de [!DNL Workfront] concernant l’existence d’un nouveau BAT à consulter.

Des alertes par e-mail sont définies pour chaque réviseur ou réviseuse et approbateur ou approbatrice, le plus souvent lorsque l’épreuve est chargée. Un type par défaut d’alerte par e-mail peut être affecté aux personnes destinataires de vos BAT afin que vous n’ayez pas à le définir à chaque fois que vous chargez un BAT. Demandez à votre administrateur ou administratrice système de définir ces paramètres par défaut.

![Une image d’un e-mail d’alerte indiquant qu’une décision a été prise concernant l’épreuve et qu’il existe un commentaire à consulter.](assets/email-alert-2.png)

Même si les alertes par e-mail sont réglées sur [!UICONTROL Désactivé], les destinataires d’épreuves sont toujours informés d’une nouvelle épreuve ou d’une nouvelle version.

## Bonnes pratiques

| Bonne pratique | Voici pourquoi |
|---|---|
| Désactivez le paramètre « Envoyer des e-mails depuis Workfront lorsqu’un commentaire est fait sur un BAT » dans les paramètres de Workfront. | Lorsque ce paramètre est activé (ce qui est le cas par défaut), les utilisateurs et les utilisatrices ont la possibilité de recevoir plusieurs notifications par e-mail pour chaque commentaire sur une épreuve : une de la fonctionnalité de relecture et une autre de Workfront. Ces notifications en double entraînent une perturbation et une confusion dans les notifications par e-mail, ainsi qu’une boîte de réception pleine, ce qui peut amener les utilisateurs et les utilisatrices à ignorer les notifications d’épreuve qu’ils reçoivent. Ce qui, ensuite, pourrait signifier des échéances non respectées.<br> <br>Note : ce paramètre se trouve dans le menu principal de Workfront > Configuration > E-mail > Révision et approbation. |


