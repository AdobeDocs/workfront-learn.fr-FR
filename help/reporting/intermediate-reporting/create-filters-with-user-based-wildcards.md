---
title: Création de filtres avec des caractères génériques basés sur l’utilisateur
description: Découvrez comment utiliser des caractères génériques basés sur l’utilisateur et comment créer un filtre basé sur l’utilisateur connecté.
activity: use
feature: Reports and Dashboards
thumbnail: 336810.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
jira: KT-9081
exl-id: 46c83acd-6e43-42aa-875f-ae24b09a7fee
doc-type: video
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 0%

---

# Création de filtres avec des caractères génériques basés sur l’utilisateur

Dans cette vidéo, vous apprendrez à :

* Comprendre pourquoi utiliser des caractères génériques
* Création d’un filtre à l’aide d’un caractère générique (générique) basé sur l’utilisateur

>[!VIDEO](https://video.tv.adobe.com/v/336810/?quality=12&learn=on)

>[!TIP]
>
>Utilisez la source et le nom du champ Affectation Utilisateurs &quot; ID lors de la création de filtres qui examinent les informations d’affectation de tâche ou de problème.  Cette option examine tous les utilisateurs affectés à la tâche ou au problème, et pas seulement le &quot;propriétaire&quot; ou la personne désignée Principale.

>[!TIP]
>
>Utilisez $$USER.ID (au lieu de votre nom) même lors de la création de filtres pour vous-même. Ainsi, si quelqu’un voit un filtre que vous exécutez et dit &quot;Partagez-le avec moi&quot;, le filtre est déjà configuré pour que chaque personne qui l’utilise voit ses propres informations.

>[!TIP]
>
>Vous devez toujours utiliser le qualificateur de filtre Egal lorsque vous utilisez des caractères génériques basés sur l’utilisateur.

## Activité

Vous avez un peu de temps supplémentaire cette semaine, donc vous voulez voir s’il y a quelqu’un dans votre équipe qui pourrait avoir besoin d’aide pour ses devoirs. Créez un filtre de tâche pour trouver les tâches qui doivent être effectuées cette semaine et qui n’ont pas été terminées.

## Réponse

Vous êtes génial pour aider vos coéquipiers ! Avec le filtre configuré comme l’image ci-dessous, vous trouverez les tâches suivantes :

* Cela n’a pas été effectué (ce qui signifie qu’il n’y a pas de [!UICONTROL Terminer] statut ou état qui correspond à [!UICONTROL Terminer]);
* qui se trouvent dans des projets avec une [!UICONTROL Actuel] statut (après tout, vous ne souhaitez pas trouver de tâches pour les projets qui n’ont pas encore été lancés) ;
* qui sont affectés à une personne de votre équipe d’accueil, conformément aux paramètres définis par l’équipe Workfront ;
* Et dont la date d’achèvement est fixée à un certain temps cette semaine (cette règle a utilisé le filtre de date prédéfini pour définir &quot;cette semaine&quot;).

![Image de l’écran de création d’un filtre de tâche avec un caractère générique basé sur l’utilisateur](assets/user-wildcard-exercise-answer.png)

Vous devrez peut-être ajouter d’autres filtres si vous avez besoin de limiter un peu plus la liste. Par exemple, vous pouvez ajouter une règle de filtrage qui examine un programme ou un portefeuille spécifique issu de votre équipe.
