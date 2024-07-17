---
title: Bonne pratique - Files d’attente de demandes
description: Découvrez les recommandations relatives aux bonnes pratiques des expertes et experts Adobe Workfront concernant la configuration, la gestion et l’utilisation des files d’attente des demandes Workfront.
feature: Resource Management
role: Admin, Leader, User
level: Beginner
jira: KT-10921
exl-id: dbb961f9-c207-49f1-9545-ec127f983c15
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '1482'
ht-degree: 100%

---

# Bonne pratique - Files d’attente de demandes

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques pour ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La zone « Pourquoi s’agit-il de bonnes pratiques ? » qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques en matière de files d’attente

* Incluez une description de chaque élément d’une file d’attente de demandes : le projet de file d’attente de demandes, les groupes de rubriques, les rubriques de file d’attente et les règles de routage.

* Créez un statut de projet nommé « File d’attente » ou « Opérationnel » qui équivaut à « En cours » pour distinguer les projets de la file d’attente de demandes des autres projets.

* Si vous prévoyez d’utiliser les approbations de problèmes avec des demandes soumises via une file d’attente, créez un statut de problème nommé Rejeté.

* Attribuez des formulaires personnalisés « universels » aux files d’attente de demandes afin de capturer autant de données pertinentes que possible dans toute l’entreprise.

* Évitez de partager les files d’attente de demandes avec « tout le monde ». Paramétrez les détails de la file d’attente pour que les utilisateurs et les utilisatrices ne voient que les files d’attente correspondant à leurs besoins.

* Créez et affectez un tableau de bord contenant des rapports sur la file d’attente des demandes afin que les responsables du trafic, les administrateurs et administratrices système ou les utilisateurs et utilisatrices affectés puissent travailler directement sur les problèmes.

* Utilisez les modèles de disposition pour supprimer les options de configuration de la file d’attente des demandes dans le menu du panneau de gauche des projets pour les utilisateurs et utilisatrices qui n’ont pas besoin de créer des files d’attente.

* Créez une file d’attente des demandes de l’équipe d’administration système afin que les utilisateurs et utilisatrices puissent poser des questions relatives à Workfront, faire des demandes concernant la configuration du système, planifier la formation des nouveaux arrivants, etc.

* Auditez régulièrement les files d’attente de demandes afin d’identifier et d’annuler le partage des files d’attente qui ne sont pas utilisées.

* Utilisez les groupes de sujets pour organiser plus de 10 sujets dans une file d’attente de demandes afin de créer des listes plus courtes et plus faciles à gérer.

* Contrôlez le nombre total de files d’attente de demandes disponibles pour les utilisateurs et utilisatrices en décomposant une file d’attente à l’aide de groupes thématiques et de sujets de file d’attente, plutôt que de créer plusieurs files d’attente.

* Définissez des règles de routage pour chaque rubrique de file d’attente. Configurez au minimum une règle de routage par défaut.

* Tirez parti des groupes thématiques et des rubriques de file d’attente lorsqu’un routage sélectif est nécessaire.

* Routez les demandes vers une équipe plutôt qu’une personne.


</br>
</br>


## Pourquoi s’agit-il des bonnes pratiques ?


**Bonnes pratiques**

Incluez une description de chaque élément d’une file d’attente de demandes : le projet de file d’attente de demandes, les groupes de rubriques, les rubriques de file d’attente et les règles de routage.

**Voici pourquoi**

Les descriptions permettent aux administrateurs et administratrices de groupe, aux futurs administrateurs et administratrices système et aux autres personnes qui gèrent les files d’attente de savoir exactement ce que fait chaque élément de la file d’attente.

Les informations de description s’affichent également lorsque vous placez le curseur de la souris sur l’icône d’informations du champ dans la nouvelle fenêtre de demande.

La description ne doit pas être nécessairement longue, il s’agit simplement d’un bref commentaire sur la fonction ou l’utilisation de l’élément.

</br>
</br>

**Bonne pratique**

Créez un statut de projet nommé « File d’attente » ou « Opérationnel » qui équivaut à « En cours » pour distinguer les projets de la file d’attente de demandes des autres projets.

**Voici pourquoi**

Une file d’attente de demandes est déjà présente dans un projet et doit avoir un statut correspondant à « en cours » pour être active.

Afin de faire la différence entre une demande et des projets de travail réels dont le statut est « En cours », créez un statut qui ne sera utilisé que pour les files d’attente de demandes, nommé « File d&#39;attente de demandes » ou « Opérationnel ». Vous pouvez ensuite utiliser ce statut pour exclure ou inclure des projets de la file d’attente des demandes lors de la rédaction des rapports.

</br>
</br>

**Bonne pratique**

Créez un statut de problème nommé « Rejeté » lorsque vous utilisez les approbations de problème et activez l’option Si rejeté sur le statut « Rejeté ».

**Voici pourquoi**

L’utilisation d’un statut « Rejeté » permet de clairement indiquer que la demande a été examinée et rejetée.

</br>
</br>

**Bonne pratique**

Attribuez des formulaires personnalisés « universels » aux files d’attente de demandes afin de capturer autant de données pertinentes que possible dans toute l’entreprise.

**Voici pourquoi**

Un formulaire personnalisé « universel » rassemble les informations standard nécessaires à la demande, quel que soit le type de demande soumise.

L’existence d’un formulaire personnalisé « universel » permet de réduire le nombre de formulaires personnalisés à créer et à maintenir à jour. Il garantit également que toutes les demandes collectent les mêmes informations de la même manière, ce qui permet d’obtenir des rapports et des analyses de données cohérents.

</br>
</br>

**Bonne pratique**

Évitez de partager les files d’attente de demandes avec « tout le monde ».  Paramétrez les détails de la file d’attente pour que les utilisateurs et les utilisatrices ne voient que les files d’attente correspondant à leurs besoins.

**Voici pourquoi**

Dans la plupart des cas, une file d’attente de demandes ne doit être partagée qu’avec un certain nombre de personnes, comme une équipe, un fournisseur, des clients, etc. Lorsque les demandeurs et les demandeuses ne voient que ce dont ils ont besoin dans la liste d’attente des demandes, ils auront plus de facilité à trouver des éléments et à naviguer parmi eux.

</br>
</br>


**Bonne pratique**

Créez et affectez un tableau de bord contenant des rapports sur la file d’attente des demandes afin que les responsables du trafic, les administrateurs et administratrices système ou les utilisateurs et utilisatrices affectés puissent travailler directement sur les problèmes.

**Voici pourquoi**

En permettant aux personnes d’accéder rapidement et facilement aux demandes entrantes, on évite que le travail ne se perde dans les méandres du système.

</br>
</br>

**Bonne pratique**

Utilisez les modèles de disposition pour supprimer les options de configuration de la file d’attente des demandes dans le menu du panneau de gauche des projets pour les utilisateurs et utilisatrices qui n’ont pas besoin de créer des files d’attente.


**Voici pourquoi**

Cela permet de s’assurer que toutes les files d’attente de demandes passent par le processus de création approprié (comme l’examen par un comité de gouvernance) et qu’elles sont configurées correctement par l’équipe d’administration du système ou du groupe.

En outre, cela permet de maintenir une liste des files d’attente organisée et de se concentrer sur les types de demandes dont votre organisation a besoin.

</br>
</br>

**Bonne pratique**

Créez une file d’attente des demandes de l’équipe d’administration système afin que les utilisateurs et utilisatrices puissent poser des questions relatives à Workfront, faire des demandes concernant la configuration du système, planifier la formation des nouveaux arrivants, etc.

**Voici pourquoi**

Elle représente un emplacement centralisé où les utilisateurs et utilisatrices peuvent envoyer leurs questions et où les équipes d’administration peuvent recueillir et surveiller les problèmes liés à Workfront et y répondre.

En outre, ces informations peuvent être utilisées pour montrer à la direction le temps, les efforts et la valeur du rôle d’administration système et pour justifier l’embauche d’un administrateur ou d’une administratrice système supplémentaire.

</br>
</br>


**Bonne pratique**

Auditez régulièrement les files d’attente de demandes afin d’identifier et d’annuler le partage des files d’attente qui ne sont pas utilisées.

**Voici pourquoi**

Un audit régulier des configurations et des éléments de votre système Adobe Workfront permet de l’alléger et de le débarrasser des éléments inutiles. Si une file d’attente n’est plus utilisée ou surveillée, assurez-vous que les utilisateurs et utilisatrices ne puissent plus y accéder afin que les demandes de travail ne soient pas perdues.

</br>
</br>


**Bonne pratique**

Utilisez les groupes de sujets pour organiser plus de 10 sujets dans une file d’attente de demandes afin de créer des listes plus courtes et plus faciles à gérer.

**Voici pourquoi**

Les groupes thématiques favorisent l’adoption par les utilisateurs et utilisatrices et réduisent la confusion en diminuant la liste initiale d’options à sélectionner. Cela permet aux personnes de trouver facilement ce qu’elles recherchent sans être submergées lorsqu’elles essaient de soumettre une demande.

En outre, cela permet à l’équipe d’administration système et/ou aux gestionnaires de files d’attente de créer un parcours de navigation fluide pour les utilisateurs et utilisatrices et une meilleure façon d’organiser et de rendre compte des types de demandes soumises.

</br>
</br>

**Bonne pratique**

Contrôlez le nombre total de files d’attente de demandes disponibles pour les utilisateurs et utilisatrices en décomposant une file d’attente à l’aide de groupes thématiques et de sujets de file d’attente, plutôt que de créer plusieurs files d’attente.

**Voici pourquoi**

Si les files d’attente de demandes sont trop nombreuses, les utilisateurs et utilisatrices ont du mal à trouver ce dont ils ont besoin.

La réduction du nombre de files d’attente aide également les équipes de coordination de trafic, d’administration système ou les autres personnes qui gèrent les files d’attente, en leur permettant de trouver plus rapidement les informations dont elles ont besoin, sans avoir à naviguer dans de multiples projets de files d’attente de demandes.

Créez plusieurs files d’attente de demandes s’il vous faut un accès différent pour les différentes files d’attente ou si la consolidation des files d’attente risque d’être source de confusion pour les utilisateurs et utilisatrices.

</br>
</br>

**Bonne pratique**

Définissez des règles de routage pour chaque rubrique de file d’attente. Configurez au minimum une règle de routage par défaut.

**Voici pourquoi**

Les règles de routage garantissent qu’une personne sera toujours affectée à la demande entrante afin que le travail ne passe pas entre les mailles du filet.

</br>
</br>

**Bonne pratique**

Tirez parti des groupes thématiques et des rubriques de file d’attente lorsqu’un routage sélectif est nécessaire.

**Voici pourquoi**

Les règles de routage ne peuvent pas être appliquées aux champs d’un formulaire personnalisé. Ainsi, si différents types de demandes doivent être routés vers différentes équipes/personnes, chaque type de demande doit avoir son propre groupe thématique/sujet de file d’attente afin que le travail puisse être routé correctement.

</br>
</br>

**Bonne pratique**

Routez les demandes vers une équipe plutôt qu’une personne.

**Voici pourquoi**

Lorsque des demandes sont envoyées à l’équipe, cela permet à l’ensemble de l’équipe d’avoir une visibilité sur les demandes formulées et sur un travail éventuel à venir. Tout le monde peut consulter la page Équipe pour connaître les nouveaux éléments ou suivre les nouveautés d’un rapport sur un tableau de bord.

Cela garantit également que, lorsque le gestionnaire de trafic ou toute autre personne chargée d’examiner ou d’affecter les demandes entrantes n’est pas disponible, un remplaçant ou une remplaçante est automatiquement disponible et a accès aux informations relatives à la demande.
