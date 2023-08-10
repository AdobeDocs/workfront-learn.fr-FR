---
title: Convertir un problème/une requête en tâche
description: Découvrez comment convertir des problèmes en d’autres tâches .
activity: use
team: Technical Marketing
feature: Work Management
thumbnail: convert-issues-to-other-work-items.jpeg
type: Tutorial
role: User
level: Intermediate
jira: KT-10069
exl-id: 1fd4d862-e44b-4c50-9663-70e727f6e9b7
source-git-commit: 060ceb14d274e8b2ad080c1f58290a2c5769e007
workflow-type: tm+mt
source-wordcount: '485'
ht-degree: 0%

---

# Convertir un problème/une requête en tâche

Un problème peut être suffisamment important pour que le temps et l’effort pour le résoudre doivent être pris en compte dans le calendrier du projet et affecter les ressources appropriées. Dans ce cas, le problème peut être converti en tâche.

![Une image de la [!UICONTROL Convertir en tâche] option d’un problème dans [!UICONTROL Workfront].](assets/15-convert-issue-to-task-menu-option.png)

1. Accédez au [!UICONTROL Problèmes] section du projet ou de la tâche sur laquelle le problème est connecté. Ou recherchez le problème dans un rapport auquel vous avez accès.
1. Cliquez sur le nom du problème pour l’ouvrir.
1. Dans le menu à 3 points situé à droite du nom du problème, sélectionnez **[!UICONTROL Convertir en tâche]**.
1. Remplissez la variable [!UICONTROL Convertir en tâche] formulaire. Commencez par donner un nom et une description à la nouvelle tâche.
1. Si la nouvelle tâche doit faire partie d’un autre projet, modifiez la variable [!UICONTROL Projet de destination] nom.
1. Dans le [!UICONTROL Options] , cochez les cases pour conserver le problème d’origine, autoriser l’accès à la nouvelle tâche et conserver la date d’achèvement. Suivez le workflow de votre entreprise lorsque vous effectuez ces sélections.
1. Joignez un formulaire personnalisé si vous souhaitez transférer des données de formulaire personnalisées du problème à la tâche. (Tous les champs qui existent à la fois dans le formulaire d’émission et dans le formulaire de tâche seront automatiquement transférés vers le formulaire de tâche.)
1. Cliquez sur **[!UICONTROL Convertir en tâche]** à la fin.

![Une image de la [!UICONTROL Convertir en tâche] forme d’un problème dans [!UICONTROL Workfront].](assets/16-convert-to-task-options.png)

Selon le [!DNL Workfront] paramètres système, vous pouvez modifier les paramètres de la section Options ou non lors de la conversion de la tâche. Ces options affectent le problème d’origine et la nouvelle tâche.

* **Conserver le problème d’origine et lier sa résolution à cette tâche** conserve le problème d’origine et les informations connexes (heures, documents, etc.). Lorsque cette option est sélectionnée, lorsque la tâche est terminée, le problème est marqué comme résolu. Si cette option est **not** sélectionné, le problème d’origine sera supprimé lors de la création de la tâche. Cela peut avoir une incidence sur la manière dont votre entreprise effectue le suivi des problèmes et génère des rapports sur ces problèmes.
* La variable **Autoriser (nom de l’utilisateur) à accéder à cette tâche** permet à la personne ayant créé le problème d’accéder à cette nouvelle tâche.
* La variable **Conserver la date d’achèvement prévue du problème** permet de conserver la date d’achèvement prévue déjà définie sur le problème. Cela définit la contrainte de tâche sur [!UICONTROL Terminer au plus tard]. Si la case est décochée, les dates de la tâche sont définies comme si une nouvelle tâche était créée dans le projet.

La nouvelle tâche est placée au bas de la liste des tâches de votre projet. Déplacez la tâche vers l’emplacement souhaité, affectez un utilisateur ou une équipe à la tâche, ajoutez les heures et la durée planifiées, etc.

>[!NOTE]
>
>Vous ne pouvez pas ajouter de problèmes à la chronologie du projet, car ils représentent un &quot;travail non planifié&quot;. La chronologie du projet est destinée aux &quot;travaux planifiés&quot;, c’est-à-dire aux tâches.


