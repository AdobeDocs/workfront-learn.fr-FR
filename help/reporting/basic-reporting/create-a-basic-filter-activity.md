---
title: Créer des activités de filtre de base
description: Dans cette activité, vous allez créer un filtre de projet nommé « Tous les projets du portefeuille marketing » et un autre nommé « Projets dont je suis propriétaire qui se terminent ce mois-ci ».
activity: use
feature: Reports and Dashboards
thumbnail: 336807.jpeg
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
jira: KT-8856
last-substantial-update: '2025-05-15T00:00:00.000Z'
exl-id: fc29b4ce-2937-478e-abd5-0b559657ead0
doc-type: video
product_v2: id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2: id: c6dd2ac5-f5bd-4e59-9101-25b156918623
subfeature_v2: id: ceb4d94a-32ed-4fea-9724-1339d684b0bc
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
autotag-review: '2026-05-06T14:23:25.803Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 462
ht-degree: 100%

---

# Créer des activités de filtre de base


## Activité 1 - Tous les projets du portfolio marketing

Dans cette activité, vous allez créer un filtre de projet nommé « Tous les projets du portfolio marketing » dans l’expérience [!UICONTROL Filtre hérité]. Vous verrez alors tous les projets du portfolio nommé « Portfolio marketing », quel que soit leur statut.

Vous trouverez ci-dessous des instructions détaillées.

## Réponse à l’activité 1

![Image de l’écran pour créer un nouveau filtre](assets/basic-filter-activity-1.png)

1. Accédez à la zone [!UICONTROL Projets] à partir du [!UICONTROL Menu principal]. Vous affichez ainsi la liste des projets.
1. Cliquez sur le menu **[!UICONTROL Filtre]** et sélectionnez [!UICONTROL Filtres hérités], le cas échéant.
1. Sélectionnez **[!UICONTROL Nouveau filtre]**.
1. Nommez votre filtre « Tous les projets du portfolio marketing ».
1. Cliquez sur **[!UICONTROL Ajouter une règle de filtre]**.
1. Cliquez sur le champ **Sélectionner un champ** et commencez à saisir les mots « [!UICONTROL nom du portefeuille] ». Sélectionnez ensuite [!UICONTROL Nom] dans la source du champ [!UICONTROL Portfolio].
1. Laissez l’opérateur [!UICONTROL Égal] en l’état.
1. Saisissez « [!UICONTROL marketing] » dans le champ de recherche.
1. Sélectionnez [!UICONTROL Portfolio marketing] en supposant que vous ayez un portfolio portant ce nom que vous souhaitez filtrer. Si ce n’est pas le cas, utilisez simplement la fonctionnalité de suggestion automatique pour trouver le portfolio que vous souhaitez.
1. Cliquez sur **[!UICONTROL Enregistrer le filtre]**.

## Activité 2 - Mes projets se terminant ce mois-ci

Dans cette vidéo, vous allez créer un filtre de projet nommé « Mes projets se terminant ce mois-ci » dans l’expérience [!UICONTROL Filtre hérité]. Si vous gardez un œil sur de nombreux projets, ce filtre peut vous aider à vous focaliser sur ceux qui doivent bientôt se terminer.

Vous trouverez ci-dessous des instructions détaillées.

>[!VIDEO](https://video.tv.adobe.com/v/336807/?quality=12&learn=on&enablevpops=1)

## Réponse à l’activité 2

![Image de l’écran pour créer un nouveau filtre](assets/basic-filter-activity-2.png)

1. Accédez à la zone [!UICONTROL Projets] à partir du [!UICONTROL Menu principal]. Vous affichez ainsi la liste des projets.
1. Cliquez sur le menu **[!UICONTROL Filtre]** et sélectionnez [!UICONTROL Filtres hérités], le cas échéant.
1. Sélectionnez **[!UICONTROL Nouveau filtre]**.
1. Nommez votre filtre « Mes projets se terminant ce mois-ci ».
1. Cliquez sur **[!UICONTROL Ajouter une règle de filtre]**.
1. Cliquez sur le champ **Sélectionner un champ** et commencez à saisir le mot « Propriétaire ». Cliquez maintenant sur Identifiant de la personne propriétaire sous la source de champ [!UICONTROL Projet].
1. Laissez l’opérateur [!UICONTROL Égal] en l’état.
1. Saisissez « $$ » dans le champ de recherche.
1. Sélectionnez [!UICONTROL $$USER.ID]. Il s’agit du caractère générique pour un utilisateur ou une utilisatrice connecté.
1. Cliquez sur Ajouter une autre règle de filtrage.
1. Cliquez sur le champ **Sélectionner un champ** et commencez à saisir le mot « Est terminé ». Cliquez maintenant sur « Est terminé » sous la source du champ [!UICONTROL Projet].
1. Laissez l’opérateur [!UICONTROL Égal] en l’état.
1. Sélectionnez « Faux ».
1. Cliquez à nouveau sur Ajouter une autre règle de filtrage.
1. Cliquez sur le champ **Sélectionner un champ** et commencez à saisir le mot « Prévu ». Cliquez maintenant sur « Date d’achèvement prévue » sous la source de champ [!UICONTROL Projet].
1. Définissez l’opérateur [!UICONTROL Égal] sur [!UICONTROL Ce mois-ci].
1. Cliquez sur **[!UICONTROL Enregistrer le filtre]**.
