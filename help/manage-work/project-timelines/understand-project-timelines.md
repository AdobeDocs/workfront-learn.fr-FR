---
title: Explorer la chronologie des projets dans Workfront
description: Découvrez comment affecter des tâches, utiliser les graphiques de Gantt et les fonctionnalités de chemin critique, surveiller les projets par le biais de vues, planifier les tâches efficacement et appliquer des contraintes pour une planification de projet optimale.
activity: use
feature: Work Management
thumbnail: 335213.jpeg
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
last-substantial-update: '2024-11-01T00:00:00.000Z'
recommendations: noDisplay,catalog
jira: KT-8953
exl-id: ba993197-9f84-4fc0-86cc-cf849c889f56
doc-type: video
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
autotag-review: '2026-05-06T14:48:54.364Z'
source-git-commit: df1a568be7d42893910e1c0afde8bbba213a7803
workflow-type: tm+mt
source-wordcount: 700
ht-degree: 74%

---

# Explorer la chronologie des projets dans Workfront

Ce que vous apprendrez :

* Obtenez une vue d’ensemble de la planification et de la gestion de projets à l’aide de Workfront. Découvrez comment les tâches parents regroupent plusieurs sous-tâches, qui sont affectées à des fonctions et ultérieurement aux personnes possédant les compétences nécessaires. Les prédécesseurs indiquent les relations séquentielles entre les tâches, tandis que les tâches sans prédécesseurs peuvent être effectuées en parallèle. Le graphique de Gantt offre une chronologie visuelle. La fonctionnalité de chemin critique met en évidence les tâches qui peuvent retarder le projet si elles prennent du retard.
* Différentes vues dans Workfront, telles que la vue standard pour la planification et la vue de statut pour la surveillance de la progression, qui inclut des indicateurs de progression, des commentaires, des documents, des problèmes, des approbations, le chemin critique et les jalons. L’activité récente peut être suivie pour afficher les mises à jour et les notes.
* La planification peut être effectuée à partir d’une date de début ou d’achèvement, Workfront calculant les dates correspondantes en fonction de la durée des tâches et des prédécesseurs. La vidéo recommande d’effectuer la planification à partir d’une date de début pour les dates d’achèvement critiques afin de laisser une certaine marge. Les contraintes de tâche, telles que « le plus tôt possible » et « le plus tard possible », sont également abordées, en montrant comment elles affectent la planification des tâches. Vous pouvez créer des vues personnalisées pour afficher les contraintes de tâche.

>[!VIDEO](https://video.tv.adobe.com/v/3435837/?captions=fre_fr&quality=12&learn=on&enablevpops=1)

>[!IMPORTANT]
>
>Pour obtenir une explication plus complète des types de durée et des contraintes de tâche, voir [Comprendre et gérer les types de durée et les contraintes de tâche](/help/manage-work/intermediate-projects/understand-and-manage-duration-types-and-task-constraints.md).

## Points clés à retenir

* **Gestion et affectation des tâches :** les tâches parents regroupent plusieurs sous-tâches, qui sont affectées à des fonctions et ultérieurement à des utilisateurs possédant les compétences nécessaires. &#x200B; prédécesseurs indiquent les relations séquentielles, tandis que les tâches sans prédécesseurs peuvent être effectuées en parallèle. 
* **Graphique Gantt et chemin critique :** le graphique Gantt fournit une chronologie visuelle du projet, et la fonction Chemin critique met en évidence les tâches qui peuvent retarder le projet en cas de glissement. &#x200B;
* **Vues et surveillance :** différentes vues dans Workfront, telles que la vue standard pour la planification et la vue de statut pour la surveillance, incluent des indicateurs de progression, des commentaires, des documents, des problèmes, des approbations, un chemin critique et des jalons. L’activité récente peut également être suivie. 
* **Options de planification :** les projets peuvent être planifiés à partir d’une date de début ou d’achèvement, Workfront calculant les dates correspondantes en fonction de la durée des tâches et des prédécesseurs. &#x200B; Planification à partir d’une date de début est recommandée pour les dates d’achèvement critiques afin de permettre une certaine marge. 
* **Contraintes de tâche :** les contraintes de tâche telles que « le plus tôt possible » et « le plus tard possible » affectent la planification des tâches. &#x200B; La modification du mode de planification après la création du projet peut avoir un impact sur les contraintes de tâche et les dates prévues. &#x200B; vues personnalisées peuvent être créées pour afficher les contraintes de tâche. 


## Modifier ou ne pas modifier les dates dans les chronologies de votre projet...

| Avantages de modifier des dates | Inconvénients de modifier des dates | Avantages de ne pas modifier des dates | Inconvénients de ne pas modifier des dates |
|---------------------------|---------------------------|---------------------------|---------------------------|
| <ul><li>Réduction du stress/communication d’attentes actualisées aux utilisateurs et utilisatrices._L’équipe créative a besoin de repères clairs pour savoir où elle en est._</li><li>Allocation précise des ressources, en particulier dans l’équilibreur de charge de travail</li><li>Utilisation des rapports d’entrée de journal (ou de la durée du projet) pour indiquer les modifications de dates</li><li>Utilisation de la condition pour indiquer si le projet est hors de portée</li><li>Possibilité d’ajouter un formulaire personnalisé (ou utiliser des problèmes) pour suivre les modifications : pourquoi elles ont été reportées, par qui, pendant combien de temps</li></ul> | <ul></li><li>Données trompeuses car les rapports ne reflètent pas le véritable état</li><li>Fausse perception de la progression : illusion que tout est sur la bonne voie</li><li>Promotion d’une culture qui consiste à toujours modifier la chronologie au lieu de s’attaquer aux causes profondes</li><li>Perte de confiance des parties prenantes/perception de l’équipe quant au respect des délais </li></ul> | <ul></li><li>Représentation précise de la chronologie du projet : les données peuvent être utilisées pour l’analyse et pour raconter une histoire claire de ce qui s’est passé.</li><li>Option permettant de modifier la durée ou d’ajouter un décalage au prédécesseur à la place</li><li>Identification facile des améliorations de processus pour la planification future des projets/gestion des risques</li><li>Option permettant d’exploiter les niveaux de référence pour capturer le plan de projet d’origine et l’utiliser comme comparaison</li><li>Si les ressources nécessaires pour effectuer ce travail ne sont pas disponibles, ou si cela ne peut pas être appliqué à l’ensemble du projet, il est préférable de ne pas modifier les dates.</li></ul> | <ul></li><li>Confusion et/ou frustration du personnel : abondance de tâches « en retard » malgré le fait qu’il vient tout juste d’être averti.</li><li>Les ressources ont été efficacement allouées pour correspondre au plan initial, mais elles sont maintenant surchargées de travail en retard.</li><li>La chronologie du projet ne peut pas être utilisée pour communiquer clairement les mises à jour aux parties prenantes.</li></ul> |


## Tutoriels recommandés sur cette rubrique

* [Suivre la progression à l’aide du pourcentage achevé et du statut de progression](/help/manage-work/project-timelines/track-work-progress-from-the-project-timeline.md)
* [Comprendre les types de dates et le statut de la progression](/help/manage-work/project-timelines/understand-task-dates-and-progress-status.md)
* [Types de durée de Principal et contraintes de tâche](/help/manage-work/intermediate-projects/understand-and-manage-duration-types-and-task-constraints.md)


