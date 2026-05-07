---
title: Configurer le mappage des métadonnées
description: Découvrez comment configurer le mappage des métadonnées pour [!UICONTROL Workfront DAM].
activity: use
team: Technical Marketing
feature: Digital Content and Documents
type: Tutorial
role: Admin
level: Intermediate
jira: KT-10088
exl-id: 3869db93-9fbc-4689-b838-0f4400a436c3
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
autotag-review: '2026-05-05T22:32:59.006Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 276
ht-degree: 100%

---

# Configurer le mappage des métadonnées

Les informations [!DNL Workfront] relatives à une ressource peuvent être transférées de [!DNL Workfront] à [!UICONTROL Workfront DAM] avec la ressource. L’option de mappage des métadonnées dans la zone [!UICONTROL Configuration] de [!DNL Workfront] permet ce transfert d’informations.

Parlez à votre consultant ou consultante [!DNL Workfront] pour obtenir des recommandations sur les bonnes pratiques relatives à la configuration du mappage des métadonnées.

Vous devez être administrateur ou administratrice [!DNL Workfront] et administrateur ou administratrice de [!UICONTROL Workfront DAM] pour configurer le mappage des métadonnées. Avant de pouvoir commencer, vous devez connecter vos comptes [!DNL Workfront] et [!UICONTROL Workfront DAM].

## Connecter des comptes

1. Connectez-vous à [!DNL Workfront].
1. Ouvrez un projet, une tâche ou un problème, puis cliquez sur l’onglet **[!UICONTROL Documents]**.
1. Cliquez sur le bouton **[!UICONTROL Ajouter]** et sélectionnez **[!UICONTROL À partir de Workfront DAM]** dans le menu déroulant.
1. Saisissez votre nom d’utilisateur ou d’utilisatrice et votre mot de passe dans le champ [!UICONTROL Workfront DAM] dans la zone d’autorisation qui s’affiche.
1. Cliquez ensuite sur **[!UICONTROL Oui]** afin d’accorder à [!DNL Workfront] l’accès au compte [!UICONTROL DAM].
1. Si nécessaire, actualisez la page pour mettre à jour l’accès à [!UICONTROL Workfront DAM].

Une fois cette connexion établie, vous pouvez commencer à mapper les métadonnées entre les deux systèmes. Assurez-vous que vous avez déjà créé les champs de métadonnées nécessaires dans [!UICONTROL Workfront DAM] avant de commencer le mappage.

## Configurer le mapping

1. Connectez-vous à [!DNL Workfront].
1. Sélectionnez **[!UICONTROL Configuration]** dans le [!UICONTROL Menu principal].
1. Développez la section **[!UICONTROL Documents]** dans le menu du panneau de gauche.
1. Cliquez ensuite sur le **[!UICONTROL Mappage des métadonnées]**.
1. Dans le champ Workfront, saisissez la source du champ [!DNL Workfront] à mapper.
1. Sélectionnez ensuite le champ correspondant ou le champ de métadonnées cible de **[!UICONTROL Workfront DAM]**.
1. Cliquez sur le bouton **[!UICONTROL Ajouter un mappage]**.
1. Vous verrez la [!UICONTROL Source du champ Workfront] et le [!UICONTROL Champ cible de Workfront DAM] dans le graphique au bas de la fenêtre.
1. Répétez l’opération pour tous les champs de métadonnées souhaités.

![Copie d’écran de [!UICONTROL Mappage des métadonnées] dans [!DNL Workfront]](assets/01-metadata-mapping.png)
