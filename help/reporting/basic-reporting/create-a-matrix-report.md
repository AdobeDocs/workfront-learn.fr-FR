---
title: Créer un rapport de matrice
description: Découvrez quand un rapport de matrice peut être utile et comment créer un rapport de matrice dans Workfront.
activity: use
feature: Reports and Dashboards
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
thumbnail: 335156.png
jira: KT-8861
last-substantial-update: 2025-05-20T00:00:00Z
exl-id: e893d94a-e808-4bc1-bc6e-f46a5582b55d
doc-type: video
source-git-commit: 39345609d988f5e625ec6bb78ed3be9f4dcdedc9
workflow-type: tm+mt
source-wordcount: '418'
ht-degree: 62%

---

# Créer un rapport de matrice

Dans cette vidéo, vous apprendrez :

* Quand un rapport de matrice peut être utile
* et comment créer un rapport de matrice

>[!VIDEO](https://video.tv.adobe.com/v/3448185/?quality=12&learn=on&captions=fre_fr)

## Points clés à retenir

* **Structure de rapport de matrice :** les rapports de matrice organisent les données en lignes et en colonnes, avec des totaux de lignes et de colonnes automatiques. &#x200B; Elles sont idéales pour le suivi de mesures telles que les heures travaillées, les coûts et les recettes. &#x200B;
* **Configuration des filtres :** utilisez les filtres pour vous concentrer sur des données spécifiques, telles que les heures travaillées au cours du dernier trimestre par les utilisateurs d’une équipe locale particulière. &#x200B; La « source du champ du propriétaire » permet d’identifier les membres de l’équipe pertinents. &#x200B;
* **Options de regroupement :** dans notre exemple, les lignes sont regroupées par « nom du propriétaire » (personne qui a travaillé les heures), tandis que les colonnes sont regroupées par « date de saisie des heures » (par mois et par semaine). &#x200B;
* **Données résumées :** les colonnes telles que les heures, le coût réel et le chiffre d’affaires sont résumées par défaut, afin de garantir l’affichage des totaux dans la matrice. Ces valeurs par défaut peuvent être désactivées, si vous le souhaitez. &#x200B;
* **Intégration de graphiques :** les rapports de matrice peuvent être complétés par des graphiques pour une visualisation des données alternative, en utilisant les mêmes informations de regroupement. Vous pouvez définir l’onglet de matrice ou l’onglet de graphique comme vue par défaut. &#x200B;

## Activités Créer un rapport de matrice

### Activité 1 : créer un rapport de matrice

Créez un rapport de matrice indiquant le nombre de demandes dans chaque statut, triées par file d’attente. Vous obtenez ainsi un aperçu rapide de la quantité de travail à accomplir et de la façon dont vous avancez.

Vous souhaitez que les files d’attente des demandes apparaissent dans les regroupements de lignes. Le statut apparaît dans les regroupements de colonnes. Nommez votre rapport « Demandes par statut et file d’attente des demandes ».

### Réponse 1

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

1. Cliquez sur **[!UICONTROL Enregistrer + Fermer]**. Lorsque l’on vous invite à saisir un nom de rapport, saisissez « Demandes par statut et file d’attente des demandes ».

   ![Image de l’écran permettant de créer un filtre de rapport de problèmes](assets/matrix-report-filters.png)
