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
source-git-commit: 30748311c14fb8aa6b10c03a74e83f46bdb5dfbf
workflow-type: tm+mt
source-wordcount: '432'
ht-degree: 56%

---

# Créer un modèle de workflow automatisé

Dans cette vidéo, vous apprendrez à :

* Créer un modèle de workflow automatisé pour les BAT de [!DNL  Workfront]
* Affecter des destinataires de BAT
* Définir une échéance pour le processus de révision et d’approbation
* Partager le modèle de workflow automatisé avec d’autres personnes

>[!VIDEO](https://video.tv.adobe.com/v/335130/?quality=12&learn=on)

## Options d’activation d’étape supplémentaires

Deux options permettant de déterminer à quel moment une étape de workflow de vérification doit démarrer sont rarement, voire jamais, utilisées : la variable [!UICONTROL Date et heure] et le[!UICONTROL Lorsque la date limite de la phase précédente est dépassée]&quot;.

La deuxième option ne fonctionne vraiment que dans les scénarios où un grand groupe de personnes passe en revue et que vous ne voulez pas attendre tous. C&#39;est une sorte de &quot;Je vais vous donner un certain temps pour terminer votre examen, puis vous perdrez votre chance&quot;. Mais cela aussi peut ralentir un processus de révision.

Si vous utilisez &quot;[!UICONTROL lorsque la date limite de la phase précédente est dépassée ;],&quot; il est important de se souvenir que vous pouvez activer manuellement une étape à tout moment si vous ne souhaitez pas attendre qu’une date limite soit dépassée.

## Bonnes pratiques

| Bonne pratique | Voici pourquoi : |
|---|---|
| Définissez le rôle de BAT du créateur du BAT sur Réviseur. | Le rôle d’épreuve Réviseur garantit que la personne ayant créé l’épreuve peut faire des commentaires et accéder à ceux laissés par d’autres. La plupart du temps, le créateur du BAT n&#39;est pas tenu de prendre une décision sur un BAT qu&#39;il a téléchargé. Les rôles d’approbation, de révision et d’approbation, de création ou de modération des épreuves exigent tous qu’une décision soit prise. Si la personne ayant créé l’épreuve se voit affecter l’un de ces rôles mais ne prend jamais de décision, cela peut avoir des conséquences négatives sur les échéances. |
| Évitez d’utiliser le rôle d’épreuve Approbateur. | Le rôle d’approbation ne permet pas à l’utilisateur ou à l’utilisatrice d’apporter des commentaires sur cette épreuve. Cela peut entraîner un refus du BAT de la part d&#39;un utilisateur, sans aucune explication, car il ne peut pas faire de commentaires. Utilisez plutôt le rôle Réviseur et approbateur d’épreuve pour que l’utilisateur ou l’utilisatrice puisse faire des commentaires. |
| Évitez l’option d’alerte par e-mail d’épreuve Toutes les activités. | Cette option permet d’envoyer une notification par e-mail à chaque fois qu’il se passe quelque chose avec une épreuve : un commentaire est fait, une réponse est publiée, une décision est prise, etc. Le ou la destinataire voit l’activité du BAT au fur et à mesure qu’elle se produit.<br><br>Pour les propriétaires et les créateurs de BAT, l’alerte par e-mail Decisions fonctionne le mieux pour les workflows de BAT à plusieurs étapes et la décision finale fonctionne le mieux pour les workflows à une seule étape. En règle générale, tous les autres peuvent être désactivés, à moins qu’ils ne souhaitent être informés des commentaires ou décisions des autres personnes (dans ce cas, l’une des options d’envoi d’un résumé par e-mail peut se révéler plus efficace). |
