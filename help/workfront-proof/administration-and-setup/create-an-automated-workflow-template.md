---
title: Créer un modèle de workflow automatisé
description: Découvrez comment créer un modèle de workflow automatisé en affectant les destinataires du BAT et en définissant les échéances du BAT. Partagez ensuite le modèle avec d’autres utilisateurs.
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
ht-degree: 0%

---

# Créer un modèle de workflow automatisé

Dans cette vidéo, vous apprendrez à :

* Création d’un modèle de processus automatisé pour [!DNL  Workfront] vérification
* Attribution de destinataires BAT
* Définition d’une date limite de processus de révision et d’approbation
* Partage du modèle de workflow automatisé avec d’autres personnes

>[!VIDEO](https://video.tv.adobe.com/v/335130/?quality=12&learn=on)

## Options d’activation d’étape supplémentaires

Deux options permettant de déterminer à quel moment une étape de workflow de vérification doit démarrer sont rarement, voire jamais, utilisées : la variable [!UICONTROL Date et heure] et le[!UICONTROL Lorsque la date limite de la phase précédente est dépassée]&quot;.

La deuxième option ne fonctionne vraiment que dans les scénarios où un grand groupe de personnes passe en revue et que vous ne voulez pas attendre tous. C&#39;est une sorte de &quot;Je vais vous donner un certain temps pour terminer votre examen, puis vous perdrez votre chance&quot;. Mais même cela peut ralentir un processus d&#39;examen.

Si vous utilisez &quot;[!UICONTROL lorsque la date limite de la phase précédente est dépassée ;],&quot; il est important de se souvenir que vous pouvez activer manuellement une étape à tout moment si vous ne souhaitez pas attendre qu’une date limite soit dépassée.

## Bonnes pratiques

| Bonne pratique | Voici pourquoi : |
|---|---|
| Définissez le rôle de BAT du créateur du BAT sur Réviseur. | Le rôle du BAT du réviseur permet au créateur du BAT de faire des commentaires et d’accéder aux commentaires laissés par d’autres personnes. La plupart du temps, le créateur du BAT n&#39;est pas tenu de prendre une décision sur un BAT qu&#39;il a téléchargé. Les rôles de BAT Approbateur, Réviseur et approbateur, Auteur ou Modérateur requièrent tous une décision. Si le créateur du BAT se voit attribuer l’un de ces rôles de BAT, mais qu’il ne prend jamais de décision, cela peut avoir une incidence négative sur les délais du BAT. |
| Évitez d’utiliser le rôle d’approbateur de BAT. | Le rôle d’ approbateur de BAT ne permet pas à l’utilisateur de faire des commentaires sur ce BAT. Cela peut entraîner un refus du BAT de la part d&#39;un utilisateur, sans aucune explication, car il ne peut pas faire de commentaires. Utilisez plutôt le rôle de BAT Réviseur et approbateur afin que l’utilisateur puisse fournir des commentaires. |
| Évitez l’option d’alerte par email de toutes les activités BAT . | Cette option envoie une notification par email de BAT chaque fois qu’un événement se produit avec un BAT : un commentaire est émis, une réponse est publiée, une décision est prise, etc. Le destinataire voit essentiellement l’activité du BAT au fur et à mesure.<br><br>Pour les propriétaires et les créateurs de BAT, l’alerte par e-mail Decisions fonctionne le mieux pour les workflows de BAT à plusieurs étapes et la décision finale fonctionne le mieux pour les workflows à une seule étape. En règle générale, tout le monde peut être défini sur Désactivé, sauf s’il souhaite être averti des commentaires ou décisions d’autres personnes (auquel cas, l’une des options de résumé du courrier électronique peut fonctionner le mieux). |
