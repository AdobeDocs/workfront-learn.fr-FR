---
title: Créer des activités de filtre de base
description: Dans cette activité, vous allez créer un filtre de projet nommé « Tous les projets du portefeuille marketing » et un autre nommé « Projets dont je suis propriétaire qui se terminent ce mois-ci ».
activity: use
feature: Reports and Dashboards
thumbnail: 336807.jpeg
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
jira: KT-8856
last-substantial-update: 2025-05-15T00:00:00Z
exl-id: fc29b4ce-2937-478e-abd5-0b559657ead0
doc-type: video
source-git-commit: 0755d62240ab307d3759c47c4561264cb4baadab
workflow-type: tm+mt
source-wordcount: '458'
ht-degree: 64%

---

# Créer des activités de filtre de base


## Activité 1 - Tous les projets du portfolio marketing

Dans cette activité, vous allez créer un filtre de projet nommé « Tous les projets du portfolio marketing » dans l’expérience [!UICONTROL Filtre hérité]. Vous verrez alors tous les projets du portfolio nommé « Portfolio marketing », quel que soit leur statut.

Vous trouverez ci-dessous des instructions détaillées.

## Réponse à l’activité 1

![Image de l’écran pour créer un nouveau filtre](assets/basic-filter-activity-1.png)

1. Accédez à la zone [!UICONTROL Projets] à partir du [!UICONTROL Menu principal]. Vous affichez ainsi la liste des projets.
1. Cliquez sur le menu **[!UICONTROL Filtre]** et sélectionnez [!UICONTROL Filtres hérités] s’il n’est pas déjà sélectionné.
1. Sélectionnez **[!UICONTROL Nouveau filtre]**.
1. Nommez votre filtre « Tous les projets du portfolio marketing ».
1. Cliquez sur **[!UICONTROL Ajouter une règle de filtre]**.
1. Cliquez sur le champ **Sélectionner un champ** et commencez à saisir les mots « [!UICONTROL nom du portefeuille] ». Sélectionnez ensuite [!UICONTROL Nom] dans la source du champ [!UICONTROL Portfolio].
1. Laissez l’opérateur [!UICONTROL Égal] en l’état.
1. Saisissez « [!UICONTROL  marketing ] » dans le champ de recherche.
1. Sélectionnez [!UICONTROL Portfolio marketing] en supposant que vous ayez un portfolio portant ce nom que vous souhaitez filtrer. Si ce n’est pas le cas, utilisez simplement la fonctionnalité de suggestion automatique pour trouver le portfolio que vous souhaitez.
1. Cliquez sur **[!UICONTROL Enregistrer le filtre]**.

## Activité 2 - Mes projets se terminant ce mois-ci

Dans cette vidéo, vous allez créer un filtre de projet nommé « Mes projets se terminant ce mois-ci » dans l’expérience [!UICONTROL Filtre hérité]. Si vous gardez un œil sur de nombreux projets, ce filtre peut vous aider à vous focaliser sur ceux qui doivent bientôt se terminer.

Vous trouverez ci-dessous des instructions détaillées.

>[!VIDEO](https://video.tv.adobe.com/v/336807/?quality=12&learn=on&enablevpops)

## Réponse à l’activité 2

![Image de l’écran pour créer un nouveau filtre](assets/basic-filter-activity-2.png)

1. Accédez à la zone [!UICONTROL Projets] à partir du [!UICONTROL Menu principal]. Vous affichez ainsi la liste des projets.
1. Cliquez sur le menu **[!UICONTROL Filtre]** et sélectionnez [!UICONTROL Filtres hérités] s’il n’est pas déjà sélectionné.
1. Sélectionnez **[!UICONTROL Nouveau filtre]**.
1. Nommez votre filtre « Mes projets se terminant ce mois-ci ».
1. Cliquez sur **[!UICONTROL Ajouter une règle de filtre]**.
1. Cliquez sur le champ **Sélectionner un champ** et commencez à saisir le mot « Propriétaire ». Cliquez maintenant sur Identifiant du propriétaire sous la source de champ [!UICONTROL Projet].
1. Laissez l’opérateur [!UICONTROL Égal] en l’état.
1. Saisissez « $$ » dans le champ de recherche.
1. Sélectionnez [!UICONTROL $$USER.ID]. Il s’agit du caractère générique pour un utilisateur ou une utilisatrice connecté.
1. Cliquez sur Ajouter une autre règle de filtrage.
1. Cliquez sur le champ **Sélectionner un champ** et commencez à saisir le mot « Est terminé ». Cliquez maintenant sur « Est terminé » sous la source du champ [!UICONTROL Projet].
1. Laissez l’opérateur [!UICONTROL Égal] en l’état.
1. Sélectionnez « Faux ».
1. Cliquez à nouveau sur Ajouter une autre règle de filtrage.
1. Cliquez sur le champ **Sélectionner un champ** et commencez à saisir le mot « Prévu ». Cliquez maintenant sur « Date d’achèvement prévue » sous la source de champ [!UICONTROL Projet].
1. Définissez l’opérateur [!UICONTROL Égal] sur [!UICONTROL Ce mois-ci].
1. Cliquez sur **[!UICONTROL Enregistrer le filtre]**.
