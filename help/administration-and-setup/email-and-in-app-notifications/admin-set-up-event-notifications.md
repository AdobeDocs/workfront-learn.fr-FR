---
title: Configurer les notifications d’événement
description: Découvrez comment contrôler les notifications par e-mail et in-app que reçoivent les utilisateurs et utilisatrices en gérant les notifications d’événement.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Intermediate
thumbnail: 10093.jpeg
jira: KT-10093
exl-id: 6bd3a777-0ed8-4383-ad8e-f1238e334e78
source-git-commit: 4568e4e47b719e2dee35357d42674613112a9c43
workflow-type: ht
source-wordcount: '622'
ht-degree: 100%

---

<!--
this has the same content as the system administrator notification setup and mangement section of the email and inapp notificiations learning path
-->

<!--
add URL link in the note at the top of the LP
-->

# Configurer les notifications d’événement

>[!NOTE]
>
>En raison d’un déploiement progressif, la fonctionnalité qui permet aux administrateurs et administratrices de systèmes et de groupes de gérer les notifications d’événements n’est temporairement pas disponible pour certains clientes et clients de [!DNL Workfront]. Consultez cet article pour connaître les mises à jour relatives à la version : déverrouillez la configuration des notifications d’événement pour les groupes.

Les administrateurs et administratrices système déterminent les notifications qui doivent être envoyées aux utilisateurs et utilisatrices [!DNL Workfront].

Fenêtre ![[!UICONTROL Notifications par e-mail] dans la zone [!UICONTROL Configuration]](assets/admin-fund-notifications-1.png)

La liste [!UICONTROL Notifications d’événements] est regroupée par type. Pour chaque notification d’événement de la liste, cinq informations s’affichent :

* **[!UICONTROL Actif] :** la colonne [!UICONTROL Actif] vous permet d’activer ou de désactiver une notification à l’échelle du système.
* **[!UICONTROL Nom] :** nom de la notification dans [!DNL Workfront].
* **[!UICONTROL Description] :** la description fournit une brève explication de l’action qui a eu lieu pour déclencher une notification ou qui doit être effectuée en réponse à la réception de la notification.
* **[!UICONTROL Objet de l’e-mail] :** ce qui s’affiche pour l’utilisateur ou l’utilisatrice dans la ligne d’objet lorsque l’e-mail est envoyé aux utilisateurs et utilisatrices.
* **[!UICONTROL Accès au groupe] :** déverrouillez les notifications afin qu’elles puissent être gérées par les administrateurs et administratrices de groupe.

## Activer les notifications

Pour gérer les notifications au niveau du système global, assurez-vous que la barre de recherche indique : [!UICONTROL Notifications d’événement système].

Activez une notification spécifique pour la rendre accessible à tous les utilisateurs et utilisatrices en cliquant sur le bouton (bascule) de manière à ce que le bleu apparaisse. Si le bleu est masqué, la notification est désactivée.

Colonne ![[!UICONTROL Actif] sur la page [!UICONTROL Notifications par e-mail]](assets/admin-fund-notifications-2.png)

Une fois qu’une notification d’événement est activée, les messages sont envoyés instantanément lorsque l’événement se produit.

## Autoriser le contrôle administrateur de groupe

Les administrateurs et administratrices système peuvent octroyer aux administrateurs et administratrices de groupe l’autorisation de personnaliser davantage la liste de notifications en fonction du fonctionnement de leurs groupes et sous-groupes ainsi que de leurs workflows.

Colonne ![[!UICONTROL Accès au groupe] sur la page [!UICONTROL Notifications par e-mail]](assets/ganotifications_01.png)

Pour permettre aux administrateurs et administratrices de groupe de gérer les notifications de leurs groupes et sous-groupes, les notifications au niveau du système doivent être déverrouillées.

* Accédez à l’onglet Notification des événements de la page Notifications par e-mail.

* Assurez-vous que la barre de recherche indique Notifications d’événement système.

* Déverrouillez une seule notification pour tous les administrateurs et administratrices de groupe en cliquant sur le bouton (bascule) dans la colonne Accès au groupe pour que le bleu s’affiche.

* Déverrouillez plusieurs notifications à la fois en cochant la case à gauche de chaque notification et en cliquant sur l’icône de déverrouillage dans la barre d’outils située au-dessus de la liste.

Colonne ![[!UICONTROL Accès au groupe] sur la page [!UICONTROL Notifications par e-mail]](assets/ganotifications_02.png)

Verrouillez une notification déverrouillée en cliquant sur le bouton (bascule) pour que le gris s’affiche. Verrouillez plusieurs notifications en même temps en cochant les cases et en cliquant sur l’icône de déverrouillage dans la barre d’outils.

Colonne ![[!UICONTROL Accès au groupe] sur la page [!UICONTROL Notifications par e-mail]](assets/ganotifications_03.png)

Les notifications déverrouillées s’affichent pour que les administrateurs et administratrices de groupe de niveau supérieur puissent déterminer si ces notifications sont nécessaires pour leurs groupes et sous-groupes. Les sous-groupes héritent des configurations de notification de leur groupe parent de niveau supérieur. ﻿


## Gérer les notifications de groupe

Une fois que l’administrateur ou administratrice système a déverrouillé les options de notification, les administrateurs et administratrices de groupe peuvent gérer les notifications d’un groupe à partir de la page du groupe en question, en cliquant sur Notifications d’événements dans le menu du panneau de gauche. Vous pouvez ensuite activer ou désactiver les options de notification.

Colonne ![[!UICONTROL Accès au groupe] sur la page [!UICONTROL Notifications par e-mail]](assets/managegroupnotifications_01.png)

Si nécessaire, les administrateurs et administratrices système peuvent gérer les notifications d’un groupe à partir de la page Notifications en saisissant le nom du groupe dans la barre de recherche située en haut de la fenêtre.

Colonne ![[!UICONTROL Accès au groupe] sur la page [!UICONTROL Notifications par e-mail]](assets/managegroupnotifications_02.png)

## Conseils pro

[!DNL Workfront] recommande de mettre certaines notifications à la disposition de vos utilisateurs et utilisatrices.

Pour la plupart des utilisateurs et utilisatrices :

* [!UICONTROL Lorsqu&#39;une tâche est terminée, envoyer un e-mail aux cessionnaires principaux de toute les tâches dépendantes]
* [!UICONTROL Quelqu&#39;un m&#39;a inclus dans une mise à jour dirigée.]
* [!UICONTROL Lorsque quelqu’un commente un élément de mon travail]
* [!UICONTROL Lors de la modification de la date d’échéance d’une tâche qui m’est affectée]


Pour les chefs de projet :

* [!UICONTROL Lorsqu’un projet sur lequel je travail devient actif]
* [!UICONTROL Quand un projet passe d&#39;un statut de progression positive (Dans les délais) à un statut de progression négative (En retard), envoyer un e-mail au propriétaire du projet]
* [!UICONTROL Envoyer un e-mail au propriétaire du projet lorsqu&#39;un événement est ajouté.]
* [!UICONTROL Une tâche jalonnée est terminée dans un projet dont je suis propriétaire]

<!--
learn more URLs
-->
