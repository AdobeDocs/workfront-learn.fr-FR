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
last-substantial-update: 2024-01-24T00:00:00Z
exl-id: eac89e40-d3ea-4376-82a2-16bec550d131
doc-type: video
source-git-commit: bbdf99c6bc1be714077fd94fc3f8325394de36b3
workflow-type: tm+mt
source-wordcount: '432'
ht-degree: 100%

---

# Créer un modèle de workflow automatisé

Dans cette vidéo, vous apprendrez à :

* Créer un modèle de workflow automatisé pour les BAT de [!DNL  Workfront]
* Affecter des destinataires de BAT
* Définir une échéance pour le processus de révision et d’approbation
* Partager le modèle de workflow automatisé avec d’autres personnes

>[!VIDEO](https://video.tv.adobe.com/v/3454253/?quality=12&learn=on&enablevpops=1&captions=fre_fr)

## Options d’activation d’étape supplémentaires

Parmi les options permettant de déterminer le moment auquel une étape de workflow de BAT doit démarrer, deux sont rarement, voire jamais, utilisées : l’option [!UICONTROL Date et heure] et l’option « [!UICONTROL Lorsque l’échéance de l’étape précédente est dépassée] ».

La deuxième option ne fonctionne vraiment que dans les cas où vous disposez d’un grand groupe de personnes en train de réviser et que vous ne voulez pas attendre que tout le monde ait terminé. Il s’agit en quelque sorte d’une option du type « Je vous donne un certain temps pour terminer votre révision, après quoi vous perdrez la possibilité de réviser. » Mais cela aussi peut ralentir un processus de révision.

Si vous utilisez l’option « [!UICONTROL Lorsque l’échéance de l’étape précédente est dépassée] », il est important de se souvenir que vous pouvez activer manuellement une étape à tout moment si vous ne souhaitez pas attendre qu’une échéance soit dépassée.

## Bonnes pratiques

| Bonne pratique | Voici pourquoi |
|---|---|
| Définissez le rôle de BAT de la personne qui a créé le BAT sur Réviseur ou réviseuse. | Le rôle d’épreuve Réviseur garantit que la personne ayant créé l’épreuve peut faire des commentaires et accéder à ceux laissés par d’autres. La plupart du temps, la personne ayant créé un BAT n’est pas tenue de prendre une décision sur un BAT qu’elle a chargé. Les rôles d’approbation, de révision et d’approbation, de création ou de modération des épreuves exigent tous qu’une décision soit prise. Si la personne ayant créé l’épreuve se voit affecter l’un de ces rôles mais ne prend jamais de décision, cela peut avoir des conséquences négatives sur les échéances. |
| Évitez d’utiliser le rôle d’épreuve Approbateur. | Le rôle d’approbation ne permet pas à l’utilisateur ou à l’utilisatrice d’apporter des commentaires sur cette épreuve. Cela pourrait amener un utilisateur ou une utilisatrice à refuser le BAT, sans aucune explication, parce qu’il lui a été impossible de faire des commentaires. Utilisez plutôt le rôle Réviseur et approbateur d’épreuve pour que l’utilisateur ou l’utilisatrice puisse faire des commentaires. |
| Évitez l’option d’alerte par e-mail d’épreuve Toutes les activités. | Cette option permet d’envoyer une notification par e-mail à chaque fois qu’il se passe quelque chose avec une épreuve : un commentaire est fait, une réponse est publiée, une décision est prise, etc. Le ou la destinataire voit l’activité du BAT au fur et à mesure qu’elle se produit.<br><br>Pour les personnes propriétaires et les créateurs et créatrices de BAT, l’alerte par e-mail Décisions est la plus adaptée aux workflows de BAT en plusieurs étapes et la Décision finale est la plus adaptée aux workflows en une seule étape. En règle générale, tous les autres peuvent être désactivés, à moins qu’ils ne souhaitent être informés des commentaires ou décisions des autres personnes (dans ce cas, l’une des options d’envoi d’un résumé par e-mail peut se révéler plus efficace). |
