---
title: Créer des rapports avec des graphiques
description: Découvrez comment les graphiques peuvent améliorer la visualisation des données et comment utiliser les outils de graphique dans Workfront.
activity: use
feature: Reports and Dashboards
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
thumbnail: 335153.png
jira: KT-8860
exl-id: ea3b360b-1fbd-4d1a-b505-b75759d24e41
doc-type: video
source-git-commit: 2c9e57b8f85c74061bd3e52ef4eaea60bc4ec5bb
workflow-type: tm+mt
source-wordcount: '334'
ht-degree: 98%

---

# Créer des rapports avec des graphiques

Dans cette vidéo, vous apprendrez :

* Comment les graphiques peuvent améliorer la visualisation des données
* Comment utiliser des outils de graphique Workfront

>[!VIDEO](https://video.tv.adobe.com/v/335155/?quality=12&learn=on)

## Activités « Créer des rapports avec des graphiques »

### Activité 1 : ajouter un graphique à un rapport

La fin du trimestre approche et vous souhaitez savoir si les projets récemment achevés ont respecté leur budget. Créez un rapport qui montre le coût prévu par rapport au coût réel pour les projets. Vous ne voulez afficher que les projets qui ont été achevés au cours du dernier trimestre. Ajoutez un graphique en colonnes combiné avec des couleurs personnalisées.

### Réponse 1

1. Sélectionnez **[!UICONTROL Rapports]** dans le **[!UICONTROL menu principal]**.
1. Cliquez sur le bouton **[!UICONTROL Nouveau rapport]** et sélectionnez **[!UICONTROL Projet]**.
1. Dans l’onglet **[!UICONTROL Colonnes (affichage)]**, cliquez sur **[!UICONTROL Ajouter une colonne]**.
1. Sélectionnez [!UICONTROL Projet] > [!UICONTROL Coût prévu] et résumez cette colonne par **[!UICONTROL Somme]**.
1. Cliquez sur **[!UICONTROL Ajouter une colonne]** encore une fois.
1. Sélectionnez [!UICONTROL Projet] > [!UICONTROL Coût réel] et résumez cette colonne par **[!UICONTROL Somme]**.

   ![Image de l’écran d’ajout de colonnes à un rapport](assets/chart-report-columns.png)

1. Dans l’onglet **[!UICONTROL Reroupements]**, définissez le rapport sur un regroupement par [!UICONTROL Projet] > [!UICONTROL Nom].

   ![Image de l’écran d’ajout de groupes à un rapport](assets/chart-report-groupings.png)

1. Dans l’onglet **[!UICONTROL Filtres]**, ajoutez deux règles de filtrage :

   * [!UICONTROL Projet] > [!UICONTROL Le statut correspond à] > [!UICONTROL Terminé].
   * [!UICONTROL Projet] >[!UICONTROL  Date d’achèvement réelle] > [!UICONTROL Dernier trimestre].

   ![Image de l’écran d’ajout de filtres à un rapport](assets/chart-report-filters.png)

1. Dans l’onglet **[!UICONTROL Graphique]**, choisissez **[!UICONTROL Colonne]** pour le type de graphique.
1. Pour l’[!UICONTROL axe gauche (Y)], choisissez [!UICONTROL Projet] > [!UICONTROL Coût prévu].
1. Pour l’[!UICONTROL axe inférieur (X)], choisissez [!UICONTROL Projet] > [!UICONTROL Nom].
1. Cliquez sur le bouton **[!UICONTROL Graphique combiné]** et sélectionnez [!UICONTROL Projet] > [!UICONTROL Coût réel] dans le champ **[!UICONTROL Valeur]**.
1. Cliquez sur la flèche à côté de la case de couleur pour modifier la couleur de [!UICONTROL Coût réel]. Sélectionnez l’une des couleurs qui s’affichent ou cliquez sur la case située dans le coin inférieur droit pour afficher la palette de couleurs.
1. Cliquez sur **[!UICONTROL Enregistrer + Fermer]**. Lorsque l’on vous invite à saisir un nom de rapport, appelez-le « Coût prévu par rapport au coût réel par projet terminé le dernier trimestre ».

   ![Image de l’écran d’ajout d’un graphique à un rapport](assets/chart-report-chart.png)
