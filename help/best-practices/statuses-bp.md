---
title: 'Bonne pratique : statuts'
description: Examinez les recommandations relatives aux bonnes pratiques des expertes et experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation des statuts Workfront.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10926
exl-id: c3a4fe42-339c-4063-ad67-045868bbc6b1
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 100%

---

# Bonne pratique : statuts

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques pour ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La zone « Pourquoi s’agit-il de bonnes pratiques ? » qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux statuts

* Lorsque vous renommez Workfront avec des statuts par défaut, conservez le même objectif initial que celui-ci.

* Si vous créez un statut de projet personnalisé pour Annulé, associez le statut à Inactif.

* Conservez au minimum les statuts personnalisés globaux.

* N’utilisez pas les statuts du projet à la place des tâches pour indiquer la progression d’un projet.


</br>
</br>



## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Lorsque vous renommez Workfront avec des statuts par défaut, conservez le même objectif initial que celui-ci.



**Voici pourquoi**

Certaines actions dans Workfront sont déclenchées par des statuts par défaut du système. La modification de l’intention d’un statut peut avoir une incidence sur le comportement de Workfront dans certaines situations, affecter les rapports, etc.



Par exemple, le statut de tâche par défaut Complet indique à Workfront de modifier le pourcentage terminé d’une tâche à 100 %. Le statut Complet permet également à Workfront de savoir que le travail sur les tâches dépendantes peut commencer. Si vous avez modifié le nom du statut sur En attente pour indiquer qu’une tâche est suspendue, Workfront pense que la tâche est terminée et démarre les étapes suivantes du projet.

</br>
</br>



**Bonne pratique**

Si vous créez un statut de projet personnalisé pour Annulé, associez le statut à Inactif.



**Voici pourquoi**

Si vous associez le statut Annulé à Terminé, vous ne pouvez pas utiliser le statut pour annuler un projet à moins que toutes les tâches soient marquées comme terminées et que tous les problèmes soient résolus. Mais si vous associez Annulé à Inactif, vous pouvez annuler le projet sans rien modifier dans l’historique.


</br>
</br>

**Bonne pratique**

Conservez au minimum les statuts personnalisés globaux.



**Voici pourquoi**

Simplicité rime avec efficacité. En plus de créer de la maintenance inutile, un trop grand nombre de statuts personnalisés crée de la confusion, en particulier lorsque l’on travaille sur des projets interfonctionnels. Il est préférable de personnaliser les statuts en fonction du groupe auquel ils s’adressent. L’environnement Workfront reste ainsi plus propre et mieux positionné pour être étendu à d’autres groupes à l’avenir. Collaborez avec votre conseil de gouvernance/de supervision et les parties prenantes pour identifier les statuts que les groupes de votre organisation doivent utiliser.


</br>
</br>

**Bonne pratique**

N’utilisez pas les statuts du projet à la place des tâches pour indiquer la progression d’un projet.



**Voici pourquoi**

Les statuts des projets doivent être simples et indiquer des phases de progression importantes, comme Planification, En cours, Terminé, etc. Les tâches, leur statut et leur pourcentage terminé vous indiquent le statut d’avancement général du projet. Ces indicateurs au niveau des tâches sont repris dans le pourcentage terminé du projet, le statut du projet et le statut de la progression du projet, qui sont tous de meilleurs indicateurs plus précis dans la progression du projet que le statut d’avancement du projet. En outre, ces informations au niveau de la tâche fournissent de meilleurs rapports sur les projets.
