---
title: Bonne pratique - États
description: Examinez les recommandations relatives aux bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation des statuts Workfront.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10926
exl-id: c3a4fe42-339c-4063-ad67-045868bbc6b1
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '584'
ht-degree: 0%

---

# Bonne pratique - États

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux états

* Lorsque vous renommez Workfront avec des états par défaut, conservez le même objectif d’origine que celui-ci.

* Si vous créez un état de projet personnalisé pour Annulé, associez le statut à Mort.

* Conservez au minimum les états personnalisés globaux.

* N’utilisez pas les états du projet à la place des tâches pour indiquer la progression d’un projet.


</br>
</br>



## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Lorsque vous renommez Workfront avec des états par défaut, conservez le même objectif d’origine que celui-ci.



**Voici pourquoi**

Certaines actions dans Workfront sont déclenchées par les états par défaut du système. La modification de l’intention d’un état peut avoir une incidence sur le comportement de Workfront dans certaines situations, affecter les rapports, etc.



Par exemple, l’état de la tâche par défaut Terminé indique à Workfront de modifier le pourcentage d’achèvement d’une tâche à 100 %. L’état Terminé indique également à Workfront que le travail sur les tâches dépendantes peut commencer. Si vous avez modifié le nom de l’état en Attente pour indiquer qu’une tâche est suspendue, Workfront pense que la tâche est terminée et démarre les étapes suivantes du projet.

</br>
</br>



**Bonne pratique**

Si vous créez un état de projet personnalisé pour Annulé, associez le statut à Mort.



**Voici pourquoi**

Si vous associez Annuler à Terminé, vous ne pouvez pas utiliser l’état pour annuler un projet tant que toutes les tâches ne sont pas marquées comme étant terminées et que tous les problèmes ne sont pas résolus. Mais si vous associez Annulé à Mort, vous pouvez annuler le projet sans rien modifier dans l’historique.


</br>
</br>

**Bonne pratique**

Conservez au minimum les états personnalisés globaux.



**Voici pourquoi**

Moins c&#39;est plus. Outre la création d’une maintenance inutile, trop d’états personnalisés créent de la confusion, en particulier lorsque vous travaillez sur des projets interfonctionnels. Définissez plutôt des états personnalisés spécifiques au groupe. Votre environnement Workfront reste ainsi plus propre et mieux positionné pour une extension vers d’autres groupes à l’avenir. Collaborez avec votre comité de gouvernance/de supervision et les parties prenantes pour identifier les états que les groupes de votre organisation doivent utiliser.


</br>
</br>

**Bonne pratique**

N’utilisez pas les états du projet à la place des tâches pour indiquer la progression d’un projet.



**Voici pourquoi**

Restez simple d’indiquer les états du projet pour indiquer les phases de progression de haut niveau, telles que Planification, Actuel, Terminé, etc. Laissez les tâches, les états des tâches et le pourcentage de tâches terminés vous indiquer comment le travail progresse globalement sur le projet. Ces indicateurs au niveau de la tâche s’affichent dans le pourcentage de réalisation du projet, la condition du projet et l’état d’avancement du projet, qui sont tous des indicateurs meilleurs et plus précis de la progression du projet qu’un état du projet. En outre, ces informations au niveau de la tâche fournissent de meilleurs rapports sur les projets.
