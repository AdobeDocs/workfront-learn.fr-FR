---
title: Création d’un état de problème
description: Découvrez comment créer un état de problème pour répondre aux besoins des workflows de votre entreprise.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Intermediate, Experienced
kt: 10019
exl-id: 1689080d-1d3c-4fad-a353-64fb3b0d5851
source-git-commit: 1f7a4da813805691fc0e52d3ad1ea708f9e07a9a
workflow-type: tm+mt
source-wordcount: '284'
ht-degree: 0%

---

# Création d’un état de problème

[!DNL Workfront] vous recommande de modifier les statues de problème existantes dans votre système avant de commencer à créer de nouveaux statuts. Cela permet de limiter le nombre d’états qui doivent être conservés.

1. Cliquez sur **[!UICONTROL Configuration]** dans le **[!UICONTROL Menu Principal]**.
1. Développez l’objet **[!UICONTROL Préférences du projet]** dans le panneau du menu de gauche.
1. Sélectionner **[!UICONTROL Statuts]**.
1. Sélectionnez la **[!UICONTROL Problèmes]** .
1. Assurez-vous que le champ dans le coin supérieur droit est défini sur [!UICONTROL États du système]. Cela garantit que le nouvel état est disponible globalement dans vos [!DNL Workfront] instance.
1. Sélectionner **[!UICONTROL Liste des Principal ]**pour afficher tous les statuts des problèmes. C’est là que vous créez ou modifiez un état.
1. Cliquez sur **[!UICONTROL Ajouter un nouvel état]**.
1. Renseignez les champs selon les besoins de votre organisation : nom, description, couleur, correspond à, clé, etc.
1. Cochez les cases correspondant au type de problème avec lequel cet état peut être utilisé.
1. Cliquez sur **[!UICONTROL Enregistrer]**.

![Nouvelle fenêtre d’état sur [!UICONTROL Statuts] page](assets/admin-fund-create-issue-status.png)

## Statuts des problèmes et administrateurs de groupes

Les administrateurs de groupe peuvent créer et personnaliser des états de problème pour les groupes qu’ils gèrent. Cela leur donne une certaine autonomie, leur donnant les états dont ils ont besoin pour continuer à travailler. Il élimine également la nécessité d’une longue liste d’états à l’échelle du système.

Les administrateurs de groupe peuvent modifier les états existants si l’administrateur système les a configurés pour autoriser la personnalisation.

Les administrateurs système peuvent gérer les états des groupes en sélectionnant le nom du groupe dans le coin supérieur droit de la [!UICONTROL Statuts] fenêtre.

![Menu Liste des groupes sur [!UICONTROL Statuts] page](assets/admin-fund-change-group-master-list.png)

Les administrateurs de groupe peuvent cliquer sur dans la variable [!UICONTROL Groupes] dans la section [!UICONTROL Configuration] , ouvrez le groupe en cliquant sur le nom, puis en sélectionnant [!UICONTROL Statuts] dans le menu du panneau de gauche. Veillez à sélectionner l’onglet Problèmes .

![[!UICONTROL Statuts] section [!UICONTROL Groupe] page](assets/admin-fund-group-issue-statuses.png)

<!---
For detailed information on how managing statuses can be done by group administrators, see these articles:
Create and customize group statuses
Group administrators
--->

<!---
learn more URLs
Issue statuses
Create and customize system-wide statuses
--->
