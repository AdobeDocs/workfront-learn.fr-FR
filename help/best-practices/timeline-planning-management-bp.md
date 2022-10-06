---
title: Bonne pratique - Planification et gestion du planning
description: Examinez les recommandations relatives aux bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation des chronologies de projet dans Workfront.
feature: Get Started with Workfront
role: Admin, Leader, User
level: Beginner
kt: 10929
exl-id: 8c18746d-e23a-44d0-b1e3-ebf5ba8d022f
source-git-commit: 444f059d3cc26d8e3074a7145bc5419407c786cf
workflow-type: tm+mt
source-wordcount: '1110'
ht-degree: 0%

---

# Bonne pratique - Planification et gestion du planning

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques en matière de planification et de gestion des chronologies

* Tous les projets terminés doivent avoir un état qui indique qu’ils sont terminés.

* Lors de la copie d’un projet, définissez l’état du nouveau projet sur Planification.

* Demandez aux utilisateurs d’enregistrer le temps réel passé sur les tâches afin que vous puissiez comparer les heures réelles aux heures planifiées.

* Lorsque cela est possible, utilisez les durées de tâche et les prédécesseurs pour créer et mettre à jour une chronologie de projet, plutôt que de sélectionner des dates de début et de fin spécifiques.

* Demandez aux utilisateurs de mettre à jour chaque jour l’état de leur tâche, le pourcentage de tâches terminées et les heures réelles (ou selon un calendrier défini chaque semaine).

* Définissez l’état du projet sur Planification lors de la mise à jour du plan du projet afin d’empêcher l’envoi automatique de notifications au fur et à mesure des modifications.

* Supprimez les utilisateurs de l’équipe de projet qui ne se voient pas attribuer de travail dans le projet.

* Placez Mesures du projet en haut du menu du panneau de gauche pour les utilisateurs qui utilisent Workfront principalement pour afficher les données.


</br>
</br>


## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Tous les projets terminés doivent avoir un état qui indique qu’ils sont terminés.


**Voici pourquoi**

Assurez-vous que tous les projets terminés ont un état Terminé (ou équivalent) pour que votre instance Workfront reste propre et à jour. En actualisant les statuts des projets et en les excluant, les utilisateurs peuvent facilement identifier le travail déjà accompli afin de se concentrer sur les principales priorités. Elle garantit également la précision des données de rapport sur les projets, les tâches, les ressources, etc.


</br>
</br>

**Bonne pratique**

Lors de la copie d’un projet, définissez l’état du nouveau projet sur Planification.

**Voici pourquoi**

L’état Planification (ou équivalent) empêche les notifications Workfront relatives aux affectations, aux modifications de la chronologie, etc., de sortir avant que le projet ne soit prêt. Lors de la copie d’un projet, une boîte de dialogue avec les options du projet s’affiche. modifiez l’état ici, tout en réglant d’autres options afin que les données ne soient pas copiées du projet d’origine vers la version copiée.

</br>
</br>

**Bonne pratique**

Demandez aux utilisateurs d’enregistrer le temps réel passé sur les tâches afin que vous puissiez comparer les heures réelles aux heures planifiées.


**Voici pourquoi**

Connaître la durée du travail permet de mettre à jour les modèles de projet pour une meilleure précision dans la planification des projets futurs. Cela signifie également que les estimations des ressources, à l’aide des outils de gestion des ressources de Workfront, sont plus précises.

</br>
</br>

**Bonne pratique**

Lorsque cela est possible, utilisez les durées de tâche et les prédécesseurs pour créer et mettre à jour une chronologie de projet, plutôt que de sélectionner des dates de début et de fin spécifiques.

**Voici pourquoi**

L’utilisation de durées et de prédécesseurs conjointement avec des contraintes de tâche flexibles (Dès que possible et Aussi tard que possible) permet de modifier automatiquement la date de la chronologie en cascade dans le plan de projet. Par exemple, lorsqu’une durée de tâche augmente d’un jour, cela modifie la date d’achèvement prévue de la tâche, qui à son tour modifie la date d’achèvement des tâches suivantes.

Si vous sélectionnez des dates de début et d’achèvement spécifiques pour les tâches, la contrainte de tâche devient une contrainte qui verrouille la date (Doit commencer le, Doit se terminer le, Dates fixes), ce qui signifie que vous devez mettre manuellement à jour certaines dates de la chronologie.

</br>
</br>


**Bonne pratique**

Demandez aux utilisateurs de mettre à jour chaque jour l’état de leur tâche, le pourcentage de tâches terminées et les heures réelles (ou selon un calendrier défini chaque semaine).

**Voici pourquoi**

Les rapports dans Workfront sont uniquement aussi précis que les données saisies dans Workfront. Lorsque les informations indiquant la progression du travail (comme l’état et le pourcentage de réalisation) ne sont pas mises à jour régulièrement, les rapports indiquant la progression du travail ne sont pas précis. La mise à jour quotidienne garantit la plus grande précision des données de création de rapports en temps réel.


L’état de la tâche est également utilisé pour informer les utilisateurs du moment où les travaux précédents ont été terminés et où leurs nouvelles tâches peuvent commencer. Lorsque l’état de la tâche n’est pas modifié pour refléter la progression réelle de l’élément de travail, Workfront ne peut pas envoyer les notifications appropriées.

</br>
</br>

**Bonne pratique**

Définissez l’état du projet sur Planification lors de la mise à jour du plan du projet afin d’empêcher l’envoi automatique de notifications au fur et à mesure des modifications.

**Voici pourquoi**

Les modifications du plan de projet peuvent générer plusieurs notifications à mesure que des affectations de tâche, des dates de début et d’achèvement planifiées et d’autres paramètres sont modifiés. Cela peut perturber les utilisateurs et créer de la confusion concernant les affectations, les échéances, etc. corrects.

L’état Planification indique à Workfront de ne pas envoyer de notifications sur le projet aux membres de l’équipe du projet (utilisateurs auxquels sont affectés des tâches/problèmes ou autres ayant accès au projet), car le plan du projet est toujours en cours de développement ou le projet n’est tout simplement pas encore prêt à être mis en ligne. Une fois les modifications terminées, redéfinissez l’état du projet sur Actuel et des notifications seront envoyées. Suivez ce processus pour réduire le nombre de notifications que les utilisateurs reçoivent.

</br>
</br>

**Bonne pratique**

Supprimez les utilisateurs de l’équipe de projet qui ne se voient pas attribuer de travail dans le projet.


**Voici pourquoi**

Lorsque vous affectez à une personne une tâche ou un problème sur un projet, cela l’ajoute à la liste de l’équipe du projet dans les sections Planification et Personnes du projet. Cependant, ils restent sur la liste de l’équipe de projet même si vous les avez supprimés de l’affectation. Cela peut prêter à confusion pour l’utilisateur, car l’équipe du projet reçoit des notifications sur l’activité du projet et voit le projet dans la liste Projets actifs.


En outre, les membres de l’équipe de projet obtiennent des autorisations sur le projet et ses tâches, problèmes et documents. Les utilisateurs peuvent ainsi avoir accès aux éléments de Workfront dont ils n’ont pas besoin ou qu’ils ne doivent pas avoir.

</br>
</br>

**Bonne pratique**

Placez Mesures du projet en haut du menu du panneau de gauche pour les utilisateurs qui utilisent Workfront principalement pour afficher les données.

**Voici pourquoi**

La plupart des dirigeants, cadres et autres utilisateurs qui ne gèrent pas de projets ou ne remplissent pas les affectations de tâche apprécieraient de voir ce niveau de mesures de projet lorsqu’ils ouvrent un projet pour la première fois. Utilisez un modèle de mise en page pour déplacer les mesures du projet dans la partie supérieure du menu du panneau de gauche sur une page de projet afin que les utilisateurs puissent y accéder plus facilement et plus facilement.
