---
title: Création et gestion des problèmes de gravité
description: Découvrez comment configurer et gérer les ruptures de problèmes.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Intermediate, Experienced
kt: 10020
exl-id: a5a9280b-0d48-413d-92de-f6a949e6b210
source-git-commit: 5d385de5cdcee0d433304c09507ba6bb5b0a10e6
workflow-type: tm+mt
source-wordcount: '368'
ht-degree: 3%

---

# Création et gestion des statistiques sur les problèmes

## Présentation de la gravité des problèmes

Une gravité peut être utilisée pour indiquer la gravité d’un problème ou son impact sur le travail en cours.

![[!UICONTROL Gravité] dans le menu [!UICONTROL Détails du problème] window](assets/admin-fund-severity-issue-details.png)

Le [!UICONTROL Gravité] est accessible dans le champ [!UICONTROL Détails du problème]. Elle peut également être incluse dans les colonnes vues des listes et dans les rapports personnalisés.

[!DNL Workfront] comporte cinq ruptures par défaut :

* [!UICONTROL Décoratif]
* [!UICONTROL Cause de la confusion]
* [!UICONTROL Bogue qui a une solution]
* [!UICONTROL Bogue sans solution]
* [!UICONTROL Erreur fatale]

Si nécessaire, les administrateurs système peuvent renommer ces ruptures par défaut ou en créer de nouvelles.

Les gravité ne sont disponibles que pour les problèmes dans [!DNL Workfront].

## Création et gestion des statistiques sur les problèmes

En tant qu’administrateur système, vous pouvez créer de nouvelles statistiques, si nécessaire, pour terminer le workflow du problème.

![[!UICONTROL Gravités] page [!UICONTROL Configuration]](assets/admin-fund-severity-section.png)

1. Cliquez sur **[!UICONTROL Configuration]** dans le **[!UICONTROL Menu Principal]**.
1. Développez l’objet **[!UICONTROL Préférences du projet]** dans le panneau du menu de gauche.
1. Sélectionner **[!UICONTROL Gravités]**.
1. Cliquez sur **[!UICONTROL Ajout d’une nouvelle gravité]**.
1. Donnez à la gravité un nom correspondant à son utilisation prévue.
1. Le **[!UICONTROL Importance]** Le nombre correspond à la gravité du problème. Le nombre le plus élevé correspond à la gravité la plus élevée. Le [!UICONTROL Importance] number doit être unique.
1. Sélectionnez une couleur pour votre priorité. Elle est utilisée dans les rapports sous forme de graphique et à d’autres endroits dans [!DNL Workfront].
1. Désigner l’une des options de gravité comme **[!UICONTROL Gravité par défaut]**. Cette option est appliquée automatiquement à tous les nouveaux problèmes de Workfront.
1. Incluez une description de la gravité, par exemple comment elle sera utilisée.
1. Cliquez en dehors des champs à enregistrer.

![[!UICONTROL Gravités] list](assets/admin-fund-severity-new.png)

### Modification des ruptures

Si un niveau de gravité n’est plus pertinent pour vos workflows de problème, il peut être renommé, masqué ou supprimé.

Si une gravité n&#39;est plus nécessaire, [!DNL Workfront] vous recommande de masquer la gravité (cliquez sur le bouton [!UICONTROL Masquer] en regard de la zone de configuration). Cette opération supprime l’option de gravité du menu déroulant sur le problème, mais elle conserve la gravité des données historiques afin qu’elle soit toujours disponible à des fins de création de rapports.

![[!UICONTROL Masquer] mise en surbrillance sur [!UICONTROL Gravités] page [!UICONTROL Configuration]](assets/admin-fund-severity-hide.png)

[!DNL Workfront] recommande que vous . **ne pas** supprimer une gravité qui a été utilisée pour des problèmes passés. Lorsque vous supprimez une gravité, il vous demande de la remplacer. Cela peut modifier les données historiques et affecter les rapports.

![Supprimer la fenêtre de gravité](assets/admin-fund-severity-delete.png)

<!---
learn more URLs
Create and customize issue severities
Update issue severity
--->
