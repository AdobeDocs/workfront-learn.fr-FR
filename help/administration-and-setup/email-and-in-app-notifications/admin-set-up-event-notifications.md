---
title: Configuration des notifications d’événement
description: Découvrez comment contrôler les notifications électroniques et in-app que reçoivent les utilisateurs en gérant les notifications d’événement.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Intermediate
thumbnail: 10093.jpeg
jira: KT-10093
exl-id: 6bd3a777-0ed8-4383-ad8e-f1238e334e78
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '621'
ht-degree: 4%

---

<!---
this has the same content as the system administrator notification setup and mangement section of the email and inapp notificiations learning path
--->

<!---
add URL link in the note at the top of the LP
--->

# Configuration des notifications d’événement

>[!NOTE]
>
>En raison d’un déploiement par étapes, la fonctionnalité qui permet aux administrateurs système et de groupe de gérer les notifications d’événement n’est temporairement pas disponible pour certains [!DNL Workfront] clients. Veuillez suivre cet article pour connaître les mises à jour relatives à cette version : Déverrouillez la configuration des notifications d’événement pour les groupes.

Les administrateurs système déterminent quelles notifications doivent être envoyées aux utilisateurs [!DNL Workfront].

![[!UICONTROL Notifications par e-mail] dans la fenêtre [!UICONTROL Configuration] area](assets/admin-fund-notifications-1.png)

Le [!UICONTROL Notifications d’événement] est regroupée par type. Pour chaque notification d’événement répertoriée, cinq informations s’affichent :

* **[!UICONTROL Principal] —** Le [!UICONTROL Principal] vous permet d’activer ou de désactiver une notification à l’échelle du système.
* **[!UICONTROL Nom] —** Il s’agit du nom de la notification dans la variable [!DNL Workfront].
* **[!UICONTROL Description] —** La description fournit une brève explication de l’action qui a eu lieu pour déclencher une notification ou qui doit être effectuée en réponse à la réception de la notification.
* **[!UICONTROL Objet du message électronique] —** Ce qui s’affiche pour l’utilisateur dans la ligne d’objet lorsque le courrier électronique est envoyé aux utilisateurs.
* **[!UICONTROL Accès au groupe] —** Déverrouillez les notifications afin qu’elles puissent être gérées par les administrateurs de groupe.

## Activation des notifications

Pour gérer les notifications au niveau du système global, assurez-vous que la barre de recherche indique [!UICONTROL Notifications d’événement système].

Activez une notification spécifique pour la rendre disponible pour tous les utilisateurs en cliquant sur le bouton de basculement afin que le bleu s’affiche. Si le bleu est masqué, la notification est désactivée.

![[!UICONTROL Principal] colonne sur [!UICONTROL Notifications par e-mail] page](assets/admin-fund-notifications-2.png)

Une fois qu’une notification d’événement est activée, les messages sont envoyés instantanément lorsque l’événement se produit.

## Autoriser le contrôle administrateur de groupe

Les administrateurs de groupe peuvent recevoir l’autorisation, de la part des administrateurs système, de personnaliser davantage la liste de notifications en fonction du fonctionnement de leurs groupes et sous-groupes et de leurs workflows.

![[!UICONTROL Accès au groupe] colonne sur [!UICONTROL Notifications par e-mail] page](assets/ganotifications_01.png)

Pour permettre aux administrateurs de groupe de gérer les notifications de leurs groupes et sous-groupes, les notifications au niveau du système doivent être déverrouillées.

* Accédez à l’onglet Notification des événements de la page Notifications par courrier électronique .

* Assurez-vous que la barre de recherche indique Notifications d’événement système.

* Déverrouillez une seule notification pour tous les administrateurs de groupe en cliquant sur la bascule dans la colonne Accès au groupe pour que le bleu s’affiche.

* Déverrouillez plusieurs notifications à la fois en cochant la case à gauche de chaque notification et en cliquant sur l’icône de déverrouillage dans la barre d’outils située au-dessus de la liste.

![[!UICONTROL Accès au groupe] colonne sur [!UICONTROL Notifications par e-mail] page](assets/ganotifications_02.png)

Verrouillez une notification déverrouillée en cliquant sur la bascule afin que le gris apparaisse. Verrouillez plusieurs notifications en même temps en cochant les cases et en cliquant sur l’icône de déverrouillage dans la barre d’outils.

![[!UICONTROL Accès au groupe] colonne sur [!UICONTROL Notifications par e-mail] page](assets/ganotifications_03.png)

Les notifications déverrouillées s’affichent pour que les administrateurs de groupe de niveau supérieur déterminent si cette notification est nécessaire pour leurs groupes et sous-groupes. Les sous-groupes héritent des configurations de notification de leur groupe parent supérieur. ﻿


## Gestion des notifications de groupe

Une fois que l’administrateur système a déverrouillé les options de notification, les administrateurs de groupe peuvent gérer les notifications d’un groupe à partir de la page Groupe individuelle, en cliquant sur Notifications d’événement dans le menu du panneau de gauche. Vous pouvez ensuite activer ou désactiver les options de notification.

![[!UICONTROL Accès au groupe] colonne sur [!UICONTROL Notifications par e-mail] page](assets/managegroupnotifications_01.png)

Si nécessaire, les administrateurs système peuvent gérer les notifications d’un groupe à partir de la page Notifications en saisissant le nom du groupe dans la barre de recherche située en haut de la fenêtre.

![[!UICONTROL Accès au groupe] colonne sur [!UICONTROL Notifications par e-mail] page](assets/managegroupnotifications_02.png)

## Conseils pratiques

Certaines notifications [!DNL Workfront] recommande de mettre à la disposition de vos utilisateurs.

Pour la plupart des utilisateurs :

* [!UICONTROL Lorsqu&#39;une tâche est terminée, envoyer un e-mail aux cessionnaires principaux de toute les tâches dépendantes]
* [!UICONTROL Quelqu&#39;un m&#39;a inclus dans une mise à jour dirigée.]
* [!UICONTROL Quelqu’un commente ma tâche]
* [!UICONTROL La date d’échéance change pour une tâche à laquelle je suis affecté.]


Spécifiquement pour les chefs de projet :

* [!UICONTROL Un projet sur lequel je travaille devient principal]
* [!UICONTROL Quand un projet passe d&#39;un statut de progression positive (Dans les délais) à un statut de progression négative (En retard), envoyer un e-mail au propriétaire du projet]
* [!UICONTROL Envoyer un e-mail au propriétaire du projet lorsqu&#39;un événement est ajouté.]
* [!UICONTROL La tâche Milestone s’achève sur un projet dont je suis propriétaire]

<!---
learn more URLs
--->
