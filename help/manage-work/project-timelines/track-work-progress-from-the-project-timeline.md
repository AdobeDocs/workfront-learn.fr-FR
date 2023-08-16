---
title: Suivi de la progression à partir de la chronologie du projet
description: Découvrez comment suivre la progression du travail à partir de la chronologie du projet dans [!DNL  Workfront] en utilisant le pourcentage terminé, l’état, les affectations ou les contraintes.
activity: use
team: Technical Marketing
feature: Work Management
thumbnail: track-work-progress-from-the-project-timeline.jpeg
type: Tutorial
role: User
last-substantial-update: 2023-08-16T00:00:00Z
level: Intermediate
jira: KT-10150
exl-id: c8793f49-24b8-48cc-af84-5239234ead0e
source-git-commit: e25a7c0119567c068504edcb8c3ddd29622d52c5
workflow-type: tm+mt
source-wordcount: '417'
ht-degree: 0%

---

# Suivi de la progression à partir de la chronologie du projet

Assurez-vous que les tâches progressent de la manière dont elles doivent respecter les délais du projet. Lorsque vous analysez les [!UICONTROL Tâche] liste, il existe plusieurs fonctionnalités dans [!DNL  Workfront] qui vous aident à surveiller la progression et l’état du travail.

## Pourcentage d’achèvement

Le pourcentage d&#39;achèvement de chaque tâche de travail est parfois utilisé pour évaluer l&#39;avancement du travail. Il est important de noter...que ce champ doit être ajusté manuellement, car c&#39;est l&#39;estimation par la personne désignée de leur distance.

>[!TIP]
>
>Bien que le pourcentage d’achèvement des tâches de travail doive être mis à jour manuellement, le pourcentage d’achèvement d’une tâche parent est calculé par Workfront en fonction du pourcentage d’achèvement et de la durée ou des heures planifiées de chaque tâche enfant. Cela signifie que vous obtiendrez une précision de pourcentage plus précise si vous divisez des tâches volumineuses en sous-tâches plus petites.


![Liste des tâches du projet présentant un [!UICONTROL Pourcentage terminé] column](assets/planner-fund-task-percent-complete.png)

Il y a trois fois où le pourcentage terminé change automatiquement :

* Lorsque la tâche [!UICONTROL État] est définie sur Terminé, le pourcentage terminé passe à 100.
* Si la tâche [!UICONTROL État] revient à Nouveau, le pourcentage terminé est réinitialisé à 0.
* Dans une tâche parent lorsque le pourcentage d’achèvement d’une tâche enfant change.

## Statut

Inclure la variable [!UICONTROL État] dans une colonne [!UICONTROL Affichage] pour voir rapidement quelles tâches ont été démarrées, celles en cours et celles qui sont terminées. Vous pouvez même configurer une mise en forme conditionnelle dans une [!UICONTROL Affichage] pour coder chaque état, ce qui facilite le déchiffrage des informations.

## Affectations de tâche

Lorsque vous passez en revue le projet, passez en revue les affectations de tâche. Peut-être que le travail a pris du retard parce que personne n&#39;a été affecté à la tâche. Ou peut-être que la personne affectée n&#39;avait pas les compétences adéquates pour terminer le travail. Ajoutez plus de personnes à une tâche ou réaffectez-lui des tâches pour vous assurer que le travail est terminé.

## Contrainte de tâche

Parfois les contraintes de tâche sont modifiées et vous ne le réalisez pas. Les contraintes peuvent avoir une incidence sur le comportement de la chronologie. Vous devez donc vous assurer qu’elles sont définies comme vous le souhaitez.

![Liste des tâches du projet présentant la colonne de contrainte des tâches](assets/planner-fund-task-constraint.png)

Créez une vue personnalisée qui inclut le [!UICONTROL Contrainte de tâche] pour afficher ces informations dans la liste des tâches. Si vous avez planifié le projet à partir d’une date de début, vous souhaitez que vos tâches comportent la variable [!UICONTROL Dès Que Possible] ([!UICONTROL ASAP]).

Pour plus d’informations sur les contraintes de tâche, voir [Comprendre et gérer les types de durée et les contraintes de tâche](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-work/intermediate-projects/understand-and-manage-duration-types-and-task-constraints.html).
