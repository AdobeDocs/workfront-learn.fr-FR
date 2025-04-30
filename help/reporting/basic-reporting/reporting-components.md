---
title: Comprendre les composants de reporting
description: Les composants de création de rapports de Workfront affinent la visualisation des données avec des filtres basés sur des objets, des vues dynamiques, des regroupements structurés et une fonctionnalité de caractères génériques pour des informations personnalisées.
activity: use
feature: Reports and Dashboards
thumbnail: 335146.jpeg
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
jira: KT-8850
last-substantial-update: 2025-04-28T00:00:00Z
exl-id: e9f9ba24-540f-49e1-ac52-740df489317b
doc-type: video
source-git-commit: af53d11fcf3e81c8ea0176f4db9dcec77e9195ed
workflow-type: tm+mt
source-wordcount: '533'
ht-degree: 45%

---

# Comprendre les composants de reporting

La vidéo explique le concept de composants de création de rapports dans Workfront, essentiels à la création de filtres, de vues et de regroupements. Les principaux composants sont les suivants :

* **Type d’objet :** spécifie l’objet Workfront traité, tel qu’un projet, une tâche ou une entrée d’heure. &#x200B; Les filtres, les vues et les regroupements sont spécifiques au type d&#39;objet. &#x200B;
* **Source du champ et Nom du champ :** la source du champ est l’élément dans Workfront auquel des informations sont jointes, et le nom du champ est l’élément d’information spécifique (par exemple, la « description » d’un projet). &#x200B;
* **Champ de valeur :** représente le contenu d’un champ, tel que « faible », « normal », « élevé » ou « urgent » pour le champ de priorité. &#x200B;
* **Qualificateur de filtre :** définit les valeurs à inclure ou à exclure dans un rapport, par exemple l’affichage des tâches avec une priorité « élevée ». &#x200B;


>[!VIDEO](https://video.tv.adobe.com/v/335146/?quality=12&learn=on)

## Points clés à retenir

* **Composants de création de rapports :** les composants de création de rapports Workfront incluent le type d’objet, la source du champ, le nom du champ, les qualificateurs de filtre et le champ de valeur, qui sont essentiels pour la création de filtres, de vues et de regroupements. &#x200B;
* **Spécificité du type d’objet :** les filtres, les vues et les regroupements sont liés à des types d’objet spécifiques, tels que des projets, des tâches ou des entrées d’heure, ce qui garantit que les rapports sont adaptés aux données pertinentes. &#x200B;
* **Règles de filtrage :** les filtres utilisent la source du champ, le nom du champ, les qualificateurs et les valeurs pour définir des critères. &#x200B; Par exemple, le filtre « Mes projets » affiche uniquement les projets actuels pour lesquels l’utilisateur connecté fait partie de l’équipe du projet. &#x200B;
* **Vues et regroupements :** les vues affichent les combinaisons de source des champs et de nom des champs dans des colonnes (par exemple, « nom du propriétaire »), tandis que les regroupements organisent les données en fonction de critères spécifiques (par exemple, « nom de la société »). &#x200B;
* **Utilisation de caractères génériques :** caractères génériques dans les filtres permettent une correspondance dynamique, comme l’identification des utilisateurs connectés au sein d’une équipe de projet, ce qui améliore la personnalisation des rapports. &#x200B;

## Référence rapide des composants de rapports

![Image de l’écran de création d’un filtre](assets/reporting-components-1.png)

**A - Source du champ**

Les options de source du champ dépendent du type d’objet sélectionné. Souvent, la source du champ est l’élément de Workfront auquel appartient une information spécifique (autrement dit, le nom du champ). Parfois, la source du champ est identique au type d’objet.
La source du champ détermine les noms des champs disponibles.

Exemples : [!UICONTROL Projet], [!UICONTROL Tâche], [!UICONTROL Problème], [!UICONTROL Affecté à]

**B - Nom du champ**

Les noms de champ sont des informations disponibles par rapport à ce que vous avez sélectionné comme source du champ.

Il peut s’agir de champs Workfront que vous avez remplis, de champs d’un formulaire personnalisé ou d’informations automatiquement capturées par Workfront.

Les noms de champ déterminent les options de champ de valeur.

Exemples : [!UICONTROL Statut de la progression], [!UICONTROL Description], [!UICONTROL Date d’achèvement prévue], Champs de formulaire personnalisé

**C - Qualificateurs de filtre**

Les qualificateurs de filtre permettent de réduire les résultats possibles, visibles sous la source du champ et le nom du champ sélectionné.

Ils indiquent le lien entre la source du champ et le nom du champ d’une part et le champ de valeur d’autre part.

Exemples : Égal à, Contient, Nul, Inférieur à

**D - Valeur**

La valeur est l’information saisie dans le champ spécifié par le nom du champ.

Les options pour la valeur sont déterminées par la source du champ et le nom du champ.

Vous pouvez utiliser des caractères génériques pour les utilisateurs et utilisatrices et les dates dans la valeur, ainsi que du texte de forme libre.

Exemples : Nouveau, Actuel, $$TODAYbw, Description

>[!TIP]
>
>Pour plus d’informations sur les noms de champ spécifiques dans Workfront, reportez-vous au [Glossaire de la terminologie Adobe Workfront](https://experienceleague.adobe.com/docs/workfront/using/basics/workfront-terminology-glossary.html?lang=fr).

