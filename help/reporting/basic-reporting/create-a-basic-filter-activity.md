---
title: Créer des activités de filtre de base
description: Dans cette activité, vous allez créer un filtre de projet nommé "Projets dont je suis propriétaire et qui se terminent ce mois-ci".
activity: use
feature: Reports and Dashboards
thumbnail: 336807.jpeg
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
jira: KT-8856
exl-id: fc29b4ce-2937-478e-abd5-0b559657ead0
doc-type: video
source-git-commit: 0ff5accae867f07cc31ac2be7b0c12981412346e
workflow-type: tm+mt
source-wordcount: '420'
ht-degree: 32%

---

# Créer des activités de filtre de base

## Activité 1 - Tous les projets du portefeuille marketing

Dans cette activité, vous allez créer un filtre de projet nommé &quot;Tous les projets du portefeuille marketing&quot; dans la variable [!UICONTROL Filtre hérité] expérience. Vous verrez alors tous les projets du portefeuille nommés &quot;Portfolio marketing&quot;, quel que soit leur état.

Vous trouverez ci-dessous des instructions détaillées.

### Réponse à l’activité 1

![Image de l’écran pour créer un nouveau filtre](assets/basic-filter-activity-1.png)

1. Accédez à la zone [!UICONTROL Projets] à partir du [!UICONTROL Menu principal]. Vous affichez ainsi la liste des projets.
1. Cliquez sur le bouton **[!UICONTROL Filtrer]** et sélectionnez [!UICONTROL Filtres hérités].
1. Sélectionner **[!UICONTROL Nouveau filtre]**.
1. Nommez votre filtre &quot;Tous les projets du portefeuille marketing&quot;.
1. Cliquez sur **[!UICONTROL Ajouter une règle de filtre]**.
1. Dans le [!UICONTROL Commencer à saisir le nom du champ] field, type &quot;[!UICONTROL nom du portfolio]&quot;. Sélectionnez [!UICONTROL Nom] sous le [!UICONTROL Portfolio] source du champ.
1. Laissez l’opérateur [!UICONTROL Égal] en l’état.
1. Type &quot;[!UICONTROL marketing]&quot; dans la variable [!UICONTROL Commencer à saisir le nom] champ .
1. Sélectionner [!UICONTROL Portfolio marketing] en supposant que vous ayez un portefeuille portant ce nom que vous souhaitez filtrer. Si ce n’est pas le cas, utilisez simplement la fonction de type à l’avance pour trouver le portfolio que vous souhaitez.
1. Cliquez sur **[!UICONTROL Enregistrer le filtre]**.

## Activité 2 - Projets dont je suis propriétaire qui ferment ce mois-ci

Dans cette vidéo, vous allez créer un filtre de projet nommé &quot;Projets dont je suis propriétaire qui se terminent ce mois-ci&quot; dans la variable [!UICONTROL Filtre hérité] expérience. Si vous gardez un oeil sur de nombreux projets, ce filtre peut vous aider à zoomer sur ceux qui doivent bientôt se fermer.

Vous trouverez ci-dessous des instructions détaillées.

>[!VIDEO](https://video.tv.adobe.com/v/336807/?quality=12&learn=on)

### Réponse à l’activité 2

![Image de l’écran pour créer un nouveau filtre](assets/basic-filter-activity-updated-6-15-21.png)

1. Accédez à la zone [!UICONTROL Projets] à partir du [!UICONTROL Menu principal]. Vous affichez ainsi la liste des projets.
1. Cliquez sur le bouton **[!UICONTROL Filtrer]** et sélectionnez [!UICONTROL Filtres hérités].
1. Sélectionner **[!UICONTROL Nouveau filtre]**.
1. Nommez votre filtre &quot;Projets dont je suis propriétaire fermant ce mois-ci&quot;.
1. Cliquez sur **[!UICONTROL Ajouter une règle de filtre]**.
1. Dans le [!UICONTROL Commencer à saisir le nom du champ] , saisissez &quot;propriétaire&quot;. Sélectionnez [!UICONTROL Identifiant du propriétaire] dans la source du champ [!UICONTROL Projet].
1. Laissez l’opérateur [!UICONTROL Égal] en l’état.
1. Saisissez &quot;$$&quot; dans le champ [!UICONTROL Commencer à saisir le nom] champ .
1. Sélectionnez [!UICONTROL $$USER.ID]. Il s’agit du caractère générique pour un utilisateur ou une utilisatrice connecté.
1. Cliquez sur [!UICONTROL Ajouter une règle de filtre] à nouveau.
1. Dans le [!UICONTROL Commencer à saisir le nom du champ] , commencez à saisir &quot;Est terminé&quot;. Sélectionnez ensuite [!UICONTROL Est terminé] dans la source du champ Projet.
1. Laissez l’opérateur [!UICONTROL Égal] en l’état.
1. Sélectionnez &quot;False&quot;.
1. Cliquez sur [!UICONTROL Ajouter une règle de filtre] à nouveau.
1. Dans le [!UICONTROL Commencer à saisir le nom du champ] type de champ &quot;planifié&quot;, puis sélectionnez [!UICONTROL Date d’achèvement prévue] sous le [!UICONTROL Projet] source du champ.
1. Définissez l’opérateur [!UICONTROL Égal] sur [!UICONTROL Ce mois-ci].
1. Cliquez sur **[!UICONTROL Enregistrer le filtre]**.
