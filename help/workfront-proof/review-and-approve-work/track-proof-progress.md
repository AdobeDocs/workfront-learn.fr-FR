---
title: Suivre la progression du BAT
description: Découvrez comment utiliser les indicateurs [!UICONTROL SOCD], la progression de la relecture et les rapports pour suivre la progression d’un BAT dans  [!DNL &#x200B; Workfront].
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User
level: Beginner
thumbnail: track-proof-progress.png
jira: KT-10111
exl-id: 343483fe-487a-4a23-914d-2807a00630f9
source-git-commit: 8ad86921177da189503211635116146e886dbd17
workflow-type: tm+mt
source-wordcount: '767'
ht-degree: 64%

---

# Suivre la progression du BAT

En tant que chef de projet, responsable d’épreuve ou autre partie prenante dans le processus de révision et d’approbation, vous souhaiterez suivre la progression de vos épreuves. Vous pouvez le faire à l’aide des **indicateurs de progression de la relecture** intégrés de [!DNL Workfront's], sur la page [!UICONTROL Documents] ou en rédigeant des rapports personnalisés.

Pour afficher la progression de la relecture sur [!DNL Workfront], vous devez disposer d’une licence de planification, de travail ou de révision et être un utilisateur ou une utilisatrice en charge de la relecture. Si vous n’êtes pas sûr que votre profil [!DNL Workfront] répond à ces exigences, contactez l’administrateur ou l’administratrice du système de relecture de votre entreprise.

## Suivre la progression de la relecture avec les indicateurs [!UICONTROL SOCD] et le statut du BAT

Obtenez une vue de haut niveau de la progression du BAT dans le processus de révision et d’approbation en utilisant les icônes [!UICONTROL SOCD] dans la liste [!UICONTROL Documents]. Ces icônes indiquent les actions spécifiques effectuées sur le BAT.

![Une image de la liste [!UICONTROL Documents] dans un projet [!DNL &#x200B; Workfront] avec les icônes [!UICONTROL SOCD] en surbrillance.](assets/manage-proofs-socd.png)

Les icônes indiquent le travail effectué sur un BAT entre le moment où vous envoyez le BAT aux destinataires et le moment où ils ou elles prennent une décision sur le BAT.

* **S -** Le BAT a été envoyé aux destinataires.
* **O -** Le BAT a été ouvert.
* **C -** Le BAT a fait l’objet de commentaires.
* **D -** Une décision a été prise à propos du BAT (approuvé, refusé, etc.).

Les couleurs indiquent si l’action est terminée ou non.

* **Blanc —** L&#39;étape n&#39;a pas encore eu lieu.
* **Vert -** L’étape est terminée.
* **Orange —** La date limite de dépôt du BAT est dans les 24 heures et l&#39;étape n&#39;a pas eu lieu.
* **Rouge —** La date limite de création du BAT est passée et l&#39;étape n&#39;a pas eu lieu.

La [!UICONTROL SOCD] dans la liste [!UICONTROL Documents], dans le panneau de résumé ou dans la [!UICONTROL Détails du document], est un résumé de haut niveau de la progression de l’épreuve. [!DNL Workfront] configure ce paramètre en fonction du destinataire le plus « en retard » dans le processus de relecture.

Par exemple, si vous disposez de trois personnes réalisant la révision/l’approbation et que seules deux d’entre elles ont examiné le BAT et apporté des commentaires, les icônes [!UICONTROL SOCD] indiqueront que le BAT a été envoyé ([!UICONTROL S]) et ouvert ([!UICONTROL O]), mais pas que des commentaires ont été apportés ([!UICONTROL C]).

**&#x200B;**&#x200B;Une fois qu’une décision finale (par exemple, Approuvée ou Rejetée) est prise sur une épreuve, tous les indicateurs SOCD peuvent apparaître en vert pour les utilisateurs à cette étape, même si des actions individuelles (telles que l’ouverture de l’épreuve ou la formulation de commentaires) n’ont pas été effectuées. Il s’agit d’un comportement à l’échelle du système conçu pour refléter l’achèvement de l’étape globale, et non l’engagement individuel.

**Avant l’enregistrement d’une décision** chaque indicateur SOCD reflète l’activité réelle de l’utilisateur (par exemple, blanc si aucune action n’a été entreprise, vert si l’action a été effectuée). Une fois la décision prise, le système suppose que le workflow est terminé et met à jour tous les indicateurs en conséquence.

Si vous souhaitez connaître l’état d’avancement de chaque destinataire du BAT, ouvrez le workflow de relecture. La progression globale de la relecture est indiquée en haut de la fenêtre. Chaque étape possède son propre indicateur de progression dans la barre grise.  Et à côté de chaque utilisateur se trouve le progrès de cet individu.

![Une image de la section [!UICONTROL Workflow de relecture] d’un document.](assets/manage-proofs-socd-in-proofing-workflow-window.png)

## Statut du BAT

Le statut du BAT est basé sur le statut des destinataires du BAT de l’étape. Le statut général du BAT est visible sur la page [!UICONTROL Documents], à droite des indicateurs [!UICONTROL SOCD], ce qui vous permet de savoir facilement si une décision a été prise à propos du BAT.

![Une image de la liste [!UICONTROL Documents] dans un projet [!DNL &#x200B; Workfront] avec le statut général du BAT en surbrillance.](assets/manage-proofs-overall-status.png)

Le statut du BAT indique le statut général du BAT. Par exemple, si deux destinataires ont approuvé le BAT, leur statut individuel indique [!UICONTROL Approuvé]. Cependant, le troisième destinataire n&#39;a pas encore pris de décision, le statut de cette personne est donc [!UICONTROL &#x200B; En attente &#x200B;]. Par conséquent, le statut général est [!UICONTROL En attente].

Si des statuts personnalisés ont été configurés pour votre organisation, ce sont ceux qui seront utilisés. Dans le cas contraire, les options de statut standard sont les suivantes :

* [!UICONTROL En attente]
* [!UICONTROL Approuvé]
* [!UICONTROL Approuvé avec des modifications]
* [!UICONTROL Modifications requises]
* [!UICONTROL Non pertinent]

Ouvrez la fenêtre du workflow de relecture pour voir le statut d&#39;un BAT pour les destinataires auxquels ont été affectés les rôles de [!UICONTROL Réviseur et approbateur] ou [!UICONTROL Approbateur] du BAT.

## Rapports dans [!DNL Workfront]

Vous pouvez également exploiter les fonctionnalités de reporting de [!DNL Workfront's] pour suivre les BAT tout au long du processus de révision et d’approbation.

Un rapport d’approbation de BAT vous aide à suivre les approbations en suspens afin de vous assurer que les délais sont respectés.

![Une image d’un rapport d’approbation de BAT dans [!DNL &#x200B; Workfront].](assets/proof-approval-report.png)

Un rapport de version de document vous permet de gérer et de suivre les versions de BAT.

![Une image d’un rapport de version de document dans [!DNL &#x200B; Workfront].](assets/document-version-report.png)

Nous vous recommandons de travailler avec votre consultant ou consultante [!DNL Workfront] pour créer des rapports qui répondent aux besoins de votre organisation. Certains de ces rapports requièrent une certaine connaissance des rapports en mode texte de [!DNL Workfront's].

## À vous

Adressez-vous à votre équipe ou à l’administrateur ou administratrice système de relecture pour savoir quel type de compte rendu des performances vous utiliserez dans Workfront pour assurer le bon fonctionnement des workflows de relecture.

<!--
### Learn more
* Learn to create reports in [!DNL Workfront] with the Basic Report Creation course.
* View progress and status of a proof
* View activity on a proof within [!DNL Workfront]
-->
