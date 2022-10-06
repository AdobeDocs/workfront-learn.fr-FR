---
title: Téléchargement à l’aide de processus automatisés
description: Découvrez quand utiliser un workflow de BAT automatisé, comment appliquer un workflow à l’aide d’un modèle de BAT et comment configurer entièrement un workflow automatisé.
activity: use
feature: Workfront Proof
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
thumbnail: 335133.png
kt: 8833
exl-id: 8301ef00-1f47-4779-aa35-c735b66fdcac
source-git-commit: c06dcc985c3b63781911e3c8cb1ac0f1a888ac7d
workflow-type: tm+mt
source-wordcount: '574'
ht-degree: 0%

---

# Chargement d’un BAT avec un workflow automatisé

Dans cette vidéo, vous apprendrez :

* Lorsqu’un workflow de BAT automatisé peut être utilisé
* Comment appliquer un workflow à l&#39;aide d&#39;un modèle de BAT
* Comment configurer entièrement un workflow automatisé

>[!VIDEO](https://video.tv.adobe.com/v/335133/?quality=12)



## Paramètres supplémentaires du workflow BAT

Les paramètres au bas de la fenêtre de chargement des BAT sont facultatifs. Vérifiez donc auprès de votre entreprise si et comment vous les utilisez.

![Une image de la fonction [!UICONTROL Nouvelle preuve ]avec la fenêtre [!UICONTROL Paramètres d’évaluation] surlignée.](assets/additional-proof-workflow-settings.png)

* **[!UICONTROL Verrouiller l’étape] —** Cela empêche les personnes qui se trouvent à l’étape du workflow de faire des commentaires ou de modifier des décisions une fois leur étape terminée.
* **[!UICONTROL Transférer les droits de décision Principaux vers] —** Accélérer le processus de vérification en désignant un Principal décideur. Lorsqu’elle est définie, [!DNL Workfront] reconnaît la décision du BAT par cette personne comme la décision . Une fois que cette personne a pris sa décision, la scène est finie et aucune autre décision n&#39;est nécessaire.
* **[!UICONTROL Exiger une seule décision pour cette étape] —** Une autre manière de rationaliser le processus de vérification consiste à ne demander qu’une seule décision sur le BAT. Lorsque cette option est activée, quel que soit le nombre d’approbateurs présents à cette étape, une fois que l’un d’eux a pris une décision, cette étape est terminée.
* **[!UICONTROL Rendre cette étape privée] —** Par défaut, tous les commentaires sur le BAT sont visibles à toutes les étapes. Empêchez les destinataires du BAT qui se trouvent à d’autres étapes de voir les commentaires effectués à cette étape en cliquant sur la case.

Au bas de la fenêtre de chargement du BAT se trouvent plusieurs paramètres de BAT qui affectent la sécurité de votre BAT, comme la nécessité d’une connexion pour afficher le BAT.

<!--
Learn more about these in the Proof settings section of the Configure a proof article.
-->

![Une image de la fonction [!UICONTROL Paramètres de BAT] de la fenêtre de téléchargement des BAT.](assets/additional-proof-workflow-settings-2.png)

<!--
### Learn more
* Automated workflow overview
* Automated workflow stages overview
-->

<!--
### Guides
* Plan an advanced workflow worksheet
-->

## Pourquoi êtes-vous dans le workflow de BAT ?

Vous remarquerez que vous êtes sur la liste des destinataires du BAT, car c’est vous qui chargez le BAT. Vous devenez également le propriétaire du BAT, qui vous donne les droits d&#39;édition sur le BAT, ce qui vous permet de modifier les configurations du workflow ou de charger une nouvelle version, entre autres.

![Une image de la fenêtre de chargement du BAT avec le propriétaire du BAT mis en surbrillance dans la liste des destinataires.](assets/proof-owner.png)

Si vous téléchargez le BAT, mais que quelqu’un d’autre gérera le workflow, vous pouvez modifier le propriétaire du BAT en cliquant sur l’ [!UICONTROL Propriétaire] et saisir leur nom. Ceci est recommandé si une autre personne que le téléchargeur d’origine télécharge une version.

## Votre tour

>[!IMPORTANT]
>
>N’oubliez pas de rappeler à vos collègues que vous leur envoyez un bon à tirer dans le cadre de votre formation Workfront.


Chargez un BAT avec un workflow avancé. Si des modèles de BAT sont déjà configurés pour votre entreprise, sélectionnez celui qui est utilisé par votre équipe, puis effectuez quelques ajustements.

* Ajustez les alertes par email afin que personne ne soit averti lorsque l’activité se produit sur le BAT.
* La première étape doit comporter 2 réviseurs/approbateurs.
* La deuxième étape ne doit comporter qu’un seul réviseur/approbateur.

Si aucun modèle de BAT n’est encore créé pour votre entreprise, configurez un workflow en 2 étapes.

* Inscrivez-vous et votre collègue préféré à la première étape.
* Définissez la date limite de la première étape 1 jour à partir de la création du BAT.
* Affectez un autre collègue favori à la deuxième étape.
* Lancez le démarrage lorsque la date limite de la première étape est dépassée.
* Donnez à la personne à cette étape 2 jours pour terminer la révision, mais elle doit le faire avant midi.


