---
title: Suivi de la progression du BAT
description: Découvrez comment utiliser [!UICONTROL SOCD] les indicateurs, la progression du BAT et les rapports permettant de suivre l’avancement d’un BAT dans [!DNL  Workfront].
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User
level: Beginner
thumbnail: track-proof-progress.png
jira: KT-10111
exl-id: 343483fe-487a-4a23-914d-2807a00630f9
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '674'
ht-degree: 1%

---

# Suivi de la progression du BAT

En tant que chef de projet, responsable de BAT ou autre partie prenante au processus de révision et d’approbation, vous souhaitez tracker l’état d’avancement de vos bons à tirer. Vous pouvez le faire avec [!DNL Workfront’s] intégré **indicateurs de progression du BAT** sur le [!UICONTROL Documents] ou en écrivant des rapports personnalisés.

Pour afficher la progression du BAT [!DNL Workfront], vous devez disposer d’une licence Plan, Travail ou Révision et être un utilisateur de vérification. Si vous n’êtes pas certain que votre [!DNL Workfront] le profil répond à ces exigences. contactez l’administrateur système de vérification de votre entreprise.

## Suivi de la progression du BAT [!UICONTROL SOCD] indicateurs et état du BAT

Obtenez une vue d’ensemble de l’avancement du BAT tout au long du processus de révision et d’approbation à l’aide de la variable [!UICONTROL SOCD] dans les [!UICONTROL Documents] liste. Ces icônes indiquent les actions spécifiques effectuées sur le BAT.

![Une image de la fonction [!UICONTROL Documents] dans une [!DNL  Workfront] avec la propriété [!UICONTROL SOCD] en surbrillance.](assets/manage-proofs-socd.png)

Les icônes indiquent le travail effectué sur un BAT depuis le moment où vous envoyez le BAT aux destinataires jusqu’au moment où ils prennent une décision sur le BAT.

* **S —** Le BAT a été envoyé aux destinataires.
* **O —** La preuve a été ouverte.
* **C —** Des commentaires ont été faits sur la preuve.
* **D —** Une décision a été prise sur le BAT (approuvé, rejeté, etc.).

Les couleurs indiquent si l’action est terminée ou non.

* **Blanc —** L’étape n’est pas encore arrivée.
* **Vert —** L’étape est terminée.
* **Orange —** L’échéance du BAT est fixée à 24 heures et l’étape n’a pas eu lieu.
* **Rouge —** La date limite du BAT est dépassée et l’étape n’a pas eu lieu.

Le [!UICONTROL SOCD] sur le [!UICONTROL Documents] , dans le panneau de résumé ou dans la variable [!UICONTROL Détails du document], est un résumé général de l’état d’avancement du BAT. [!DNL Workfront] configure ceci en fonction du destinataire qui est le &quot;plus à la traîne&quot; dans le processus de vérification.

Par exemple, s’il y a trois réviseurs/approbateurs et que seulement deux d’entre eux ont examiné le BAT et ont fait des commentaires, alors la variable [!UICONTROL SOCD] les icônes indiquent que le BAT a été envoyé ([!UICONTROL s]) et ouvert ([!UICONTROL O]) mais pas que des commentaires aient été faits ([!UICONTROL C]).

Si vous souhaitez savoir comment se comporte chaque destinataire de BAT, ouvrez le workflow de vérification. La progression globale du BAT se trouve en haut de la fenêtre. Chaque étape possède son propre indicateur de progression dans la barre grise.  Et à côté de chaque utilisateur se trouve la progression de cet individu.

![Une image de la fonction [!UICONTROL Workflow de vérification] d’un document.](assets/manage-proofs-socd-in-proofing-workflow-window.png)

## État du BAT

Le statut du BAT est basé sur le statut des destinataires du BAT de l’étape. L’état global du BAT est visible sur le [!UICONTROL Documents] , à droite de la [!UICONTROL SOCD] indicateurs, afin que vous puissiez facilement déterminer si vous avez une décision sur le BAT.

![Une image de la fonction [!UICONTROL Documents] dans une [!DNL  Workfront] avec l’état global du BAT en surbrillance.](assets/manage-proofs-overall-status.png)

Ce statut indique le statut global du BAT. Par exemple, si deux destinataires ont validé le BAT, leur statut individuel affiche [!UICONTROL Approuvé]. Cependant, le troisième destinataire n’a pas encore pris de décision, de sorte que le statut de cette personne est [!UICONTROL En attente]. Par conséquent, l’état global s’affiche comme suit : [!UICONTROL En attente].

Si des états personnalisés ont été configurés pour votre organisation, ils seront utilisés. Sinon, vous verrez les options d’état standard de :

* [!UICONTROL En attente]
* [!UICONTROL Approuvé]
* [!UICONTROL Approuvé avec des modifications]
* [!UICONTROL Modifications requises]
* [!UICONTROL Non pertinent]

Ouvrez la fenêtre du workflow de vérification afin d’afficher le statut du BAT pour les destinataires auxquels le [!UICONTROL Réviseur et approbateur] ou [!UICONTROL Approbateur]rôles de BAT.

## Rapports dans [!DNL Workfront]

Vous pouvez également tirer parti de [!DNL Workfront’s] fonctionnalités de création de rapports pour effectuer le suivi des bons à tirer au fil du processus de révision et d’approbation.

Un rapport d&#39;approbation de BAT vous permet de suivre les validations en cours pour vous assurer que les délais sont respectés.

![Une image d’un rapport d’approbation de BAT dans [!DNL  Workfront].](assets/proof-approval-report.png)

Un rapport de version de document vous permet de gérer et de suivre les versions de BAT.

![Image d’un rapport de version de document dans [!DNL  Workfront].](assets/document-version-report.png)

Nous vous recommandons de travailler avec vos [!DNL Workfront] consultant pour créer des rapports qui répondent aux exigences de votre entreprise. Certains rapports requièrent une connaissance approfondie de la fonction [!DNL Workfront’s] rapport en mode texte.

## Votre tour

Contactez votre équipe ou l’administrateur du système de vérification pour savoir quel type de rapport vous utiliserez dans Workfront pour que les workflows de BAT continuent à fonctionner correctement.

<!--
### Learn more
* Learn to create reports in [!DNL Workfront] with the Basic Report Creation course.
* View progress and status of a proof
* View activity on a proof within [!DNL Workfront]
-->
