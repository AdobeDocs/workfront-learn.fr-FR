---
title: Création d’activités de rapport de matrice
description: Pratiquez la création de rapports matriciels, avec des instructions étape par étape.
activity: use
feature: Reports and Dashboards
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
thumbnail: 335156.png
jira: KT-8861
hidefromtoc: true
source-git-commit: 915b28bbbf138fa84dce6d1915387fbe22c63362
workflow-type: tm+mt
source-wordcount: '236'
ht-degree: 66%

---

# Création d’activités de rapport de matrice

Pratiquez la création de rapports matriciels, avec des instructions étape par étape.

## Activité 1 : Création d’un rapport de matrice

Créez un rapport de matrice indiquant le nombre de demandes dans chaque statut, triées par file d’attente. Cela vous donne un aperçu rapide de la quantité de travail qui arrive et de la façon dont vous suivez le rythme.

Vous souhaitez que les files d’attente des demandes apparaissent dans les regroupements de lignes. Le statut apparaît dans les regroupements de colonnes. Nommez votre rapport « Demandes par statut et file d’attente des demandes ».

## Réponse 1

1. Sélectionnez **[!UICONTROL Rapports]** dans le **[!UICONTROL menu principal]**.
1. Cliquez sur l’option **[!UICONTROL Nouveau rapport]** et sélectionnez **[!UICONTROL Problème]**.
1. Accédez à l’onglet **[!UICONTROL Regroupements]** et cliquez sur **[!UICONTROL Basculer vers le regroupement de matrice]**.
1. Pour [!UICONTROL Regroupements de lignes], sélectionnez **[!UICONTROL Projet]** > **[!UICONTROL Nom]**.
1. Pour [!UICONTROL Regroupement de colonnes], sélectionnez **[!UICONTROL Problème]** > **[!UICONTROL Statut]**.

   ![Image de l’écran permettant de créer un nouveau regroupement de rapports de problèmes.](assets/matrix-report-groupings.png)

1. Accédez à l’onglet **[!UICONTROL Filtres]**.
1. Pour vous assurer que seules les demandes présentes dans les files d’attente des demandes actives sont visibles, ajoutez les règles de filtrage suivantes :

   * [!UICONTROL Projet] > [!UICONTROL Le statut correspond à] > [!UICONTROL Égal] > [!UICONTROL Actuel].
   * [!UICONTROL Définition de la file d’attente] > [!UICONTROL Est publique] > [!UICONTROL Différent de] > [!UICONTROL Aucun] (c’est ainsi que nous savons qu’un projet est en fait une file d’attente des demandes, par la définition de file d’attente affectée à l’une des options publiques).

1. Cliquez sur **[!UICONTROL Enregistrer + Fermer]**. Lorsque vous êtes invité à saisir un nom de rapport, saisissez « Demandes par statut et file d’attente des demandes ».

   ![Image de l’écran permettant de créer un filtre de rapport de problèmes](assets/matrix-report-filters.png)
