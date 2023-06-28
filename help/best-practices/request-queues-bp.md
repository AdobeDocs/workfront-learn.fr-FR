---
title: Bonne pratique - Files d’attente des demandes
description: Examinez les recommandations relatives aux bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation des files d’attente de demandes Workfront.
feature: Resource Management
role: Admin, Leader, User
level: Beginner
jira: KT-10921
exl-id: dbb961f9-c207-49f1-9545-ec127f983c15
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '1480'
ht-degree: 0%

---

# Bonne pratique - Files d’attente des demandes

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux requêtes de file d’attente

* Incluez une description pour chaque élément d’une file d’attente de demandes : le projet de file d’attente de demandes, les groupes de rubriques, les rubriques de file d’attente et les règles de routage.

* Créez un état de projet appelé &quot;File d’attente des demandes&quot; ou &quot;Opérationnel&quot; qui correspond à &quot;Actuel&quot; pour distinguer les projets de la file d’attente des demandes des autres projets.

* Si vous prévoyez d’utiliser les approbations de problèmes avec les demandes envoyées via une file d’attente, créez un état de problème appelé Refusé.

* Attribuez des formulaires personnalisés &quot;universels&quot; pour demander des files d’attente afin de capturer autant de données homogènes à l’échelle de l’entreprise que possible.

* Évitez de partager les files d’attente de requête avec &quot;tout le monde&quot;. Configurez les paramètres de détails de la file d’attente afin que les utilisateurs ne voient que les files d’attente correspondant à leurs besoins.

* Créez et affectez un tableau de bord contenant les rapports de file d’attente des demandes afin que les gestionnaires de trafic, les administrateurs système ou les utilisateurs affectés puissent travailler directement sur les problèmes.

* Utilisez les modèles de mise en page pour supprimer les options de configuration de la file d’attente des demandes du menu du panneau de gauche des projets pour les utilisateurs qui n’ont pas besoin de créer des files d’attente.

* Créez une file d’attente de requêtes de l’administrateur système pour que les utilisateurs puissent poser des questions liées à Workfront, effectuer des requêtes concernant les configurations système, planifier une nouvelle formation des utilisateurs, etc.

* Les files d’attente de demande d’audit de manière régulière afin d’identifier et d’annuler le partage des files d’attente qui ne sont pas utilisées.

* Utilisez les groupes de rubriques pour organiser plus de 10 rubriques de file d’attente dans une file d’attente de requêtes afin de créer des listes plus courtes et plus faciles à gérer.

* Contrôlez le nombre total de files d’attente de demandes disponibles pour les utilisateurs en ventilant une file d’attente de demandes à l’aide de groupes de rubriques et de rubriques de file d’attente, plutôt que de créer plusieurs files d’attente.

* Configurez les règles de routage pour chaque rubrique de file d’attente. Configurez au minimum une règle de routage par défaut.

* Tirez parti des groupes de rubriques et des rubriques de file d’attente lorsque le routage sélectif est nécessaire.

* Itinéraires les demandes à une équipe, plutôt qu’à un individu.


</br>
</br>


## Pourquoi ces bonnes pratiques ?


**Bonne pratique**

Incluez une description pour chaque élément d’une file d’attente de demandes : le projet de file d’attente de demandes, les groupes de rubriques, les rubriques de file d’attente et les règles de routage.

**Voici pourquoi**

Les descriptions permettent aux administrateurs de groupe, aux futurs administrateurs système ou à d’autres personnes qui gèrent des files d’attente de savoir exactement ce que fait chaque élément de la file d’attente de requêtes.

Les informations de description s’affichent également lorsque vous placez le pointeur de la souris sur l’icône d’informations du champ dans la nouvelle fenêtre de requête.

La description n’a pas besoin d’être longue, mais d’un bref commentaire sur l’objectif ou l’utilisation de l’élément.

</br>
</br>

**Bonne pratique**

Créez un état de projet appelé &quot;File d’attente des demandes&quot; ou &quot;Opérationnel&quot; qui correspond à &quot;Actuel&quot; pour distinguer les projets de la file d’attente des demandes des autres projets.

**Voici pourquoi**

Une file d’attente de requêtes &quot;réside&quot; dans un projet et doit être dans un état égal à Actuel pour que la file d’attente soit principale.

Afin de distinguer une requête des projets de travail réels avec un état &quot;Actuel&quot;, créez un état à utiliser uniquement sur les files d’attente de requête appelées &quot;File d’attente de requête&quot; ou &quot;Opérationnelle&quot;. Vous pouvez ensuite utiliser cet état pour exclure ou inclure des projets de file d’attente de demandes lors de l’écriture de rapports.

</br>
</br>

**Bonne pratique**

Créez un état de problème appelé &quot;Refusé&quot; lors de l’utilisation des approbations de problèmes et définissez l’option Si Refusé sur le statut &quot;Refusé&quot;.

**Voici pourquoi**

En utilisant le statut &quot;Refusé&quot;, il est clair que la demande a été révisée et rejetée.

</br>
</br>

**Bonne pratique**

Attribuez des formulaires personnalisés &quot;universels&quot; pour demander des files d’attente afin de capturer autant de données homogènes à l’échelle de l’entreprise que possible.

**Voici pourquoi**

Un formulaire personnalisé &quot;universel&quot; rassemble les informations standard nécessaires à la demande, quel que soit le type de demande en cours d’envoi.

La présence d’un formulaire personnalisé &quot;universel&quot; permet de réduire le nombre de formulaires personnalisés que vous devez créer et gérer. Elle garantit également que toutes les demandes collectent les mêmes informations de la même manière, ce qui permet d’obtenir des rapports et une analyse des données cohérents.

</br>
</br>

**Bonne pratique**

Évitez de partager les files d’attente de requête avec &quot;tout le monde&quot;.  Configurez les paramètres de détails de la file d’attente afin que les utilisateurs ne voient que les files d’attente correspondant à leurs besoins.

**Voici pourquoi**

Dans la plupart des cas, une file d’attente de demandes ne doit être partagée qu’avec un certain groupe de personnes, comme une équipe, un fournisseur, des clients, etc. Lorsque les demandeurs ne voient que ce dont ils ont besoin dans la liste de file d’attente des demandes, cela facilite la recherche et la navigation.

</br>
</br>


**Bonne pratique**

Créez et affectez un tableau de bord contenant les rapports de file d’attente des demandes afin que les gestionnaires de trafic, les administrateurs système ou les utilisateurs affectés puissent travailler directement sur les problèmes.

**Voici pourquoi**

L’accès rapide et facile aux utilisateurs aux requêtes entrantes signifie que le travail ne se perd pas dans le mélange.

</br>
</br>

**Bonne pratique**

Utilisez les modèles de mise en page pour supprimer les options de configuration de la file d’attente des demandes du menu du panneau de gauche des projets pour les utilisateurs qui n’ont pas besoin de créer des files d’attente.


**Voici pourquoi**

Cela permet de s’assurer que toutes les files d’attente de demande suivent le processus approprié pour leur création (tel qu’elles ont été examinées par un comité de gouvernance) et sont correctement configurées par un administrateur système ou de groupe.

En outre, cela permet de conserver la liste des files d’attente organisée et de se concentrer sur les types de requêtes dont votre organisation a besoin.

</br>
</br>

**Bonne pratique**

Créez une file d’attente de requêtes de l’administrateur système pour que les utilisateurs puissent poser des questions liées à Workfront, effectuer des requêtes concernant les configurations système, planifier une nouvelle formation des utilisateurs, etc.

**Voici pourquoi**

Cet emplacement centralisé permet aux utilisateurs d’envoyer des questions et aux administrateurs de rassembler, surveiller et répondre aux problèmes liés à Workfront.

En outre, ces informations peuvent servir à montrer l’autorité en ce qui concerne le temps, les efforts et la valeur du rôle d’administrateur du système et à justifier l’existence d’un administrateur système supplémentaire.

</br>
</br>


**Bonne pratique**

Les files d’attente de demande d’audit de manière régulière afin d’identifier et d’annuler le partage des files d’attente qui ne sont pas utilisées.

**Voici pourquoi**

Un audit régulier des configurations et des éléments de votre système Adobe Workfront vous permet de le garder dénué de tout encombrement et d’éléments inutiles. Si une file d’attente n’est plus utilisée ou surveillée, assurez-vous que les utilisateurs ne peuvent plus y accéder afin que les demandes de travail ne tombent pas dans un vide.

</br>
</br>


**Bonne pratique**

Utilisez les groupes de rubriques pour organiser plus de 10 rubriques de file d’attente dans une file d’attente de requêtes afin de créer des listes plus courtes et plus faciles à gérer.

**Voici pourquoi**

Les groupes de rubriques augmentent l’adoption par les utilisateurs et créent moins de confusion en réduisant la liste initiale des options à sélectionner. Cela permet aux utilisateurs de trouver facilement ce qu’ils recherchent sans les écraser lorsqu’ils tentent d’envoyer une requête.

En outre, elle permet aux administrateurs système et/ou aux gestionnaires de file d’attente de demander une opportunité de créer un chemin de navigation fluide pour les utilisateurs et une meilleure manière d’organiser et de générer des rapports sur les types de requêtes en cours d’envoi.

</br>
</br>

**Bonne pratique**

Contrôlez le nombre total de files d’attente de demandes disponibles pour les utilisateurs en ventilant une file d’attente de demandes à l’aide de groupes de rubriques et de rubriques de file d’attente, plutôt que de créer plusieurs files d’attente.

**Voici pourquoi**

Trop de files d’attente de requêtes rend difficile pour les utilisateurs de trouver ce dont ils ont besoin.

Moins de files d’attente aident également les coordinateurs de trafic, les administrateurs système ou d’autres personnes à gérer les files d’attente, ce qui leur permet de trouver plus rapidement les informations dont ils ont besoin, sans avoir à accéder à plusieurs projets de file d’attente de demandes.

Créez plusieurs files d’attente si un accès différent est nécessaire pour différentes files d’attente de requête ou si la consolidation des files d’attente peut dérouter les utilisateurs.

</br>
</br>

**Bonne pratique**

Configurez les règles de routage pour chaque rubrique de file d’attente. Configurez au minimum une règle de routage par défaut.

**Voici pourquoi**

Les règles de routage garantissent qu’une personne se verra toujours attribuer la requête entrante afin que le travail ne tombe pas dans les mailles du filet.

</br>
</br>

**Bonne pratique**

Tirez parti des groupes de rubriques et des rubriques de file d’attente lorsque le routage sélectif est nécessaire.

**Voici pourquoi**

Les règles de routage ne peuvent pas être appliquées aux champs d’un formulaire personnalisé. Ainsi, si différents types de requêtes doivent être acheminés vers différentes équipes/individus, faites de chaque type de requête son propre groupe de rubriques/rubrique de file d’attente afin que le travail puisse être correctement acheminé.

</br>
</br>

**Bonne pratique**

Itinéraires les demandes à une équipe, plutôt qu’à un individu.

**Voici pourquoi**

Lorsque des demandes sont envoyées à l’équipe, elles donnent une visibilité à l’ensemble de l’équipe sur les demandes en cours et sur les tâches à venir qui pourraient entraîner. Tout le monde peut consulter la page Équipe pour connaître les nouveaux éléments ou suivre les nouveautés d’un rapport sur un tableau de bord.

Elle garantit également que lorsque le gestionnaire de trafic ou toute autre personne chargée de contrôler ou d’affecter les requêtes entrantes n’est pas disponible, une sauvegarde est automatiquement disponible et a accès aux informations de la requête.
