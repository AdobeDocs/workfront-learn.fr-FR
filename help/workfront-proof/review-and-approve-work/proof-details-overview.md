---
title: Comprendre les détails du BAT
description: Découvrez plus en détail les spécificités d’un BAT dans  [!DNL  Workfront]  par le biais du panneau de résumé et de la page [!UICONTROL Détails du document].
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User, Admin
level: Beginner
thumbnail: understand-proof-details.png
jira: KT-10110
exl-id: 196f9318-eced-4825-b0fd-8592b6cb3403
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: ht
source-wordcount: '1029'
ht-degree: 100%

---

# Comprendre les détails du BAT

## Afficher les détails du BAT

En tant que gestionnaire ou propriétaire de BAT, vous pouvez approfondir les détails d’un BAT grâce au panneau de résumé et à la page [!UICONTROL Détails du document]. Commencez par trouver votre BAT dans la section [!UICONTROL Documents] d’un projet, d’une tâche ou d’un problème.

### Panneau Résumé

Le panneau de résumé fournit une vue d’ensemble de haut niveau des détails de base d’un BAT. Utilisez l’icône pour développer le panneau lorsque vous en avez besoin et le réduire lorsqu’il n’est plus utile. Vous pouvez même pointer sur la miniature du BAT pour l’ouvrir ou le télécharger.

![Une image de la section [!UICONTROL Documents] d’un projet avec un BAT sélectionné et le panneau de résumé développé. L’icône du panneau de résumé et le panneau de résumé sont mis en surbrillance.](assets/document-summary.png)

Note : la section [!UICONTROL Approbations] du panneau de résumé est destinée aux approbations de **documents** et **n’est pas** liée au processus de révision et d’approbation des BAT que vous avez vu dans ce cours. Les deux processus sont séparés dans [!DNL Workfront].

### [!UICONTROL Détails du document]

Si vous avez besoin d’informations supplémentaires sur le BAT, le lien [!UICONTROL Détails du document] vous conduit à la « page » du BAT dans [!DNL Workfront].

![Une image de la page du BAT dans [!DNL  Workfront].](assets/document-details.png)

Il faut noter que la possibilité d’afficher les informations relatives au processus de relecture dépend de vos autorisations de relecture dans [!DNL Workfront].

La page du BAT vous permet d’accéder à ces sections à partir du menu du panneau de gauche :

* **Mises à jour :** les commentaires apportés dans la visionneuse de BAT apparaissent ici, avec l’étiquette « commentaire de BAT ». Vous pouvez également faire des commentaires sur le fichier, tout comme dans une tâche ou un projet (ces commentaires n’apparaissent pas dans la visionneuse de BAT).
* **Approbations :** cette section concerne les approbations de documents et non les approbations de relecture. Les deux types d’approbations sont des processus distincts dans [!DNL Workfront] et ne sont pas liés. Si vous utilisez des workflows de BAT pour vos révisions et vos approbations, vous n’utiliserez pas cette section.
* **Toutes les versions :** suivez et gérez l’historique des versions du BAT. Il vous sera peut-être plus facile d’accéder à ces informations dans le panneau de résumé de la liste [!UICONTROL Documents].
* **Formulaires personnalisés :** les formulaires personnalisés sont utilisés sur les BAT pour recueillir des informations spécifiques à l’organisation. Ces informations peuvent être transmises avec le fichier à des systèmes de stockage de documents intégrés, tels que [!DNL Workfront] DAM ou [!DNL Adobe’s] AEM. Les formulaires personnalisés sont mis en place par l’équipe d’administration du système ou du groupe [!DNL Workfront]. Contactez votre équipe ou vos administrateurs ou administratrices pour savoir si vous utiliserez des formulaires personnalisés sur des BAT.
* **Workflow de relecture :** pour gérer ou modifier le workflow affecté au BAT. Vous pouvez également ouvrir cette fenêtre en utilisant le lien [!UICONTROL Workflow de relecture] sur le BAT dans la liste [!UICONTROL Documents]. Découvrez comment apporter des modifications au workflow avec la vidéo Modifier un workflow de BAT.

Regardons de plus près deux des sections : [!UICONTROL Paramètres de la visionneuse de BAT] et [!UICONTROL Activité de relecture].

### [!UICONTROL Paramètres de la visionneuse de relecture]

Ces paramètres vous aident à contrôler l’accès au BAT lui-même.

![Une image des [!UICONTROL Paramètres de la visionneuse de BAT] tirée de la page du BAT avec l’option [!UICONTROL Paramètres de la visionneuse de BAT] en surbrillance dans le menu du panneau de gauche.](assets/proofing-settings-on-details-page.png)

* **[!UICONTROL Exiger une connexion. Ce BAT ne peut pas être partagé avec des personnes invitées] -** Le BAT ne peut être partagé qu’avec les personnes disposant d’une licence de relecture [!DNL Workfront].
* **[!UICONTROL Exiger que les décisions soient signées électroniquement] -** Lors du partage d’un BAT, le ou la destinataire doit disposer des autorisations de relecture dans [!DNL Workfront] et « signer électroniquement » le BAT en saisissant son mot de passe de relecture lorsqu’il ou elle prend une décision à propos du BAT. (Note : le mot de passe de relecture est différent de votre mot de passe [!DNL Workfront]. Le mot de passe de relecture n’est pas facilement accessible, de sorte que la plupart des destinataires ne le connaîtront pas). [!DNL Workfront] recommande de discuter avec votre consultant ou consultante [!DNL Workfront] avant d’utiliser cette fonctionnalité.
* **[!UICONTROL Verrouiller le BAT lorsque toutes les décisions requises ont été prises] -** Ceci verrouille le BAT contre tout autre commentaire, réponse, décision, etc., une fois que toutes les décisions relatives au BAT ont été prises. Cela verrouille toute la version du BAT, et pas seulement une étape spécifique du workflow de relecture.
* **[!UICONTROL Autoriser le téléchargement du fichier d’origine] -** Les destinataires du BAT peuvent télécharger le fichier source d’origine du BAT depuis la visionneuse de BAT (l’option se trouve dans le menu du panneau de droite).
* **[!UICONTROL Autoriser le partage du BAT via une URL publique ou un code incorporé] -** Les destinataires du BAT peuvent partager avec n’importe qui un lien accessible au public.
* **[!UICONTROL Autoriser l’abonnement à un BAT via une URL publique ou un code incorporé] -** Toute personne qui reçoit l’URL publique peut s’ajouter au BAT avec son adresse e-mail et son nom (si elle n’est pas utilisatrice du BAT) ou son adresse e-mail et son mot de passe de relecture (si elle est utilisatrice du BAT). (Note : le mot de passe de relecture n’est pas le même qu’un mot de passe [!DNL Workfront].)

Ces mêmes paramètres peuvent être définis lorsque le BAT est chargé dans la section [!UICONTROL Paramètres de BAT], au bas de la fenêtre de chargement.

![Une image de la section [!UICONTROL Paramètres de BAT] au bas de la fenêtre de chargement.](assets/proof-settings-on-upload-page.png)

### [!UICONTROL Activité de relecture]

Cette page effectue le suivi de toutes les activités qui se sont produites sur le BAT, ainsi que des e-mails envoyés concernant ce BAT.

![Image de la section [!UICONTROL Activité de relecture] de la page du BAT avec l’option [!UICONTROL Activité de relecture] en surbrillance dans le menu du panneau gauche.](assets/proofing-activity-in-details.png)

La section [!UICONTROL Activité] indique l’heure à laquelle les commentaires et les décisions ont été pris, ainsi que l’identité de leur auteur ou autrice. Cela permet également de savoir quand les étapes du workflow de relecture ont commencé, quand un ou une destinataire a ouvert un BAT pour la première fois, et d’autres informations qu’un ou une gestionnaire ou un ou une propriétaire de BAT voudra connaître. Ces détails peuvent s’avérer utiles lorsque vous essayez de comprendre des choses comme, par exemple, pourquoi une étape de workflow de relecture n’a jamais été lancée.

La section [!UICONTROL Messages] indique l’heure à laquelle les alertes et les e-mails ont été envoyés aux destinataires, le nom de l’expéditeur ou de l’expéditrice et le contenu du message. Cela peut s’avérer utile en cas de dépannage si quelqu’un dit ne pas avoir reçu d’e-mail au sujet d’un BAT. Vous pouvez vérifier si et quand un e-mail a été envoyé.

[!DNL Workfront] recommande au ou à la gestionnaire et au ou à la propriétaire du BAT de se familiariser avec les informations contenues dans ces deux sections. Lorsque vous combinez ces informations à la compréhension de la barre de progression de [!UICONTROL SOCD], vous pouvez réellement comprendre et gérer vos BAT, quel que soit leur emplacement dans le workflow de relecture.

Une fois que vous avez terminé de travailler dans la section [!UICONTROL Détails du document], utilisez le cheminement de navigation pour revenir à la section [!UICONTROL Documents] du projet, de la tâche ou du problème auquel le BAT est joint.

![Image du cheminement de navigation dans l’en-tête.](assets/proof-breadcrumb.png)

<!--
#### Learn more
* [!UICONTROL Document details] overview
* Add a custom form to a document
* Request document approvals
* Summary for documents overview
* View activity on a proof within [!DNL Workfront]
-->
