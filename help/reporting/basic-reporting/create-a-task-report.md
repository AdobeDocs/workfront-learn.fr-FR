---
title: Création d’un rapport de tâche
description: 'Apprenez à créer un rapport de tâches avec un filtre complexe et à trouver les rapports que vous créez dans Workfront. Activité : créer un rapport de notes avec des invites.'
activity: use
feature: Reports and Dashboards
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
thumbnail: 335154.png
jira: KT-8859
exl-id: 90bad2e8-9cd2-4ae7-973b-eeab9d615bef
doc-type: video
source-git-commit: 8cd01b3dca3a62c1d8699d7d076dccddf2010907
workflow-type: tm+mt
source-wordcount: '794'
ht-degree: 6%

---

# Création d’un rapport de tâche

Dans cette vidéo, vous apprendrez :

* Comment créer un rapport de tâche avec un filtre complexe
* Comment trouver les rapports que vous créez

>[!VIDEO](https://video.tv.adobe.com/v/335154/?quality=12&learn=on)

## Activité 1 : créer un rapport de note avec des invites

Créez un rapport Remarque que vous pouvez utiliser pour rechercher des notes utilisateur (c’est-à-dire des commentaires ou des mises à jour) ou des notes système en fonction du contenu de la note, de l’auteur, de la date d’entrée, du nom du projet ou du type d’audit. Nommez le rapport &quot;Recherche de notes&quot;.

Lorsque vous utilisez l’invite Texte de la remarque , ce rapport effectue une recherche dans les threads de mise à jour afin d’extraire rapidement les segments répondant aux critères spécifiés dans les invites. Lorsque vous exécutez le rapport, vous n’avez pas besoin de remplir toutes les invite, seulement celles qui vous intéressent. Les champs vierges sont automatiquement ignorés.

La vue doit inclure des colonnes pour :

* Texte de la note
* Texte d&#39;audit
* Date d’entrée
* Propriétaire : nom
* Type d&#39;audit
* Nom de la tâche
* Nom de l&#39;événement

Laissez l’onglet Filtre vide.

Nom du projet.

Insérez des invites pour les éléments suivants :

* Texte d&#39;audit
* Texte de la note
* Nom du propriétaire
* Date d’entrée
* Nom du projet
* Type d&#39;audit

## Réponse de l’activité 1

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

1. Sélectionnez la variable **[!UICONTROL Date d’entrée]** et modifiez la variable **[!UICONTROL Tri vers descendant]**.
1. Dans le **[!UICONTROL Groupements]** , définissez le rapport sur le groupe suivant : [!UICONTROL Projet] > [!UICONTROL Nom].

   ![Image de l’écran de création de groupes de rapports de notes](assets/note-report-groupings.png)

1. Laisser [!UICONTROL Filtres] vide.
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

## Activité 2 : création d’un rapport de retour de l’équipe d’administration

Il s’agit d’un rapport de problèmes qui affiche tous les problèmes d’une file d’attente de demandes de retour créée pour les administrateurs système. Vous pouvez voir comment créer cette file d’attente de demandes dans le [Création d’une file d’attente de demandes de commentaires de l’administrateur système](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-work/request-queues/create-a-system-admin-feedback-request-queue.html) tutoriel .

Ce rapport utilise également un formulaire personnalisé. Pour savoir comment créer un formulaire personnalisé, reportez-vous au [Création et partage d’un formulaire personnalisé](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/custom-data/custom-forms/custom-forms-creating-and-sharing-a-custom-form.html) tutoriel .

Ce formulaire personnalisé doit être créé comme suit :

Nom : commentaires sur le processus d’administration

1. Type de processus (champ déroulant)
   * niveaux d’accès
   * processus d’approbation (global uniquement)
   * notifications par e-mail
   * modèle de mise en page
   * chemin du jalon
   * modèle de projet
   * notifications de rappel
   * file d’attente de requête
1. Nom du processus (champ de texte d’une seule ligne)
1. Évaluation des processus (champ déroulant)
   * 1 - totalement inutile
   * 2 - pas très utile
   * 3 - bonne mais pourrait être meilleure
   * 4 - excellent
1. Problème ou bonne nouvelle (champ de texte de paragraphe)

Créez un rapport sur les problèmes nommé **Rapport de retour de l’équipe d’administration**.

La vue doit contenir les colonnes suivantes :

* Problème : Nom
* Contact Principal : Nom
* Problème : type de processus
* Problème : nom du processus
* Problème : qualité du processus
* Problème : problème ou bonnes nouvelles
* Problème : date d’entrée
* Problème : âge
* Problème : Affectations
* Problème : état

Groupe sur le type de processus.

Filtrez sur l’identifiant du projet de file d’attente des demandes où résident les problèmes de retour.


![Capture d’écran du rapport de retour de l’équipe d’administration](assets/create-a-system-admin-feedback-request-queue.png)



## Réponse de l’activité 2

1. Sélectionner **[!UICONTROL Rapports]** de la **[!UICONTROL Menu Principal]**.
1. Cliquez sur le bouton **[!UICONTROL Nouveau rapport]** et sélectionnez **[!UICONTROL Problème]**.
1. Dans **[!UICONTROL Colonnes (affichage)]** configurez vos colonnes pour inclure :

   ![Image de l’écran de création de colonnes de rapport de problème](assets/task-report-activity-2-1.png)

   * [!UICONTROL Problème] > [!UICONTROL Nom]
   * [!UICONTROL Contact Principal] > [!UICONTROL Nom]
      * Remarque : &quot;Propriétaire:Nom&quot; apparaît comme libellé de colonne. Vous pouvez remplacer cette valeur par &quot;Signalé par&quot; en cliquant sur Options avancées et en saisissant &quot;Signalé par&quot; dans la zone **Libellé de colonne personnalisé** champ .
   * [!UICONTROL Problème] > [!UICONTROL Type de processus]
   * [!UICONTROL Problème] > [!UICONTROL Nom du processus]
   * [!UICONTROL Problème] > [!UICONTROL Évaluation des processus]
   * [!UICONTROL Problème] > [!UICONTROL Problème ou bonnes nouvelles]
   * [!UICONTROL Problème] > [!UICONTROL Date d’entrée]
   * [!UICONTROL Problème] > [!UICONTROL Age]
   * [!UICONTROL Problème] > [!UICONTROL Affectations]
   * [!UICONTROL Problème] > [!UICONTROL État]

1. Sélectionnez la variable **[!UICONTROL Date d’entrée]** et modifiez la variable **[!UICONTROL Tri vers descendant]**.
1. Dans le **[!UICONTROL Groupements]** , définissez le rapport sur le groupe suivant : **[!UICONTROL Problème] > [!UICONTROL Type de processus]**.

   ![Image de l’écran de création de groupes de rapports de problèmes](assets/task-report-activity-2-2.png)

1. Dans le **[!UICONTROL Filtres]** , ajoutez un filtre pour la variable **[!UICONTROL Problème] > [!UICONTROL Identifiant de projet]** pour égaler le projet de file d’attente des demandes où résident les problèmes de retour.

   ![Image de l’écran de création de filtres de rapport de problème](assets/task-report-activity-2-3.png)

1. Enregistrez et fermez votre rapport.
