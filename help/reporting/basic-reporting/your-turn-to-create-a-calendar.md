---
title: 'Activité : créer un rapport de calendrier'
description: Instructions détaillées pour la création du calendrier d’un client ou d’une cliente qui affiche vos tâches et problèmes incomplets.
activity: use
team: Technical Marketing
feature: Reports and Dashboards
type: Tutorial
role: User
level: Beginner
last-substantial-update: '2025-06-23T00:00:00.000Z'
thumbnail: your-turn-to-create-a-calendar.png
jira: KT-10026
exl-id: 74d57f1a-c6c5-49e0-9529-2e2deb2f273e
product_v2: id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2: id: c6dd2ac5-f5bd-4e59-9101-25b156918623
subfeature_v2: id: c6584858-4838-4ce3-ab7f-7292f37179f4
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
autotag-review: '2026-05-06T14:16:18.343Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 362
ht-degree: 100%

---

# Activité : créer un rapport de calendrier

Créez un calendrier client intitulé « Mon travail inachevé ».

Incluez un groupe de calendriers nommé « Tâches inachevées » montrant toutes les tâches inachevées qui vous ont été assignées sur les projets en cours.

Sélectionnez le rouge comme couleur pour ces éléments.

Incluez un autre groupe de calendriers nommé « Problèmes non résolus » montrant tous les problèmes non résolus qui vous ont été assignés sur les projets en cours. Sélectionnez le bleu comme couleur pour ces éléments.

## Réponse

1. Naviguez vers la zone Calendriers à partir du menu principal.
1. Cliquez sur le bouton Nouveau calendrier et nommez le calendrier « Mon travail inachevé ».
1. Cliquez sur le bouton Ajouter au calendrier, puis sur Ajouter des éléments avancés.
1. Dans la fenêtre Ajouter des éléments au calendrier qui s’affiche, nommez le groupe « Tâches inachevées ».
1. Sélectionnez le rouge comme couleur.
1. Remplacez le champ Date par Dates planifiées.
1. Définissez le champ Sur le calendrier, afficher sur Date de fin uniquement.
1. Définissez le champ Passer aux dates réelles lorsque le champ est disponible sur Non.
1. Dans la section Que souhaitez-vous ajouter au calendrier ? sélectionnez Tâches. Cliquez ensuite sur le bouton Ajouter des tâches.
1. Ajoutez trois règles de filtrage :

   * Projet > Statut est égal à > Égal à > Actuel
   * Utilisateurs/utilisatrices de l’affectation > ID > Égal à > $$USER.ID
   * Tâche > Est terminée > Égal à > Faux

1. Cliquer sur Enregistrer.

   ![Image de l’écran d’ajout d’éléments à un calendrier](assets/calendar-activity-1.png)

1. Créez un second regroupement en cliquant sur Ajouter au calendrier, puis sur Ajouter des éléments avancés.
1. Dans la fenêtre Ajouter des éléments au calendrier qui s’affiche, nommez le groupe « Problèmes non résolus ».
1. Sélectionnez le bleu comme couleur.
1. Remplacez le champ Date par Dates planifiées.
1. Définissez le champ Sur le calendrier, afficher sur Date de fin uniquement.
1. Définissez le champ Passer aux dates réelles lorsque le champ est disponible sur Non.
1. Dans la section Que souhaitez-vous ajouter au calendrier ? sélectionnez Problèmes. Cliquez ensuite sur le bouton Ajouter des problèmes.
1. Ajoutez les trois règles de filtrage suivantes :

   * Projet > Statut est égal à > Égal à > Actuel
   * Utilisateurs/utilisatrices de l’affectation > ID > Égal à > $$USER.ID
   * Problème > Est résolu > Égal à > Faux

1. Cliquer sur Enregistrer.

   ![Image de l’écran d’ajout d’éléments à un calendrier](assets/calendar-activity-2.png)

Comme vous avez utilisé $$USER.ID dans les filtres, vous pouvez partager ce calendrier avec d’autres personnes qui verront leurs propres tâches inachevées et problèmes non résolus.
