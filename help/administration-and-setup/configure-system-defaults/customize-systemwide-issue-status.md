---
title: Personnaliser les statuts des problèmes à l’échelle du système
description: Découvrez comment modifier les noms des statuts des problèmes, contrôler les types de problèmes pour lesquels un statut est utilisé et verrouiller/déverrouiller les statuts pour la personnalisation au niveau du groupe.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Intermediate, Experienced
jira: KT-10030
exl-id: c8f5677f-8d9d-4d1a-a1e3-d1a438878213
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: ht
source-wordcount: '386'
ht-degree: 100%

---

# Personnaliser les statuts à l’échelle du système

[!DNL Workfront] fournit différents statuts par défaut pour s’adapter aux workflows de gestion des problèmes de votre organisation. Ces statuts peuvent être renommés pour correspondre à la terminologie de votre organisation. Les statuts peuvent être attribués à des types de problèmes spécifiques.

Des statuts supplémentaires peuvent être créés, si nécessaire. Seuls les administrateurs et les administratrices système peuvent créer des statuts pour l’ensemble du système. En outre, les administrateurs et les administratrices système contrôlent les statuts qui peuvent être modifiés par les administrateurs et les administratrices de groupe.

Onglet ![[!UICONTROL Problèmes] sur la page [!UICONTROL Statuts] dans [!UICONTROL Configuration]](assets/admin-fund-all-issue-statuses.png)

## Modifier les statuts existants

[!DNL Workfront] recommande un nombre minimum de statuts. Cela permet d’avoir une liste de choix plus courte afin de facilier la sélection du statut pour les utilisateurs et les utilisatrices.

Vous pouvez modifier un statut existant pour changer le nom, les types de problèmes auxquels il est affecté, la couleur associée, etc.

![Liste de statuts des problèmes avec l’option [!UICONTROL Modifier] mise en surbrillance](assets/admin-fund-edit-issue-status.png)

1. Cliquez sur **[!UICONTROL Configuration]** dans le **[!UICONTROL menu principal]**.
1. Développez la section **[!UICONTROL Préférences du projet]** dans le panneau de menu gauche.
1. Sélectionnez **[!UICONTROL Statuts]**.
1. Sélectionnez l’onglet **[!UICONTROL Problèmes]** et assurez-vous que la section [!UICONTROL Statuts du système] s’affiche dans le coin supérieur droit.
1. Sélectionnez **[!UICONTROL Liste principale]** pour voir les statuts de tous les types de problèmes. Cette section vous permet de créer ou modifier un statut de problème.
1. Pointez sur le côté droit du statut que vous souhaitez renommer, puis cliquez sur **[!UICONTROL Modifier]**.
1. Renommez le statut ou modifiez l’une des autres informations, selon vos besoins.
1. Verrouillez le statut si ces paramètres doivent s’appliquer à tous les utilisateurs et toutes les utilisatrices de votre instance [!DNL Workfront].
1. Déverrouillez le statut pour permettre aux administrateurs et aux administratrices de groupe de modifier le statut uniquement pour leurs groupes.
1. Cochez les cases correspondant au type de problème auquel le statut doit s’appliquer.
1. Cliquer sur **[!UICONTROL Enregistrer]**.

![Fenêtre de création d’un statut](assets/admin-fund-edit-issue-status-2.png)

### Affectations de statuts

Tous les statuts ne peuvent pas être affectés à tous les types de problèmes. La page [!UICONTROL Statuts] comporte des colonnes indiquant le type de problème pour lequel chaque statut peut être utilisé.

![Ordre de modification surligné sur l’onglet Problèmes de la page Statuts](assets/admin-fund-issue-type-statuses.png)


Pour afficher uniquement les statuts affectés à un type de problème spécifique, cliquez simplement sur le nom du type de problème en haut de la fenêtre.

Onglet ![[!UICONTROL Problème] de la page [!UICONTROL Statuts] avec colonnes surlignées](assets/admin-fund-statuses-issue-type.png)

Ici, vous pouvez faire glisser les problèmes et les déposer dans l’ordre dans lequel ils doivent apparaître dans le menu déroulant [!UICONTROL Statuts].

Pour modifier les statuts, vous devez revenir à la [!UICONTROL Liste principale].
