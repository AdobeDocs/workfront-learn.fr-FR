---
title: Créer des filtres avec des caractères génériques basés sur l’utilisateur ou l’utilisatrice
description: Découvrez comment utiliser les caractères génériques basés sur l’utilisateur ou l’utilisatrice et créer un filtre basé sur la personne connectée.
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
source-git-commit: 88c2161e897f23587ccc1d0e867b6f8961927a0f
workflow-type: tm+mt
source-wordcount: '357'
ht-degree: 48%

---

# Créer des filtres avec des caractères génériques basés sur l’utilisateur ou l’utilisatrice

Dans cette vidéo, vous apprendrez à :

* Comprendre pourquoi utiliser des caractères génériques
* Créer un filtre avec un caractère générique basé sur l’utilisateur ou l’utilisatrice

>[!VIDEO](https://video.tv.adobe.com/v/336810/?quality=12&learn=on)

>[!TIP]
>
>Utilisez la source et le nom du champ Utilisateurs de l’affectation >> ID lorsque vous créez des filtres qui examinent les informations relatives à l’affectation des tâches ou des problèmes.  Cette option examine tous les   les utilisateurs affectés à la tâche ou à l’événement, pas seulement le « propriétaire » ou la personne désignée principale.

>[!TIP]
>
>Utilisez l’identifiant $$USER.ID (au lieu de votre nom), même lorsque vous créez des filtres pour vous-même. Ainsi, si quelqu’un voit un filtre que vous exécutez et dit « Partagez-le avec moi », le filtre est déjà configuré afin que chaque personne qui l’utilise voie ses propres informations.

>[!TIP]
>
>Vous devez toujours utiliser le qualificatif de filtre Égal lorsque vous utilisez des caractères génériques basés sur l’utilisateur ou l’utilisatrice.


## Création de filtres avec des activités de caractères génériques basées sur l’utilisateur

Pour télécharger un fichier PDF de cette page, [cliquez ici](/help/assets/create-filters-with-user-based-wildcards-activities.pdf).

### Activité 1

Vous avez un peu de temps supplémentaire cette semaine, alors vous voulez voir s&#39;il y a quelqu&#39;un dans votre équipe qui pourrait utiliser de l&#39;aide pour ses affectations. Créez un filtre de tâches pour rechercher les tâches qui sont dues cette semaine et qui ne sont pas terminées.

### Réponse 1

Vous êtes génial pour aider vos coéquipiers ! Une fois le filtre configuré comme l’image ci-dessous, vous trouverez les tâches suivantes :

* qui n&#39;ont pas été terminés (ce qui signifie qu&#39;ils n&#39;ont pas un statut [!UICONTROL Terminé] ou un statut équivalent à [!UICONTROL Terminé]) ;
* qui se trouvent dans des projets avec un statut [!UICONTROL Actuel] (après tout, vous ne souhaitez pas rechercher des tâches pour des projets qui ne sont pas encore lancés) ;
* Les tâches qui sont affectées à une personne de votre équipe d’origine, tel que défini par les paramètres d’équipe Workfront ;
* Et dont la date de fin est fixée à un moment de cette semaine (cette règle a utilisé le filtre de date prédéfini pour définir « cette semaine »).

![Une image de l’écran de création d’un filtre de tâches avec un caractère générique basé sur l’utilisateur ou l’utilisatrice](assets/user-wildcard-exercise-answer.png)

Vous devrez peut-être ajouter des filtres supplémentaires pour restreindre un peu plus la liste. Par exemple, vous voudrez peut-être ajouter une règle de filtrage qui concerne un programme ou un portfolio spécifique avec lesquels votre équipe travaille.
