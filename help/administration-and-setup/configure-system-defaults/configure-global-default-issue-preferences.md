---
title: Configurer les préférences globales par défaut des problèmes
description: Apprenez à définir les préférences des problèmes convertis, des dates réelles et de l’accès aux problèmes.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Intermediate, Experienced
jira: KT-10018
exl-id: 9924e479-c300-47b4-8e40-241ebb2435cf
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '885'
ht-degree: 100%

---

# Configurer les préférences globales par défaut des problèmes

Plusieurs paramètres à l’échelle du système définissent les valeurs par défaut du comportement des problèmes dans certaines circonstances dans [!DNL Workfront].

Il est recommandé de conserver les valeurs par défaut globales telles quelles et permettre aux chefs et cheffes de projet d’effectuer les ajustements dont ils ou elles ont besoin au niveau du projet ou dans les modèles de projet.

Les préférences globales des problèmes peuvent être ajustées, mais il est recommandé de définir avec votre consultant ou votre consultante [!DNL Workfront] quels sont les paramètres nécessaires pour les workflows, les processus et les besoins en reporting de votre organisation. Votre consultant ou votre consultante peut également vous aider à comprendre ce qui se passera si certains paramètres sont modifiés.

Les préférences relatives aux problèmes permettent aux administrateurs et administratrices système de contrôler les options de conversion des problèmes en tâches ou en projets, le mode de calcul des dates réelles et les personnes qui ont accès au projet lorsque des problèmes sont attribués. Regardons où se trouvent ces paramètres dans [!DNL Workfront].

## Préférences de problèmes converties

Ces paramètres contrôlent ce qui se passe lorsqu’un problème est converti en tâche ou en projet dans [!DNL Workfront].

Fenêtre des préférences ![[!UICONTROL Tâches et problèmes] avec la section [!UICONTROL Problèmes] mise en surbrillance](assets/admin-fund-issue-prefs-converting.png).

1. Cliquez sur **[!UICONTROL Configuration]** dans le **[!UICONTROL menu principal]**.
1. Développez la section **[!UICONTROL Préférences projet]** dans le panneau de menu gauche.
1. Sélectionnez **[!UICONTROL Tâches et problèmes]**.
1. Faites défiler jusqu’à la section **[!UICONTROL Problèmes]**.
1. Cliquez sur les options de votre choix.
1. Enregistrez lorsque vous avez terminé.

Examinons les options de cette section afin que vous puissiez choisir celles appropriées pour votre organisation.

* **[!UICONTROL Mettre à jour automatiquement le statut des problèmes pouvant être résolus lorsque le statut de l’objet de résolution change]**

  Cette configuration vous permet de mettre en corrélation la résolution du problème d’origine avec la résolution du nouvel objet (tâche ou projet).

  Avec cette configuration activée (cochée), vous pouvez créer des statuts de problèmes personnalisés qui ont la même clé de statut qu’un statut de tâche ou de projet. Lorsque la tâche ou le projet (l’objet résolvable) est configuré sur le statut personnalisé, la modification s’affiche également sur le statut du problème.

  Lorsque cette option est désactivée, le statut de l’objet de résolution est automatiquement configuré sur le statut par défaut plutôt que sur le statut personnalisé.

  Pour que cette configuration soit effective, l&#39;option « [!UICONTROL Conserver le problème d’origine et lier sa résolution à la tâche] » doit être sélectionnée.

* **[!UICONTROL Conserver le problème d’origine et lier sa résolution à la tâche/projet]**

  Lorsque le problème est converti, cela indique à [!DNL Workfront] qu&#39;il faut conserver les problèmes d’origine. Le statut du problème change en fonction du statut de la tâche ou du projet. Une fois que la tâche ou le projet est marqué comme terminé, le problème est marqué comme résolu.

  Si cette option n’est pas cochée, le problème d’origine est supprimé et seule la tâche ou le projet converti est conservé.

  Cette configuration affecte la création de rapports sur les problèmes initialement consignés dans un projet ou qui passent par une file d’attente des demandes [!DNL Workfront].

* **[!UICONTROL Autoriser l’interlocuteur principal ou l&#39;interlocutrice principale à accéder à la tâche/projet]**

  Cela permet à la personne qui a créé le problème d’origine d’accéder à la tâche ou au projet créé lors de la conversion. Celle-ci peut réviser le travail, faire des mises à jour et rester informée de sa progression.

* **[!UICONTROL Autoriser la modification de ces paramètres pendant la conversion]**

  Lorsque cette option est sélectionnée, cela signifie que les paramètres par défaut pour « [!UICONTROL Garder le problème d&#39;origine] » et « [!UICONTROL Autoriser le contact principal] » peuvent être modifiés par l&#39;utilisateur ou l’utilisatrice qui convertit le problème. Si vous souhaitez que les valeurs par défaut restent inchangées, désélectionnez cette option.

<!---
learn more URLs
Configure system-wide task and issue preferences
Issue statuses
Create and customize system-wide statuses
--->

## Préférences des dates réelles

Plusieurs types de dates sont utilisés dans [!DNL Workfront]. Les dates réelles sont un « horodatage » généré par [!DNL Workfront] lorsque certains statuts sont modifiés.

L’horodatage [!UICONTROL Date de début effectif] est créé lorsque le statut du problème passe de Nouveau à un autre statut. L’horodatage de la [!UICONTROL Date d’achèvement réelle] est utilisé quand le statut du problème passe au statut indiquant qu’il est fermé.

Il est important de noter que cette préférence contrôle les paramètres de date réelle pour les tâches et les problèmes.

La fenêtre de préférences ![[!UICONTROL Tâches et problèmes] avec la section [!UICONTROL Dates réelles] mise en surbrillance](assets/admin-fund-issue-prefs-actual-dates.png)

1. Cliquez sur **[!UICONTROL Configuration]** dans le **[!UICONTROL menu principal]**.
1. Développez la section **[!UICONTROL Préférences projet]** dans le panneau de menu gauche.
1. Sélectionnez **[!UICONTROL Tâches et problèmes]**.
1. Faites défiler jusqu’à la section **[!UICONTROL Dates réelles]**.
1. Sélectionnez l’option de votre choix pour la **[!UICONTROL Date de début effectif]** - [!UICONTROL Maintenant] (date et heure actuelles) ou [!UICONTROL Date de début planifiée] (la [!UICONTROL Date de début effectif] correspond à la date de début définie dans les détails du problème).
1. Sélectionnez maintenant l’option pour la **[!UICONTROL Date d’achèvement effectif]** - [!UICONTROL Maintenant] (date et heure actuelles) ou [!UICONTROL Date d’achèvement prévue] (la variable [!UICONTROL Date de début effectif] correspond à la date définie dans les détails du problème).
1. Enregistrez lorsque vous avez terminé.


<!---
learn more URLs
Definitions for the project, task, and issue dates within Workfront
Configure system-wide task and issue preferences
--->

## Accès aux problèmes

Les paramètres d’[!UICONTROL accès] pour les problèmes permettent de contrôler l’accès accordé à un utilisateur ou une utilisatrice lors de l’affectation d’un problème dans Workfront. Ces paramètres contrôlent l’accès au problème lui-même, en plus de l’accès au projet auquel le problème est associé.

Avant de modifier ces paramètres, discutez de vos éventuels besoins de processus ou de workflow avec vos consultants et consultantes [!DNL Workfront] et votre équipe de gouvernance interne.

Fenêtre des préférences des ![[!UICONTROL Tâches et problèmes] avec la section [!UICONTROL Lorsqu’une personne est affectée à un PROBLÈME] mise en surbrillance](assets/admin-fund-issue-prefs-access-1.png)

1. Cliquez sur **[!UICONTROL Configuration]** dans le **[!UICONTROL menu principal]**.
1. Développez la section **[!UICONTROL Préférences projet]** dans le panneau de menu gauche.
1. Sélectionnez **[!UICONTROL Tâches et problèmes]**.
1. Faites défiler l’écran jusqu’à la section **[!UICONTROL Accès]** et recherchez l’option « [!UICONTROL Lorsqu’une personne est affectée à un PROBLÈME] ».
1. Définissez le type d’accès pour le problème lui-même : [!UICONTROL Voir], [!UICONTROL Contribuer], ou [!UICONTROL Gérer]. [!DNL Workfront] recommande de laisser les options avancées telles quelles.
1. Cochez la case si la personne désignée pour le problème doit également avoir accès au projet.
1. Sélectionnez ensuite le type d’accès pour le projet : [!UICONTROL Voir], [!UICONTROL Contribuer], ou [!UICONTROL Gérer]. Lorsque vous définissez les [!UICONTROL Options avancées], tenez compte des workflows et des besoins d’accès de votre organisation.
1. Enregistrez lorsque vous avez terminé.

Fenêtre ![[!UICONTROL Accès] montrant les options [!UICONTROL Contribuer]](assets/admin-fund-issue-prefs-access-2.png)

<!---
learn more URLs
Configure system-wide task and issue preferences
Grant access to issues
--->
