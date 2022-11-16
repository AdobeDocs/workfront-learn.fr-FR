---
title: Créer un rapport de tâche
description: 'Découvrez comment créer un rapport de tâche avec un filtre complexe et trouver les rapports que vous créez dans Workfront. Activité : créez un rapport de note avec des invites.'
activity: use
feature: Reports and Dashboards
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
thumbnail: 335154.png
kt: 8859
exl-id: 90bad2e8-9cd2-4ae7-973b-eeab9d615bef
source-git-commit: 252ba3ba44f22519a35899fcda9c6bca597a6c2c
workflow-type: tm+mt
source-wordcount: '414'
ht-degree: 5%

---

# Créer un rapport de tâche

Dans cette vidéo, vous apprendrez :

* Comment créer un rapport de tâche avec un filtre complexe
* Comment trouver les rapports que vous créez

>[!VIDEO](https://video.tv.adobe.com/v/335154/?quality=12)

## Activité : Création d’un rapport de note avec des invites

Créez un rapport Remarque que vous pouvez utiliser pour rechercher des notes utilisateur (c’est-à-dire des commentaires ou des mises à jour) ou des notes système en fonction du contenu de la note, de l’auteur, de la date d’entrée, du nom du projet ou du type d’audit. Nommez le rapport &quot;Recherche de notes&quot;.

Lorsque vous utilisez l’invite Texte de la remarque , ce rapport effectue une recherche dans les threads de mise à jour afin d’extraire rapidement les segments répondant aux critères spécifiés dans les invites. Lorsque vous exécutez le rapport, il n’est pas nécessaire de remplir toutes les invite, uniquement celles qui vous intéressent. Les champs vierges sont automatiquement ignorés.

La vue doit inclure des colonnes pour :

* Texte de la note
* Texte d&#39;audit
* Date d’entrée
* Propriétaire : Nom
* Type d&#39;audit
* Nom de la tâche
* Nom de l&#39;événement

Laissez l’onglet Filtre vide.

Groupe sur le nom du projet.

Insérez des invites pour les éléments suivants :

* Texte d&#39;audit
* Texte de la note
* Nom du propriétaire
* Date d’entrée
* Nom du projet
* Type d&#39;audit

## Réponse

1. Sélectionner **[!UICONTROL Rapports]** de la **[!UICONTROL Menu Principal]**.
1. Cliquez sur le bouton **[!UICONTROL Nouveau rapport]** et sélectionnez **[!UICONTROL Remarque]**.
1. Dans **[!UICONTROL Colonnes (affichage)]** configurez vos colonnes pour inclure :

   ![Image de l’écran de création des colonnes de rapports de notes](assets/note-report-columns.png)

   * [!UICONTROL Remarque] > [!UICONTROL Texte de la remarque]
   * [!UICONTROL Remarque] > [!UICONTROL Texte de l’audit]
   * [!UICONTROL Remarque] > [!UICONTROL Date d’entrée]
   * [!UICONTROL Propriétaire] > [!UICONTROL Nom]
   * [!UICONTROL Remarque] > [!UICONTROL Type d’audit]
   * [!UICONTROL Tâche] > [!UICONTROL Nom]
   * [!UICONTROL Problème] > [!UICONTROL Nom]

1. Sélectionnez la **[!UICONTROL Date d’entrée]** et modifiez la variable **[!UICONTROL Tri vers descendant]**.
1. Dans le **[!UICONTROL Groupements]** , définissez le rapport sur le groupe suivant : [!UICONTROL Projet] > [!UICONTROL Nom].

   ![Image de l’écran de création de groupes de rapports de notes](assets/note-report-groupings.png)

1. Laissez tomber [!UICONTROL Filtres] vide.
1. Ouvrir **[!UICONTROL Paramètres des rapports]** et nommez le rapport &quot;Recherche de notes&quot;.
1. Dans le [!UICONTROL Description] , indiquez quelque chose comme &quot;Rechercher des notes système ou utilisateur en fonction du type d’audit sélectionné et d’autres invites. Les notes système apparaissent dans la colonne Texte de l’audit et les notes utilisateur dans la colonne Texte de la remarque.&quot;

   ![Image de l’écran de création des paramètres de rapport de note](assets/note-report-report-options.png)

1. Sélectionner **[!UICONTROL Onglet Détails]** afin qu’il s’affiche au chargement du rapport.
1. Définissez le rapport pour afficher 200 éléments lorsque le rapport est inclus dans un tableau de bord.
1. Cliquez sur **[!UICONTROL Invite de rapports]** et ajoutez :

   ![Une image de l’écran pour créer les invites de rapport de notes](assets/note-report-report-prompts.png)

   * [!UICONTROL Remarque] > [!UICONTROL Texte de l’audit]
   * [!UICONTROL Remarque] > [!UICONTROL Texte de la remarque]
   * [!UICONTROL Propriétaire] > [!UICONTROL Nom]
   * [!UICONTROL Remarque] > [!UICONTROL Date d’entrée]
   * [!UICONTROL Projet] > [!UICONTROL Nom]
   * [!UICONTROL Remarque] > [!UICONTROL Type d’audit]

1. Cochez la case pour **[!UICONTROL Afficher les invites dans les tableaux de bord]**.
1. Enregistrez et fermez votre rapport.
