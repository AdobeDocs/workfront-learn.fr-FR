---
title: Créer un modèle de workflow automatisé
description: Découvrez comment créer un modèle de workflow automatisé en affectant des destinataires de BAT et en établissant des échéances pour les BAT. Partagez ensuite le modèle avec d’autres utilisateurs et utilisatrices.
activity: use
feature: Workfront Proof
type: Tutorial
role: User, Admin
level: Intermediate
team: Technical Marketing
thumbnail: 335130.png
jira: KT-8830
last-substantial-update: '2024-01-24T00:00:00.000Z'
exl-id: eac89e40-d3ea-4376-82a2-16bec550d131
doc-type: video
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
autotag-review: '2026-05-05T20:09:06.617Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 435
ht-degree: 91%

---

# Créer un modèle de workflow automatisé

Dans cette vidéo, vous apprendrez à :

* Créer un modèle de workflow automatisé pour les épreuves de [!DNL &#x200B; Workfront]
* Affecter des destinataires de BAT
* Définir une échéance pour le processus de révision et d’approbation
* Partager le modèle de workflow automatisé avec d’autres personnes

>[!VIDEO](https://video.tv.adobe.com/v/335130/?quality=12&learn=on&enablevpops=1)

## Options d’activation d’étape supplémentaires

Parmi les options permettant de déterminer le moment auquel une étape de workflow de relecture doit démarrer, deux sont rarement, voire jamais, utilisées : l’option [!UICONTROL Date et heure] et l’option « [!UICONTROL Lorsque l’échéance de l’étape précédente est dépassée] ».

La deuxième option ne fonctionne vraiment que dans les cas où vous disposez d’un grand groupe de personnes en train de réviser et que vous ne voulez pas attendre que tout le monde ait terminé. Il s’agit en quelque sorte d’une option du type « Je vous donne un certain temps pour terminer votre révision, après quoi vous perdrez la possibilité de réviser. » Mais cela aussi peut ralentir un processus de révision.

Si vous utilisez l’option « [!UICONTROL Lorsque l’échéance de l’étape précédente est dépassée] », il est important de se souvenir que vous pouvez activer manuellement une étape à tout moment si vous ne souhaitez pas attendre qu’une échéance soit dépassée.

## Bonnes pratiques

| Bonne pratique | Voici pourquoi |
|---|---|
| Définissez le rôle de BAT de la personne qui a créé le BAT sur Réviseur ou réviseuse. | Le rôle d’épreuve Réviseur garantit que la personne ayant créé l’épreuve peut faire des commentaires et accéder à ceux laissés par d’autres. La plupart du temps, la personne ayant créé un BAT n’est pas tenue de prendre une décision sur un BAT qu’elle a chargé. Les rôles d’approbation, de révision et d’approbation, de création ou de modération des épreuves exigent tous qu’une décision soit prise. Si la personne ayant créé l’épreuve se voit affecter l’un de ces rôles mais ne prend jamais de décision, cela peut avoir des conséquences négatives sur les échéances. |
| Évitez d’utiliser le rôle d’épreuve Approbateur. | Le rôle d’approbation ne permet pas à l’utilisateur ou à l’utilisatrice d’apporter des commentaires sur cette épreuve. Cela pourrait amener un utilisateur ou une utilisatrice à refuser le BAT, sans aucune explication, parce qu’il lui a été impossible de faire des commentaires. Utilisez plutôt le rôle Réviseur et approbateur d’épreuve pour que l’utilisateur ou l’utilisatrice puisse faire des commentaires. |
| Évitez l’option d’alerte par e-mail d’épreuve Toutes les activités. | Cette option envoie une notification d’épreuve par e-mail chaque fois qu’un événement se produit avec une épreuve (qu’un commentaire soit posté, qu’une réponse soit publiée, qu’une décision soit prise, etc.). Le destinataire voit essentiellement l’activité de l’épreuve lorsqu’elle se produit.<br><br>Pour les personnes propriétaires et les créateurs et créatrices de BAT, l’alerte par e-mail Décisions est la plus adaptée aux workflows de BAT en plusieurs étapes et la Décision finale est la plus adaptée aux workflows en une seule étape. En règle générale, tous les autres peuvent être désactivés, à moins qu’ils ne souhaitent être informés des commentaires ou décisions des autres personnes (dans ce cas, l’une des options d’envoi d’un résumé par e-mail peut se révéler plus efficace). |
