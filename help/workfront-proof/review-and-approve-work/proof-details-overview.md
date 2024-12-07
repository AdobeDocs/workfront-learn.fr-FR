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
source-git-commit: cb72c429f0ef4cd9945282876aa49189dab1bd96
workflow-type: tm+mt
source-wordcount: '1038'
ht-degree: 57%

---

# Comprendre les détails du BAT

## Afficher les détails du BAT

En tant que gestionnaire ou propriétaire de BAT, vous pouvez approfondir les détails d’un BAT grâce au panneau de résumé et à la page [!UICONTROL Détails du document]. Commencez par trouver votre BAT dans la section [!UICONTROL Documents] d’un projet, d’une tâche ou d’un problème.

### Panneau Résumé

Sélectionnez un BAT dans la liste des documents, puis cliquez sur l&#39;icône Résumé en haut à droite de l&#39;écran.

![Une image de la section [!UICONTROL Documents] d&#39;un projet avec un BAT sélectionné.](assets/document-summary-1.png)

Cliquez ensuite sur Aperçu pour développer la section d’aperçu.

![Une image de la section [!UICONTROL Documents] d’un projet avec un BAT sélectionné et le panneau de résumé développé. L’icône du panneau de résumé et le panneau de résumé sont mis en surbrillance.](assets/document-summary-2.png)

Faites ensuite défiler l’écran jusqu’à la section Vérification . Ici, vous pouvez voir le propriétaire du BAT, l&#39;état d&#39;avancement, le nombre de commentaires, l&#39;état et l&#39;échéance.

![Une image de la section [!UICONTROL Documents] d’un projet avec un BAT sélectionné et le panneau de résumé développé. L’icône du panneau de résumé et le panneau de résumé sont mis en surbrillance.](assets/document-summary-3.png)

Remarque : La section [!UICONTROL Approbations] du panneau de résumé concerne les **approbations de document** et **n’est pas** liée au processus de révision et d’approbation des BAT. Les deux processus sont séparés dans [!DNL Workfront].

### [!UICONTROL Détails du document]

Pour plus d’informations sur le BAT, cliquez sur [!UICONTROL Document Details].

![Une image de la section [!UICONTROL Documents] d&#39;un projet avec un BAT sélectionné et [!UICONTROL Document Details] mise en surbrillance.](assets/document-summary-4.png)

Vous accédez alors à la page [!UICONTROL Détails du document] et à diverses options supplémentaires dans le panneau de gauche.

![Une image de la page du BAT dans [!DNL  Workfront].](assets/document-details.png)

Il est important de noter que la possibilité d’afficher les informations relatives au processus de vérification dépend de vos autorisations de vérification dans [!DNL Workfront].

La page du BAT vous permet d’accéder aux sections suivantes à partir du menu du panneau de gauche :

* **Mises à jour —** Les commentaires effectués dans la visionneuse de BAT s’affichent ici, avec une balise &quot;commentaire de BAT&quot;. Vous pouvez également faire des commentaires sur le fichier, tout comme dans une tâche ou un projet (ces commentaires n’apparaissent pas dans la visionneuse de BAT).
* **Approbations :** cette section concerne les approbations de documents et non les approbations de relecture. Les deux types d’approbations sont des processus distincts dans [!DNL Workfront] et ne sont pas liés. Si vous utilisez des workflows de BAT pour vos révisions et approbations, vous n’utiliserez pas cette section.
* **Toutes les versions :** suivez et gérez l’historique des versions du BAT. Il vous sera peut-être plus facile d’accéder à ces informations dans le panneau de résumé de la liste [!UICONTROL Documents].
* **Formulaires personnalisés :** les formulaires personnalisés sont utilisés sur les BAT pour recueillir des informations spécifiques à l’organisation. Ces informations peuvent être transmises avec le fichier aux systèmes de stockage de documents intégrés, tels que [!DNL Workfront] DAM ou Adobe Experience Manager. Les formulaires personnalisés sont mis en place par l’équipe d’administration du système ou du groupe [!DNL Workfront]. Contactez votre équipe ou vos administrateurs ou administratrices pour savoir si vous utiliserez des formulaires personnalisés sur des BAT.
* **Workflow de relecture :** pour gérer ou modifier le workflow affecté au BAT. Vous pouvez ouvrir cette fenêtre à l’aide du lien [!UICONTROL Workflow de vérification de l’identité] sur le BAT dans la liste [!UICONTROL Documents].

Regardons de plus près deux des sections : [!UICONTROL Paramètres de la visionneuse de vérification] et [!UICONTROL Activité de vérification].

### [!UICONTROL Paramètres de la visionneuse de relecture]

Ces paramètres vous aident à contrôler l’accès au BAT lui-même.

![Une image des [!UICONTROL Paramètres de la visionneuse de BAT] tirée de la page du BAT avec l’option [!UICONTROL Paramètres de la visionneuse de BAT] en surbrillance dans le menu du panneau de gauche.](assets/proofing-settings-on-details-page.png)

* **[!UICONTROL Exiger une connexion. Ce BAT ne peut pas être partagé avec des personnes invitées] -** Le BAT ne peut être partagé qu’avec les personnes disposant d’une licence de relecture [!DNL Workfront].
* **[!UICONTROL Exiger que les décisions soient signées électroniquement] —** Lors du partage d’un BAT, cela nécessite que le destinataire dispose d’autorisations de vérification dans [!DNL Workfront] et le fait &quot;signer électroniquement&quot; le BAT en saisissant son mot de passe de vérification lorsqu’il prend une décision concernant le BAT. (Note : le mot de passe de relecture est différent de votre mot de passe [!DNL Workfront]. Le mot de passe de vérification n’est pas facilement accessible. La plupart des destinataires ne connaîtront donc pas ce mot de passe.) Adobe recommande de discuter avec votre consultant [!DNL Workfront] avant d’utiliser cette fonctionnalité.
* **[!UICONTROL Verrouiller le BAT lorsque toutes les décisions requises ont été prises] -** Ceci verrouille le BAT contre tout autre commentaire, réponse, décision, etc., une fois que toutes les décisions relatives au BAT ont été prises. Cela verrouille toute la version du BAT, et pas seulement une étape spécifique du workflow de relecture.
* **[!UICONTROL Autoriser le téléchargement du fichier d’origine] —** Les destinataires du BAT peuvent télécharger le fichier source d’origine du BAT à partir de la visionneuse de vérification.
* **[!UICONTROL Autoriser le partage du BAT via une URL publique ou un code incorporé] -** Les destinataires du BAT peuvent partager avec n’importe qui un lien accessible au public.
* **[!UICONTROL Autoriser l’abonnement à un BAT via une URL publique ou un code incorporé] -** Toute personne qui reçoit l’URL publique peut s’ajouter au BAT avec son adresse e-mail et son nom (si elle n’est pas utilisatrice du BAT) ou son adresse e-mail et son mot de passe de relecture (si elle est utilisatrice du BAT). (Note : le mot de passe de relecture n’est pas le même qu’un mot de passe [!DNL Workfront].)


### [!UICONTROL Activité de relecture]

Cette page effectue le suivi de toutes les activités qui se sont produites sur le BAT, ainsi que des emails envoyés concernant ce BAT.

![Image de la section [!UICONTROL Activité de relecture] de la page du BAT avec l’option [!UICONTROL Activité de relecture] en surbrillance dans le menu du panneau gauche.](assets/proofing-activity-in-details.png)

La section **[!UICONTROL Activité]** indique l’heure à laquelle les commentaires et les décisions ont été pris, ainsi que l’identité de leur auteur ou autrice. Cela permet également de savoir quand les étapes du workflow de relecture ont commencé, quand un ou une destinataire a ouvert un BAT pour la première fois, et d’autres informations qu’un ou une gestionnaire ou un ou une propriétaire de BAT voudra connaître. Ces détails peuvent s’avérer utiles lorsque vous essayez de comprendre des choses comme, par exemple, pourquoi une étape de workflow de vérification n’a jamais été lancée.

La section **[!UICONTROL Messages]** indique l’heure à laquelle les alertes et les e-mails ont été envoyés aux destinataires, le nom de l’expéditeur ou de l’expéditrice et le contenu du message. Cela peut s’avérer utile lors de la résolution des problèmes si quelqu’un indique qu’il n’a pas reçu d’e-mail sur un BAT. Vous pouvez vérifier si et quand un e-mail a été envoyé.

Adobe recommande au responsable du BAT et au propriétaire du BAT de se familiariser avec les informations contenues dans ces deux sections. Lorsque vous combinez ces informations à la compréhension de la barre de progression de [!UICONTROL SOCD], vous pouvez réellement comprendre et gérer vos BAT, quel que soit leur emplacement dans le workflow de relecture.

Une fois que vous avez terminé de travailler dans la section [!UICONTROL Détails du document], utilisez le chemin de navigation pour revenir à la section [!UICONTROL Documents] du projet, de la tâche ou de l’émission à laquelle le BAT est joint.

![Image du cheminement de navigation dans l’en-tête.](assets/proof-breadcrumb.png)

<!--
#### Learn more
* [!UICONTROL Document details] overview
* Add a custom form to a document
* Request document approvals
* Summary for documents overview
* View activity on a proof within [!DNL Workfront]
-->
