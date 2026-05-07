---
title: Visualiser des données avec des graphiques dans des rapports
description: Les graphiques améliorent la visualisation des données en organisant les informations sur les données par le biais de filtres, de regroupements et de formats de colonnes empilés personnalisables, ce qui rend l’analyse plus claire et plus exploitable.
activity: use
feature: Reports and Dashboards
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
thumbnail: 335153.png
jira: KT-8860
last-substantial-update: '2025-05-06T00:00:00.000Z'
exl-id: ea3b360b-1fbd-4d1a-b505-b75759d24e41
doc-type: video
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
subfeature_v2:
  - id: ceb4d94a-32ed-4fea-9724-1339d684b0bc
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
autotag-review: '2026-05-06T14:21:20.703Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 590
ht-degree: 65%

---

# Visualiser des données avec des graphiques dans des rapports

La vidéo explique comment utiliser des graphiques pour visualiser efficacement les données, en particulier pour effectuer le suivi des tâches du projet. &#x200B; Il illustre la création de deux types de rapports dans Workfront :

**Rapport Tâches en retard par projet :**

* Commencez avec un rapport de liste et appliquez des filtres pour afficher uniquement les tâches incomplètes et en retard dans les projets actuels. &#x200B;
* Regroupez les tâches par nom de projet et créez un graphique en secteurs pour visualiser la répartition des tâches en retard entre les projets. &#x200B;
* Définissez le graphique comme onglet par défaut pour un accès plus facile. &#x200B;

**Rapport Tâches par projet et Statut de la progression :**

* Copiez le premier rapport et ajoutez un autre regroupement pour le statut de la progression des tâches.
* Supprimez les filtres pour inclure toutes les tâches et afficher leur progression pendant l’exécution du projet.
* Utilisez un graphique à colonnes empilées pour afficher le nombre total de tâches par projet, avec des piles représentant les différents statuts de la progression.
* Personnalisez les couleurs si nécessaire et enregistrez le rapport.

La vidéo montre comment des graphiques tels que les secteurs et les graphiques à colonnes empilés peuvent fournir des informations sur la distribution des tâches et les performances des projets, ce qui permet aux utilisateurs de comparer les projets et de comprendre visuellement la progression des tâches. &#x200B;

>[!VIDEO](https://video.tv.adobe.com/v/3450016/?captions=fre_fr&quality=12&learn=on&enablevpops=0)

## Points essentiels à retenir

* **Les graphiques améliorent la clarté des données** : la visualisation des données avec des graphiques, tels que les graphiques à secteurs ou à colonnes, facilite la compréhension de la répartition des tâches et de l’avancement du projet par rapport aux rapports de liste. &#x200B;
* **Filtrage pour obtenir des informations spécifiques** : l’application de filtres (par exemple, pour les tâches incomplètes ou en retard dans les projets actuels) permet de se concentrer sur les données pertinentes pour une analyse ciblée. &#x200B;
* **Regroupement pour une meilleure organisation** : le regroupement des tâches par nom de projet ou statut d’avancement organise les données de manière efficace, ce qui permet des comparaisons significatives entre les projets. &#x200B;
* **Options de personnalisation des graphiques** : les utilisateurs peuvent sélectionner des types de graphiques (par exemple, circulaire, à colonnes, à barres) et personnaliser les couleurs pour s’aligner sur les préférences ou l’identité graphique. &#x200B;
* **Graphiques à colonnes empilés pour des informations détaillées** : les graphiques à colonnes empilés fournissent une vue complète de la progression des tâches dans les projets, présentant à la fois le total des tâches et leurs statuts en une seule visualisation.


## Activités Créer des rapports avec des graphiques

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
   * [!UICONTROL Projet] >[!UICONTROL &#x200B; Date d’achèvement réelle] > [!UICONTROL Dernier trimestre].

   ![Image de l’écran d’ajout de filtres à un rapport](assets/chart-report-filters.png)

1. Dans l’onglet **[!UICONTROL Graphique]**, choisissez **[!UICONTROL Colonne]** pour le type de graphique.
1. Pour l’[!UICONTROL axe gauche (Y)], choisissez [!UICONTROL Coût prévu].
1. Pour l’[!UICONTROL axe inférieur (X)], choisissez [!UICONTROL Nom].
1. Cliquez sur le bouton **[!UICONTROL Graphique combiné]** et sélectionnez [!UICONTROL Coût réel] dans le champ **[!UICONTROL Valeur]**.
1. Dans le champ **[!UICONTROL Type de graphique]**, sélectionnez Linéaire.
1. Cliquez sur la case de couleur pour modifier la couleur de [!UICONTROL Coût réel]. Sélectionnez une couleur.
1. Cliquez sur **[!UICONTROL Enregistrer et fermer]**. Lorsque l’on vous invite à saisir un nom de rapport, appelez-le « Coût prévu par rapport au coût réel par projet terminé le dernier trimestre ».

   ![Image de l’écran d’ajout d’un graphique à un rapport](assets/chart-report-chart.png)
