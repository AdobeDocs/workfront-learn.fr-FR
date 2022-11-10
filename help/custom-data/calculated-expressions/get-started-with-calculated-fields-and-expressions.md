---
title: Prise en main des champs et expressions calculés
description: Découvrez comment créer des expressions dans des champs calculés afin de collecter des données personnalisées uniques sur le travail effectué pour votre organisation.
feature: System Setup and Administration
type: Tutorial
role: Admin, Leader, User
level: Experienced
activity: use
team: Technical Marketing
thumbnail: gs-calc-fields-expressions.png
exl-id: fbd17f01-9e97-4ead-9a56-7ce4f81255ec
source-git-commit: f81d156b4058bec70bc3256efda6f85746f0f625
workflow-type: tm+mt
source-wordcount: '500'
ht-degree: 0%

---

# Prise en main des champs et expressions calculés

<!-- **Note**: The expression examples shown are simple and some may be mitigated by fields already supplied by  . However, the examples are used to illustrate the foundational knowledge needed in order to build expressions in Workfront.-->

Workfront fournit divers champs communs à plusieurs secteurs d’activité et régulièrement utilisés pour la gestion du travail. Champs tels que la date d’achèvement prévue, le budget du projet, le nom du responsable de la tâche, etc.

Pourtant, chaque organisation possède des données spécifiques à son secteur et à sa société qui doivent être collectées pour déterminer si les objectifs de l’entreprise sont atteints. Par exemple, votre entreprise souhaite effectuer le suivi des éléments suivants :

* À quel secteur d’activité un projet contribuera-t-il ?
* Si le financement provient de fournisseurs, internes ou des deux.
* Quelle résolution est nécessaire pour les images utilisées ?

Bien que ces champs ne soient pas intrinsèquement intégrés à [!DNL Workfront], vous pouvez créer des champs de saisie de données personnalisés et des champs de réponse à sélection multiple préremplis par le biais d’un formulaire personnalisé.

Ce parcours d’apprentissage se concentre sur le champ calculé. Vous découvrirez ce qu’est un champ calculé, les différents types d’informations que vous pouvez extraire dans le champ calculé au moyen d’expressions de données et comment créer ces champs calculés afin d’améliorer la collecte de données et la création de rapports.

![Configuration d’un téléavertisseur dans la gestion des ressources](assets/GS01.png)

## Qu’est-ce qu’un champ calculé ?

Un champ calculé contient des données personnalisées créées à l’aide d’expressions de données et de champs Workfront existants.

![Équilibreur de charge de travail avec rapport d’utilisation](assets/GS02.png)

Par exemple, votre entreprise dispose d’un système de numérotation de projet spécifique, ou numéro de travail, qui comprend les éléments suivants :

* Année de création du projet,
* les initiales du propriétaire du projet, et
* Le [!DNL Workfront] numéro de référence du projet.


En utilisant des expressions dans un champ calculé, vous pouvez prendre chaque information déjà stockée dans [!DNL Workfront] et créez cet ID de projet unique, ou numéro de travail, qui peut ensuite être ajouté à un rapport comme celui-ci :

![Équilibreur de charge de travail avec rapport d’utilisation](assets/GS03.png)

En fonction des données spécifiques nécessaires, les champs calculés peuvent être simples, utilisant une ou deux expressions, ou plus complexes, à l’aide de plusieurs expressions incorporées. Gardez simplement à l’esprit que Workfront ne peut utiliser que les données déjà stockées ou extraites dans le système pour les champs calculés.

## Expressions de texte

Expressions textuelles : recherchez, disséquez et combinez les informations figurant dans la section [!DNL Workfront] pour créer des données plus significatives ou pour mieux comprendre le travail effectué pour votre entreprise.

Par exemple, les expressions de texte peuvent être utilisées pour :

* Afficher &quot;Plus de 5 000 $&quot; lorsque les dépenses du projet sont supérieures à 5 000 $ ou &quot;Moins de 5 000 $&quot; lorsque les dépenses sont inférieures à celles-ci, dans une colonne de la vue du projet.

* Attribuez à chaque projet un numéro unique qui inclut l’année de création du projet, le numéro du projet  [!DNL Workfront] numéro de référence, nom du projet et initiales du propriétaire du projet.

* Créez un rapport qui répertorie tous les projets qui ne sont pas affectés à un portefeuille et/ou à un programme afin que vous puissiez les utiliser dans vos réunions de gestionnaires.

Les expressions de texte peuvent être utilisées dans un champ personnalisé pour effectuer ces types de recherches et combinaisons dans Workfront.

Lorsque vous examinez les expressions de texte possibles, vous trouverez plusieurs options.

![Configuration d’un téléavertisseur dans la gestion des ressources](assets/TE01.png)

Il existe six expressions de texte les plus utilisées :

* CONCAT
* GAUCHE/DROITE
* CONTIENT
* IF
* ISBLANK