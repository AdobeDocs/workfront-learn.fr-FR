---
title: Charger un BAT avec un workflow automatisé
description: Découvrez quand utiliser un workflow de BAT automatisé, comment appliquer un workflow à l’aide d’un modèle de BAT et comment configurer entièrement un workflow automatisé.
activity: use
feature: Workfront Proof
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
thumbnail: 335133.png
jira: KT-8833
exl-id: 8301ef00-1f47-4779-aa35-c735b66fdcac
doc-type: video
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '579'
ht-degree: 100%

---

# Charger un BAT avec un workflow automatisé

Dans cette vidéo, vous apprendrez :

* Lorsqu’un workflow de BAT automatisé peut être utilisé
* Appliquer un workflow à l’aide d’un modèle de BAT
* Configurer entièrement un workflow automatisé

>[!VIDEO](https://video.tv.adobe.com/v/335133/?quality=12&learn=on)



## Paramètres supplémentaires du workflow de BAT

Les paramètres au bas de la fenêtre de chargement des BAT sont facultatifs. Vérifiez auprès de votre entreprise si et comment vous les utilisez.

![Image de la fenêtre [!UICONTROL Nouveau BAT] avec les [!UICONTROL Paramètres de l’étape] surlignés.](assets/additional-proof-workflow-settings.png)

* **[!UICONTROL Verrouiller l’étape] :** empêche les personnes qui se trouvent à l’étape du workflow de faire des commentaires ou de modifier des décisions une fois leur étape terminée.
* **[!UICONTROL Transférer les droits de décision principaux vers] :** accélère le processus de vérification en désignant une personne principale en charge des décisions. Lorsqu’il est défini, [!DNL Workfront] reconnaît le statut de décision du BAT de cette personne comme étant LA décision. Une fois que cette personne a pris sa décision, l’étape est finie et aucune autre décision n’est nécessaire.
* **[!UICONTROL Exiger une seule décision pour cette étape] :** une autre manière de rationaliser le processus d’épreuvage consiste à ne demander qu’une seule décision sur le BAT. Lorsque cette option est activée, quel que soit le nombre d’approbateurs ou d’approbatrices présents à cette étape, une fois que l’un d’eux a pris une décision, cette étape est terminée.
* **[!UICONTROL Rendre cette étape privée] :** par défaut, les commentaires sur le BAT sont visibles par tous dans toutes les étapes. Empêchez les destinataires du BAT qui se trouvent à d’autres étapes de voir les commentaires effectués à cette étape en cliquant sur la case.

Au bas de la fenêtre de chargement du BAT se trouvent plusieurs paramètres de BAT qui affectent la sécurité de votre BAT, comme la nécessité d’une connexion pour afficher le BAT.

<!--
Learn more about these in the Proof settings section of the Configure a proof article.
-->

![Image de la section [!UICONTROL Paramètres du BAT] de la fenêtre de chargement des BAT.](assets/additional-proof-workflow-settings-2.png)

<!--
### Learn more
* Automated workflow overview
* Automated workflow stages overview
-->

<!--
### Guides
* Plan an advanced workflow worksheet
-->

## Pourquoi êtes-vous dans le workflow de BAT ?

Vous remarquerez que vous figurez sur la liste des destinataires du BAT parce que c’est vous qui l’avez chargé. Vous devenez également le propriétaire du BAT, qui vous donne les droits d’édition sur le BAT et vous permet de modifier les configurations du workflow ou de charger une nouvelle version, entre autres.

![Image de la fenêtre de chargement du BAT avec le ou la propriétaire du BAT mis en surbrillance dans la liste des destinataires.](assets/proof-owner.png)

Si vous ne faites que charger le BAT mais que quelqu’un d’autre va gérer le workflow, vous pouvez changer le ou la propriétaire du BAT en cliquant sur le lien [!UICONTROL Propriétaire] et en saisissant son nom. Ceci est recommandé si une autre personne que la personne qui a chargé le BAT à l’origine charge une version.

## À vous

>[!IMPORTANT]
>
>Penser à rappeler à vos collaborateurs et collaboratrices que vous leur envoyez un BAT dans le cadre de votre formation Workfront.


Chargez un BAT à l’aide d’un workflow avancé. Si des modèles de BAT sont déjà configurés pour votre entreprise, sélectionnez celui qui est utilisé par votre équipe, puis effectuez quelques ajustements.

* Ajustez les alertes par e-mail afin que personne ne soit averti lorsque l’activité se produit sur le BAT.
* La première étape doit comporter 2 personnes en charge de la révision/de l’approbation.
* La deuxième étape ne doit comporter qu’une personne en charge de la révision/de l’approbation.

Si aucun modèle de BAT n’est encore créé pour votre entreprise, configurez un workflow en 2 étapes.

* Inscrivez-vous et votre collègue préféré à la première étape.
* Définissez la date limite de la première étape 1 jour à partir de la création du BAT.
* Affectez un ou une autre collègue à la deuxième étape.
* Lancez l’étape lorsque la date limite de la première étape est dépassée.
* Donnez à la personne à cette étape 2 jours pour terminer la vérification, mais elle doit le faire avant midi.


