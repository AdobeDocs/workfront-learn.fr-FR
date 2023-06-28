---
title: Afficher le délai d’expiration affecte les calendriers du projet
description: Découvrez ce qui arrive à la chronologie d’un projet lorsque le paramètre de délai d’expiration est activé et désactivé.
feature: Resource Management
type: Tutorial
role: Leader, User
level: Intermediate, Experienced
activity: use
team: Technical Marketing
jira: KT-10180
exl-id: 0f79dd8d-b7ce-4ee9-b211-23c8ed5d497c
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '524'
ht-degree: 4%

---

# Comment le délai d’expiration affecte-t-il les calendriers du projet

Si le temps de pause d’un utilisateur affecté dépend d’un paramètre de projet appelé [!UICONTROL Heure de désactivation de l’utilisateur]. Ce paramètre détermine si le temps de pause de la Principale personne désignée de la tâche ajuste les dates prévues pour cette tâche sur le projet.

Regardons ce qui se passe avec la chronologie d’un projet lorsque chacun des paramètres est sélectionné : C[!UICONTROL Tenir compte du temps d’arrêt des utilisateurs dans les durées de tâche] ou [!UICONTROL Ignorer le temps d’arrêt des utilisateurs dans les durées de tâche].

![Paramètres de délai d’expiration de l’utilisateur](assets/toapt_01.png)

## Prendre en compte les congés de l&#39;utilisateur dans la durée des tâches

Cette option est le paramètre par défaut de Workfront.

Dans cet exemple, la personne désignée Principale pour la tâche a des jours de congé marqué sur son calendrier personnel.

![calendrier personnel](assets/toapt_02.png)

Le chef de projet souhaite affecter cette personne à une tâche dont les dates planifiées chevauchent les heures de congé de l’utilisateur.

![tâche de projet avec des dates](assets/toapt_03.png)

Lorsque cet utilisateur est affecté à la tâche, les dates prévues s’ajustent automatiquement. La date d’achèvement prévue de la tâche a désormais été prolongée de plusieurs jours pour s’adapter au temps de congé de l’utilisateur. Il est important de noter que cette modification peut affecter les dates prévues d’autres tâches du projet et, éventuellement, la date d’achèvement prévue du projet.

![tâche de projet avec échéance](assets/toapt_04.png)

## [!UICONTROL Ignorer les congés de l&#39;utilisateur dans la durée des tâches]

Avec cette option, les dates prévues de la tâche restent comme initialement prévues, même si la personne désignée Principale a un temps de congé pendant la durée de la tâche.

Le membre de l&#39;équipe a des jours de congé marqués sur son calendrier.

![calendrier pto avec dates marquées](assets/toapt_05.png)

Le chef de projet leur attribue une tâche qui chevauche le temps de pause. Une fois l’utilisateur affecté, les dates planifiées de la tâche restent telles que prévues initialement.

![modification des dates des tâches du projet](assets/toapt_06.png)

Pour garantir que le travail est effectué à temps, il peut s’avérer utile d’affecter une autre personne pouvant travailler sur la tâche pendant que la personne désignée d’origine est absente du bureau.

## Ajuster le paramètre au niveau du projet

Pour modifier le paramètre de désactivation de l’heure de l’utilisateur sur un projet :

* Ouvrez le projet en cliquant sur son nom dans Workfront.

* Sélectionner [!UICONTROL Modifier] dans le menu à 3 points de l’en-tête de la page, à droite du nom du projet.

* Faites défiler l’écran jusqu’à [!UICONTROL Paramètres du projet] et recherchez les [!UICONTROL Heure de désactivation de l’utilisateur] champ .

* Sélectionnez l’option que vous souhaitez appliquer à ce projet — [!UICONTROL Tenir compte du temps d’arrêt de l’utilisateur dans les durées de tâche] ou I[!UICONTROL Ignorer le temps d’arrêt de l’utilisateur dans les durées de tâche].

* Cliquez sur le bouton [!UICONTROL Enregistrer] dans le coin supérieur droit de la fenêtre.

![Prendre en compte les congés de l&#39;utilisateur dans la durée des tâches](assets/toapt_07.png)


**Remarque**: Ce paramètre n’est pas disponible lorsque vous sélectionnez [!UICONTROL Détails du projet] dans le menu du panneau de gauche de la page du projet.

Un paramètre global pour ce paramètre existe dans les préférences du projet dans la variable [!UICONTROL Configuration] . Ce paramètre est géré par votre administrateur système. Les administrateurs de groupe peuvent être en mesure d’ajuster ce paramètre pour les groupes qu’ils gèrent.

Workfront recommande que le paramètre soit défini de la manière dont vous souhaitez que la plupart de vos projets prennent en charge le temps libre de votre entreprise.

Le paramètre peut également être intégré à des modèles de projet, par le biais des détails du modèle.
