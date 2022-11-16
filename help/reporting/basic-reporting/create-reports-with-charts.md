---
title: Création de rapports avec des graphiques
description: Découvrez comment les graphiques peuvent améliorer la visualisation des données et comment utiliser les outils de graphique dans Workfront.
activity: use
feature: Reports and Dashboards
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
thumbnail: 335153.png
kt: 8860
exl-id: ea3b360b-1fbd-4d1a-b505-b75759d24e41
source-git-commit: 252ba3ba44f22519a35899fcda9c6bca597a6c2c
workflow-type: tm+mt
source-wordcount: '327'
ht-degree: 0%

---

# Création de rapports avec des graphiques

Dans cette vidéo, vous apprendrez :

* Comment les graphiques peuvent améliorer la visualisation des données
* Utilisation des outils de graphique Workfront

>[!VIDEO](https://video.tv.adobe.com/v/335155/?quality=12)

## Activité : Ajout d’un graphique à un rapport

La fin du trimestre approche, et vous voulez voir comment les projets récemment terminés restent fidèles à leurs budgets. Créez un rapport qui présente le coût prévu par rapport au coût réel des projets. Vous souhaitez afficher uniquement les projets qui ont été terminés au dernier trimestre. Ajoutez un graphique en colonnes combiné avec des couleurs personnalisées.

## Réponse

1. Sélectionner **[!UICONTROL Rapports]** de la **[!UICONTROL Menu Principal]**.
1. Cliquez sur le bouton **[!UICONTROL Nouveau rapport]** et sélectionnez **[!UICONTROL Projet]**.
1. Dans le **[!UICONTROL Colonnes (affichage)]** , cliquez sur **[!UICONTROL Ajouter une colonne]**.
1. Sélectionner [!UICONTROL Projet] > [!UICONTROL Coût planifié] et résumez cette colonne par **[!UICONTROL Somme]**.
1. Cliquez sur **[!UICONTROL Ajouter une colonne]** encore une fois.
1. Sélectionner [!UICONTROL Projet] > [!UICONTROL Coût réel] et résumez cette colonne par **[!UICONTROL Somme]**.

   ![Image de l’écran d’ajout de colonnes à un rapport](assets/chart-report-columns.png)

1. Dans le **[!UICONTROL Groupements]** , définissez le rapport sur le groupe suivant : [!UICONTROL Projet] > [!UICONTROL Nom].

   ![Image de l’écran d’ajout de groupes à un rapport](assets/chart-report-groupings.png)

1. Dans le **[!UICONTROL Filtres]** ajoutez deux règles de filtrage :

   * [!UICONTROL Projet] > [!UICONTROL L’état correspond à] > [!UICONTROL Terminer]
   * [!UICONTROL Projet] >[!UICONTROL  Date d’achèvement réelle] > [!UICONTROL Dernier trimestre]

   ![Image de l’écran d’ajout de filtres à un rapport](assets/chart-report-filters.png)

1. Dans le **[!UICONTROL Graphique]** , choisissez **[!UICONTROL Colonne]** pour le type de graphique.
1. Pour le [!UICONTROL Axe gauche (Y)], choisissez [!UICONTROL Projet] > [!UICONTROL Coût planifié].
1. Pour le [!UICONTROL Axe inférieur (X)], choisissez [!UICONTROL Projet] > [!UICONTROL Nom].
1. Cliquez sur le bouton **[!UICONTROL Graphique en combinaison]** et sélectionnez [!UICONTROL Projet] > [!UICONTROL Coût réel] dans le **[!UICONTROL Valeur]** champ .
1. Cliquez sur la flèche en regard de la zone de couleur pour modifier la variable [!UICONTROL Coût réel] couleur. Sélectionnez l’une des couleurs qui s’affichent ou cliquez sur la case située dans le coin inférieur droit pour afficher la palette de couleurs.
1. Cliquez sur **[!UICONTROL Enregistrer + Fermer]**. Lorsque vous êtes invité à saisir un nom de rapport, appelez-le &quot;Coût planifié par rapport au coût réel par projet terminé le dernier trimestre&quot;.

   ![Image de l’écran auquel ajouter un graphique à un rapport](assets/chart-report-chart.png)
