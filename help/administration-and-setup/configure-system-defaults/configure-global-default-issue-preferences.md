---
title: Configuration des préférences de problème par défaut globales
description: Découvrez comment définir les préférences de problème pour les problèmes convertis, les dates réelles et l’accès aux problèmes.
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
ht-degree: 0%

---

# Configuration des préférences de problème par défaut globales

Plusieurs paramètres à l’échelle du système définissent les valeurs par défaut du comportement des problèmes dans certaines circonstances. [!DNL Workfront].

Il est recommandé de conserver les valeurs par défaut globales telles quelles et de permettre aux chefs de projet d’effectuer les ajustements dont ils ont besoin au niveau du projet ou dans les modèles de projet.

Les préférences de problème globales peuvent être ajustées, mais il est recommandé de [!DNL Workfront] conseiller discute des paramètres nécessaires aux workflows, aux processus et aux besoins en matière de création de rapports de votre entreprise. Votre consultant peut également vous aider à comprendre ce qui se passera si certains paramètres sont modifiés.

Les préférences de problème permettent aux administrateurs système de contrôler les options lorsque des problèmes sont convertis en tâches ou en projets, le mode de calcul des dates réelles et l’accès au projet lorsque des problèmes sont affectés. Regardons où se trouvent ces paramètres. [!DNL Workfront].

## Préférences de publication converties

Ces paramètres contrôlent ce qui se passe lorsqu’un problème est converti en tâche ou en projet dans [!DNL Workfront].

![[!UICONTROL Tâches et problèmes] fenêtre Préférences avec [!UICONTROL Problèmes] section mise en surbrillance](assets/admin-fund-issue-prefs-converting.png)

1. Cliquez sur **[!UICONTROL Configuration]** dans le **[!UICONTROL Menu Principal]**.
1. Développez l’objet **[!UICONTROL Préférences du projet]** dans le panneau du menu de gauche.
1. Sélectionner **[!UICONTROL Tâches et problèmes]**.
1. Faites défiler l’écran jusqu’à **[!UICONTROL Problèmes]** .
1. Cliquez sur les options de votre choix.
1. Enregistrez lorsque vous avez terminé.

Examinons les options de cette section afin que vous puissiez choisir les options appropriées à votre organisation.

* **[!UICONTROL Mettre automatiquement à jour l’état Problème résolvable lorsque l’état de l’objet de résolution change]**

  Ce paramètre permet de mettre en corrélation la résolution du problème d’origine avec la résolution du nouvel objet (tâche ou projet).

  Lorsque ce paramètre est activé (coché), vous pouvez créer des états de problème personnalisés ayant la même clé d’état qu’une tâche ou un état de projet. Lorsque la tâche ou le projet (l’objet résolvable) est défini sur l’état personnalisé, la modification s’affiche également sur l’état du problème.

  Lorsque cette option est désactivée, l’état de l’objet de résolution est défini automatiquement sur l’état par défaut, plutôt que sur l’état personnalisé.

  Pour que ce paramètre ait un effet, le paramètre[!UICONTROL Conserver le problème d’origine et lier sa résolution à la tâche]&quot; doit être sélectionnée.

* **[!UICONTROL Conserver le problème d’origine et lier la résolution à la tâche/au projet]**

  Lorsque le problème est converti, cette instruction indique : [!DNL Workfront] pour conserver les problèmes d’origine. L’état du problème change à mesure que l’état de la tâche ou du projet est modifié. Une fois que la tâche ou le projet est marqué comme terminé, le problème est marqué comme résolu.

  Si cette option n’est pas cochée, le problème d’origine est supprimé et seule la tâche ou le projet converti est conservé.

  Ce paramètre affecte la création de rapports sur les problèmes initialement consignés dans un projet ou qui passent par une [!DNL Workfront] file d’attente des demandes.

* **[!UICONTROL Autoriser les contacts Principal à accéder à la tâche/au projet]**

  Cela permet à la personne qui a créé le problème d’origine d’accéder à la tâche ou au projet créé lors de la conversion. Ils peuvent examiner le travail, faire des mises à jour et rester informés de ses progrès.

* **[!UICONTROL Autoriser la modification de ces paramètres pendant la conversion]**

  Lorsque cette option est sélectionnée, les paramètres par défaut de &quot;[!UICONTROL Conserver le problème d’origine]&quot; et &quot;[!UICONTROL Autoriser les contacts Principal]&quot; peut être modifié par l’utilisateur qui convertit le problème. Si vous souhaitez que les valeurs par défaut restent inchangées, désélectionnez cette option.

<!---
learn more URLs
Configure system-wide task and issue preferences
Issue statuses
Create and customize system-wide statuses
--->

## Préférences des dates réelles

Plusieurs types de dates sont utilisés dans l’ensemble de [!DNL Workfront]. Les dates réelles sont un &quot;horodatage&quot; qui [!DNL Workfront] génère lorsque certaines modifications d’état se produisent.

Le [!UICONTROL Date de début réelle] l’horodatage est créé lorsque l’état du problème passe de Nouveau à un autre état. Le [!UICONTROL Date d’achèvement réelle] l’horodatage est défini lorsque l’état du problème passe à un état indiquant qu’il est fermé.

Il est important de noter que cette préférence contrôle les paramètres de date réels pour les tâches et les problèmes.

![[!UICONTROL Tâches et problèmes] fenêtre Préférences avec [!UICONTROL Dates réelles] section mise en surbrillance](assets/admin-fund-issue-prefs-actual-dates.png)

1. Cliquez sur **[!UICONTROL Configuration]** dans le **[!UICONTROL Menu Principal]**.
1. Développez l’objet **[!UICONTROL Préférences du projet]** dans le panneau du menu de gauche.
1. Sélectionner **[!UICONTROL Tâches et problèmes]**.
1. Faites défiler l’écran jusqu’à **[!UICONTROL Dates réelles]** .
1. Sélectionnez l’option de votre choix pour le **[!UICONTROL Date de début réelle]** — [!UICONTROL Maintenant] (date et heure actuelles) ou [!UICONTROL Date de début planifiée] (la variable [!UICONTROL Date de début réelle] correspond à la date de début définie dans les détails du problème).
1. Sélectionnez maintenant l’option pour le **[!UICONTROL Date d’achèvement réelle]** — [!UICONTROL Maintenant] (date et heure actuelles) ou [!UICONTROL Date d’achèvement prévue] (la variable [!UICONTROL Date de début réelle] correspond à la date définie dans les détails du problème).
1. Enregistrez lorsque vous avez terminé.


<!---
learn more URLs
Definitions for the project, task, and issue dates within Workfront
Configure system-wide task and issue preferences
--->

## Accès aux problèmes

Le [!UICONTROL Accès] les paramètres pour les problèmes contrôlent l’accès accordé à un utilisateur lorsqu’un problème lui est assigné dans Workfront. Ces paramètres contrôlent l’accès au problème lui-même, en plus de l’accès au projet auquel le problème est associé.

Avant de modifier ces paramètres, discutez avec vous des besoins en termes de processus ou de processus. [!DNL Workfront] consultants et votre équipe de gouvernance interne.

![[!UICONTROL Tâches et problèmes] fenêtre Préférences avec [!UICONTROL Lorsqu’une personne est affectée à un problème] section mise en surbrillance](assets/admin-fund-issue-prefs-access-1.png)

1. Cliquez sur **[!UICONTROL Configuration]** dans le **[!UICONTROL Menu Principal]**.
1. Développez l’objet **[!UICONTROL Préférences du projet]** dans le panneau du menu de gauche.
1. Sélectionner **[!UICONTROL Tâches et problèmes]**.
1. Faites défiler l’écran jusqu’à **[!UICONTROL Accès]** et recherchez le[!UICONTROL Lorsqu’une personne est affectée à un problème]&quot;.
1. Définissez l’accès au partage pour le problème lui-même — [!UICONTROL Affichage], [!UICONTROL Contribution]ou [!UICONTROL Gérer]. [!DNL Workfront] recommande de laisser les options avancées telles quelles.
1. Cochez la case si la personne désignée pour le problème doit également avoir accès au projet.
1. Sélectionnez ensuite l’accès au partage pour le projet — [!UICONTROL Affichage], [!UICONTROL Contribution]ou [!UICONTROL Gérer]. Lorsque vous définissez la variable [!UICONTROL Options avancées], gardez à l’esprit les workflows de votre entreprise et les besoins en matière d’accès.
1. Enregistrez lorsque vous avez terminé.

![[!UICONTROL Accès] affichage de la fenêtre [!UICONTROL Contribution] options](assets/admin-fund-issue-prefs-access-2.png)

<!---
learn more URLs
Configure system-wide task and issue preferences
Grant access to issues
--->
