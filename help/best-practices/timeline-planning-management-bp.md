---
title: Bonne pratique – Planification et gestion de la chronologie
description: Examinez les recommandations relatives aux bonnes pratiques des expertes et experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation des chronologies de projet dans Workfront.
feature: Get Started with Workfront
role: Admin, Leader, User
level: Beginner
jira: KT-10929
exl-id: 8c18746d-e23a-44d0-b1e3-ebf5ba8d022f
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '1110'
ht-degree: 100%

---

# Bonne pratique – Planification et gestion de la chronologie

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques pour ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La zone « Pourquoi s’agit-il de bonnes pratiques ? » qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques en matière de planification et de gestion des chronologies

* Tous les projets terminés doivent avoir un statut qui indique qu’ils sont terminés.

* Lors de la copie d’un projet, définissez le statut du nouveau projet sur Planification.

* Demandez aux utilisateurs et aux utilisatrices d’enregistrer le temps réel passé sur les tâches afin que vous puissiez comparer les heures réelles au nombre d’heures prévues.

* Lorsque cela est possible, utilisez les durées de tâche et les prédécesseurs pour créer et mettre à jour une chronologie de projet, plutôt que de sélectionner des dates de début et de fin spécifiques.

* Demandez aux utilisateurs et aux utilisatrices de mettre à jour quotidiennement le statut de leur tâche, le pourcentage de tâches terminées et les heures effectives (ou selon un calendrier défini chaque semaine).

* Définissez le statut du projet sur Planification lors de la mise à jour du plan du projet afin d’empêcher l’envoi automatique de notifications au fur et à mesure des modifications.

* Supprimez les utilisateurs et les utilisatrices de l’équipe de projet qui ne se voient pas attribuer de travail dans le projet.

* Placez les mesures du projet dans la partie supérieure du menu du panneau de gauche pour les utilisateurs et les utilisatrices qui utilisent Workfront principalement pour afficher les données.


</br>
</br>


## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Tous les projets terminés doivent avoir un statut qui indique qu’ils sont terminés.


**Voici pourquoi**

En veillant à ce que tous les projets terminés aient un statut Terminé (ou équivalent), votre instance Workfront reste claire et à jour. En gardant les statuts des projets à jour et en les clôturant, les utilisateurs et les utilisatrices peuvent facilement savoir quel travail a déjà été accompli et se concentrer sur les priorités actives. Cela garantit également la précision des données de rapport sur les projets, les tâches, les ressources, etc.


</br>
</br>

**Bonne pratique**

Lors de la copie d’un projet, définissez le statut du nouveau projet sur Planification.

**Voici pourquoi**

Le statut Planification (ou un statut équivalent) empêche les notifications Workfront concernant les affectations, les changements de calendrier, etc. d’être envoyées avant que le projet ne soit prêt. Lors de la copie d’un projet, une boîte de dialogue avec les options du projet s’affiche. Modifiez le statut ici, tout en réglant d’autres options afin que les données ne soient pas copiées du projet d’origine vers la version copiée.

</br>
</br>

**Bonne pratique**

Demandez aux utilisateurs et aux utilisatrices d’enregistrer le temps réel passé sur les tâches afin que vous puissiez comparer les heures réelles au nombre d’heures prévues.


**Voici pourquoi**

En connaissant la durée d’une tâche, vous pouvez mettre à jour les modèles de projet pour une meilleure précision dans la planification des projets futurs. Cela signifie également que les estimations des ressources, à l’aide des outils de gestion des ressources de Workfront, sont plus précises.

</br>
</br>

**Bonne pratique**

Lorsque cela est possible, utilisez les durées de tâche et les prédécesseurs pour créer et mettre à jour une chronologie de projet, plutôt que de sélectionner des dates de début et de fin spécifiques.

**Voici pourquoi**

L’utilisation des durées et des prédécesseurs en conjonction avec des contraintes de tâches flexibles (le plus tôt possible et le plus tard possible) permet de modifier automatiquement les dates du calendrier en « cascade » dans le plan du projet. Par exemple, lorsqu’une durée de tâche augmente d’un jour, cela modifie la date d’achèvement prévue de la tâche, qui à son tour modifie la date d’achèvement des tâches suivantes.

Si vous sélectionnez des dates de début et d’achèvement spécifiques pour les tâches, la contrainte de tâche devient une contrainte qui verrouille la date (Doit commencer le, Doit se terminer le, Dates fixes), ce qui signifie que vous devez mettre manuellement à jour certaines dates de la chronologie.

</br>
</br>


**Bonne pratique**

Demandez aux utilisateurs et aux utilisatrices de mettre à jour quotidiennement le statut de leur tâche, le pourcentage de tâches terminées et les heures effectives (ou selon un calendrier défini chaque semaine).

**Voici pourquoi**

Les rapports dans Workfront ne peuvent pas être plus précis que les données saisies dans Workfront. Lorsque les informations relatives à l’avancement du travail, telles que le statut et le pourcentage terminé, ne sont pas mises à jour régulièrement, les rapports sur l’avancement du travail ne sont pas exacts. La mise à jour quotidienne garantit la plus grande précision des données de création de rapports en temps réel.


Le statut des tâches est également utilisé pour indiquer aux utilisateurs et aux utilisatrices quand leur travail antérieur a été achevé et que leurs nouvelles tâches peuvent commencer. Lorsque le statut de la tâche n’est pas modifié pour refléter la progression réelle de l’élément de travail, Workfront ne peut pas envoyer les notifications appropriées.

</br>
</br>

**Bonne pratique**

Définissez le statut du projet sur Planification lors de la mise à jour du plan du projet afin d’empêcher l’envoi automatique de notifications au fur et à mesure des modifications.

**Voici pourquoi**

Les modifications du plan de projet peuvent générer plusieurs notifications au fur et à mesure que les affectations de tâches, les dates de début et d’achèvement prévues et d’autres paramètres sont modifiés. Cela peut perturber les personnes et créer de la confusion concernant l’exactitude des affectations, des échéances, etc.

Le statut Planification indique à Workfront de ne pas envoyer de notifications sur le projet aux personnes membres de l’équipe de projet (personnes assignées à des tâches/problèmes ou autres personnes ayant accès au projet) parce que le plan du projet est encore en cours d’élaboration ou que le projet n’est tout simplement pas encore prêt à être activé. Une fois les modifications terminées, le statut du projet redevient « Actif » et les notifications sont envoyées. Suivez ce processus pour réduire le nombre de notifications que les personnes reçoivent.

</br>
</br>

**Bonne pratique**

Supprimez les utilisateurs et les utilisatrices de l’équipe de projet qui ne se voient pas attribuer de travail dans le projet.


**Voici pourquoi**

Lorsque vous assignez une tâche ou un problème à une personne dans le cadre d’un projet, la personne est ajoutée à la liste de l’équipe du projet dans les sections Planification et Personnes du projet. Cependant, la personne reste dans la liste de l’équipe de projet même si vous l’avez retirée de la tâche. Cela peut prêter à confusion pour la personne, car l’équipe du projet reçoit des notifications sur l’activité du projet et voit le projet dans la liste Projets sur lesquels je travaille.


En outre, les personnes membres de l’équipe de projet ont accès au projet et à ses tâches, problèmes et documents. Les personnes peuvent ainsi avoir accès aux éléments de Workfront dont elles n’ont pas besoin ou qu’elles ne doivent pas avoir.

</br>
</br>

**Bonne pratique**

Placez les mesures du projet dans la partie supérieure du menu du panneau de gauche pour les utilisateurs et les utilisatrices qui utilisent Workfront principalement pour afficher les données.

**Voici pourquoi**

La plupart des personnes dirigeantes ou cadres et des autres utilisateurs et utilisatrices qui ne gèrent pas de projets ou ne remplissent pas d’affectations de tâches apprécieraient de voir ce niveau de mesures de projet lorsqu’ils ouvrent un projet pour la première fois. Utilisez un modèle de disposition pour déplacer les mesures du projet dans la partie supérieure du menu du panneau de gauche sur une page de projet afin que les personnes puissent les voir et y accéder plus facilement.
