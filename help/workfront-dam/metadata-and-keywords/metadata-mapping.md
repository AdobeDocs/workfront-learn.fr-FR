---
title: Configuration du mappage des métadonnées pour [!UICONTROL Gestion des actifs numériques Workfront]
description: Découvrez comment configurer le mappage des métadonnées pour [!UICONTROL Gestion des actifs numériques Workfront].
activity: use
team: Technical Marketing
feature: Digital Content and Documents
type: Tutorial
role: Admin
level: Intermediate
jira: KT-10088
exl-id: 3869db93-9fbc-4689-b838-0f4400a436c3
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '276'
ht-degree: 0%

---

# Mappage des métadonnées

[!DNL Workfront]Les informations relatives à une ressource peuvent être transférées à partir de [!DNL Workfront] into [!UICONTROL Gestion des actifs numériques Workfront] avec la ressource. L’option de mappage des métadonnées dans la variable [!DNL Workfront] [!UICONTROL Configuration] permet ce transfert d’informations.

Contactez votre [!DNL Workfront] consultant pour obtenir des recommandations sur les bonnes pratiques relatives à la configuration du mappage des métadonnées.

Vous devez être un [!DNL Workfront] administrateur et un [!UICONTROL Gestion des actifs numériques Workfront] administrateur pour configurer le mappage des métadonnées. Avant de pouvoir commencer, vous devez connecter votre [!DNL Workfront] et [!UICONTROL Gestion des actifs numériques Workfront] comptes.

## Connexion de comptes

1. Connectez-vous à [!DNL Workfront].
1. Ouvrez un projet, une tâche ou un problème, puis cliquez sur le bouton **[!UICONTROL Documents]** .
1. Cliquez sur le bouton **[!UICONTROL Ajouter]** et sélectionnez **[!UICONTROL À partir de Workfront DAM]** dans le menu déroulant.
1. Saisissez votre nom d’utilisateur et votre mot de passe dans le champ [!UICONTROL Gestion des actifs numériques Workfront] la zone d’autorisation qui s’affiche.
1. Cliquez ensuite sur **[!UICONTROL Oui]** donner [!DNL Workfront] accès au [!UICONTROL DAM] compte .
1. Si nécessaire, actualisez la page pour mettre à jour l’accès à [!UICONTROL Gestion des actifs numériques Workfront].

Une fois cette connexion établie, vous pouvez maintenant commencer à mapper les métadonnées entre les deux systèmes. Assurez-vous que vous avez déjà créé les champs de métadonnées nécessaires dans [!UICONTROL Gestion des actifs numériques Workfront] avant de commencer le mappage.

## Configuration du mapping

1. Connectez-vous à [!DNL Workfront].
1. Sélectionner **[!UICONTROL Configuration]** de la [!UICONTROL Menu Principal].
1. Développez l’objet **[!UICONTROL Documents]** dans le menu du panneau de gauche.
1. Cliquez ensuite sur **[!UICONTROL Mappage des métadonnées]**.
1. Dans le champ Workfront , saisissez la source du champ de la variable [!DNL Workfront] champ à mapper.
1. Sélectionnez ensuite la cible ou la cible correspondante **[!UICONTROL Gestion des actifs numériques Workfront]** champ de métadonnées.
1. Cliquez sur le bouton **[!UICONTROL Ajouter un mappage]** bouton .
1. Vous verrez le [!UICONTROL Source du champ Workfront] et [!UICONTROL Champ cible de la gestion des actifs numériques Workfront] dans le graphique au bas de la fenêtre.
1. Répétez l’opération pour tous les champs de métadonnées souhaités.

![Capture d’écran de la [!UICONTROL Mappage des métadonnées] écran [!DNL Workfront]](assets/01-metadata-mapping.png)
