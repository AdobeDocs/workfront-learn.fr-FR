---
title: Bonne pratique - Formulaires personnalisés
description: Découvrez les recommandations de bonnes pratiques des expertes et experts d’Adobe Workfront concernant la configuration et la gestion des formulaires personnalisés Workfront.
feature: Digital Content and Documents
role: Admin, Leader, User
level: Beginner
jira: KT-10907
exl-id: 0c0fca34-2be0-4208-95d0-241d2e032ce7
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '2202'
ht-degree: 100%

---

# Bonne pratique - Formulaires personnalisés

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques pour ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La zone « Pourquoi s’agit-il de bonnes pratiques ? » qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux formulaires personnalisés

* Ébauchez un formulaire personnalisé (sur un tableau blanc ou un morceau de papier) avant de le créer dans Adobe Workfront.

* Attachez des formulaires personnalisés à un modèle de projet si les projets réalisés avec ce modèle doivent toujours être accompagnés de certains formulaires personnalisés. Vous pouvez même remplir les champs qui changent rarement ou qui requièrent des informations spécifiques.

* Créez un formulaire personnalisé pour effectuer le suivi des informations sur les clientes, clients, fournisseurs ou fournisseuses externes que vous avez ajoutés à votre système Workfront en tant qu’entreprise.

* Créez un seul formulaire personnalisé « général » ou « universel » qui contient des champs communs et des champs calculés, plutôt que d’ajouter des champs individuels à plusieurs formulaires. Cela vous permet de collecter des informations à l’échelle de l’entreprise de manière cohérente.

* Ajoutez des sauts de section dans un formulaire personnalisé afin qu’il soit ordonné et facile à comprendre.

* Veillez à ce que vos formulaires personnalisés restent courts pour vous assurer que ceux-ci soient entièrement remplis et que vous puissiez obtenir toutes les informations dont vous avez besoin.

* Utilisez des options de champ personnalisé prédéfinies, telles que des boutons radio et des menus déroulants, pour limiter les options de réponse en demandant aux utilisateurs et utilisatrices de sélectionner des options spécifiques.

* Assurez-vous que les libellés de champ sont clairement écrits et descriptifs.

* Ajoutez des informations dans le champ Instructions des champs personnalisés pour indiquer ce que doit saisir la personne qui remplit le champ.

* Utilisez la logique d’affichage pour afficher les champs nécessaires lorsqu’un autre champ est rempli d’une manière spécifique. Utilisez la logique de saut dans les formulaires personnalisés pour masquer les champs qui ne sont pas liés au type de requête.

* Réduisez le nombre de calculs requis sur un formulaire personnalisé en extrayant les informations calculées d’un autre formulaire.

* Avant de créer de nouveaux champs pour un formulaire personnalisé, consultez la bibliothèque de champs afin de vérifier si le champ existe déjà.

* Utilisez les champs requis pour vous assurer que les informations essentielles à votre processus ou à votre organisation sont capturées.

* Faites preuve de prudence lors de la modification des noms de champ sur un formulaire personnalisé, car cela peut affecter les champs calculés qui appellent ce champ.

* Consultez régulièrement les formulaires et champs personnalisés (une fois par trimestre, par exemple) dans le cadre de la maintenance régulière du système Workfront.

* Désactivez les formulaires personnalisés inutiles au lieu de les supprimer.

* Masquez les champs personnalisés qui ne sont plus nécessaires dans un formulaire personnalisé sous un saut de section. Rendez ensuite cette section visible uniquement aux administrateurs et administratrices système.

* Limitez les utilisateurs et utilisatrices autorisés à créer des formulaires personnalisés dans votre instance Workfront.

</br>
</br>

## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Ébauchez un formulaire personnalisé (sur un tableau blanc ou un morceau de papier) avant de le créer dans Adobe Workfront.

**Voici pourquoi**

Assurez-vous que vous disposez de champs pour toutes les informations requises et qu’ils sont organisés de manière à faciliter le remplissage du formulaire. L’ébauche du formulaire peut également vous aider à déterminer si certains champs peuvent être masqués/affichés à l’aide de la logique d’affichage.

</br>
</br>

**Bonne pratique**

Attachez des formulaires personnalisés à un modèle de projet si les projets réalisés avec ce modèle doivent toujours être accompagnés de certains formulaires personnalisés. Vous pouvez même remplir les champs qui changent rarement ou qui requièrent des informations spécifiques.

**Voici pourquoi**

Ainsi, le formulaire est déjà joint et certaines informations sont déjà renseignées, ce qui accélère la création du projet et garantit que ces champs personnalisés sont remplis correctement et intégralement dans tous les projets applicables.

</br>
</br>

**Bonne pratique**

Créez un formulaire personnalisé pour effectuer le suivi des informations sur les clientes, clients, fournisseurs ou fournisseuses externes que vous avez ajoutés à votre système Workfront en tant qu’entreprise.

**Voici pourquoi**

Utilisez le formulaire personnalisé pour suivre l’adresse, le nom du contact principal, etc., de façon à ce que ces informations soient facilement accessibles dans Workfront. Vous pourrez également extraire ces informations de formulaire personnalisé vers des rapports.

</br>
</br>

**Bonne pratique**

Créez un seul formulaire personnalisé « général » ou « universel » qui contient des champs communs et des champs calculés, plutôt que d’ajouter des champs individuels à plusieurs formulaires. Cela vous permet de collecter des informations à l’échelle de l’entreprise de manière cohérente.

**Voici pourquoi**

Un formulaire « général » facilite la gestion de ces champs, car ils sont tous regroupés au même endroit. Cela vous permettra de mettre à jour un seul formulaire, plutôt que de disposer de champs individuels présents dans plusieurs formulaires différents, que vous auriez à mettre à jour individuellement.

</br>
</br>

**Bonne pratique**

Ajoutez des sauts de section dans un formulaire personnalisé afin qu’il soit ordonné et facile à comprendre.

**Voici pourquoi**

Le regroupement des informations connexes dans des sections permet aux utilisateurs et aux utilisatrices de parcourir plus facilement le formulaire.

</br>
</br>

**Bonne pratique**

Veillez à ce que vos formulaires personnalisés restent courts pour vous assurer que ceux-ci soient entièrement remplis et que vous puissiez obtenir toutes les informations dont vous avez besoin.

**Voici pourquoi**

Les longs formulaires peuvent être intimidants pour les utilisateurs et les utilisatrices et mènent souvent à un formulaire rempli de manière incomplète. Cela produit des informations d’affectation incomplètes et des données inexactes pour les rapports.

Si un formulaire personnalisé comporte de nombreux champs, placez les champs apparentés côte à côte, dans la mesure du possible, afin de réduire le défilement nécessaire pour l’utilisateur ou l’utilisatrice. Vous pouvez également utiliser une logique de saut pour masquer les champs qui n’ont pas besoin d’être remplis ou afficher la logique pour afficher des champs spécifiques.

</br>
</br>

**Bonne pratique**

Utilisez des options de champ personnalisé prédéfinies, telles que des boutons radio et des menus déroulants, pour limiter les options de réponse en demandant aux utilisateurs et utilisatrices de sélectionner des options spécifiques.

**Voici pourquoi : **

Avec un champ prédéfini, les utilisateurs et utilisatrices se contentent de cliquer dans une case ou de sélectionner un élément de menu, ce qui garantit que toutes les réponses à cette question sont identiques.

Des données cohérentes et exactes sont essentielles à l’établissement de rapports précis. Des données incohérentes donnent lieu à des rapports inexacts, ce qui peut affecter les décisions prises au niveau individuel et aux niveaux supérieurs. En outre, ces données cohérentes vous permettent d’ajouter des graphiques aux rapports pour une représentation visuelle de vos données. Les champs de texte ouverts ne peuvent pas être utilisés dans des graphiques.

</br>
</br>

**Bonne pratique**

Assurez-vous que les libellés de champ sont clairement écrits et descriptifs.

**Voici pourquoi : **

Ainsi, la personne qui remplit le formulaire personnalisé comprend les informations demandées.

</br>
</br>

**Bonne pratique**

Ajoutez des informations dans le champ Instructions des champs personnalisés pour indiquer ce que doit saisir la personne qui remplit le champ.

**Voici pourquoi : **

Ces informations apparaissent dans une fenêtre contextuelle lorsque vous survolez l’icône « ? »  à côté d’un champ dans un formulaire personnalisé. Incluez les données à saisir dans le champ, y compris toute mise en forme requise pour les champs de texte.

Le fait de fournir plus de détails à l’utilisateur ou l’utilisatrice permet de réduire les conversations superflues, les échanges d’e-mails, ou la confusion. Lorsque des informations sont incomplètes ou manquantes, cela peut retarder le travail en cours.

</br>
</br>

**Bonne pratique**

Utilisez la logique d’affichage pour afficher les champs nécessaires lorsqu’un autre champ est rempli d’une manière spécifique. Utilisez la logique de saut dans les formulaires personnalisés pour masquer les champs qui ne sont pas liés au type de requête.

**Voici pourquoi : **

Le fait de n’afficher que les champs nécessaires ou de masquer ceux qui ne le sont pas permet de créer un formulaire personnalisé plus clair et de réduire la confusion des utilisateurs et utilisatrices lorsque ceux-ci remplissent des formulaires personnalisés. Cela contribue également à un formulaire globalement plus court, qui décourage moins les utilisateurs et utilisatrices et favorise un taux de réponse plus élevé.

L’utilisation de la logique d’affichage peut également vous aider à réduire le nombre de formulaires personnalisés que vous devez créer et gérer.

</br>
</br>

**Bonne pratique**

Réduisez le nombre de calculs requis sur un formulaire personnalisé en extrayant les informations calculées d’un autre formulaire.

**Voici pourquoi : **

Par exemple, un champ calculé appelé « Nombre de ressources » dans un formulaire de problème calcule le nombre de ressources liées à l&#39;élément. Celui-ci étant utilisé pour une file d’attente de demandes. Ces informations doivent être reportées dans le projet lorsque la demande est convertie. Faites une copie du formulaire de problème et enregistrez-le en tant que formulaire de projet. Ajoutez ensuite le nom du champ calculé du problème à la zone de calcul du formulaire de projet. Dans cet exemple, dans le champ calculé du formulaire de projet intitulé « Nombre de ressources », entrez littéralement « Nombre de ressources ». Cela empêche Workfront d’exécuter à nouveau ce calcul sur le projet et d’utiliser à la place la valeur du formulaire personnalisé de problème.

</br>
</br>

**Bonne pratique**

Utilisez les champs existants de la bibliothèque de champs qui ont le même objectif, le cas échéant.

**Voici pourquoi :**

Deux champs dans Workfront ne peuvent pas porter le même nom. Si le champ a un nom courant, il est probable qu’il existe déjà. Vérifiez la bibliothèque de champs avant de créer de nouveaux champs pour voir si le champ existe déjà.

Lorsque vous utilisez des champs que vous n’avez pas créés, n’oubliez pas que les modifications apportées à ce champ affectent TOUS les formulaires personnalisés dont il fait partie. Si vous devez modifier un calcul ou changer le type de champ (du texte aux boutons radio, par exemple), vous devez créer un nouveau champ et lui donner un nom différent de l’original. (Gardez à l’esprit que plusieurs champs portant des noms similaires peuvent dérouter les utilisateurs et les utilisatrices.)

</br>
</br>

**Bonne pratique**

Utilisez les champs requis pour vous assurer que les informations essentielles à votre processus ou à votre organisation sont capturées.

**Voici pourquoi :**

Des données incomplètes dans un formulaire personnalisé peuvent retarder le travail et affecter les rapports. L’indicateur de champ obligatoire (un caractère rouge * en regard du nom du champ) rappelle aux utilisateurs et utilisatrices que des informations spécifiques sont requises avant de modifier, puis d’enregistrer ce formulaire personnalisé ou d’envoyer officiellement une requête.

Toutefois, les champs obligatoires doivent être utilisés avec parcimonie et prudence. Le fait que chaque champ soit obligatoire peut dissuader les utilisateurs et utilisatrices de remplir les champs avec des informations utiles et complètes. En outre, lors de la modification d’un formulaire personnalisé dans la zone Détails d’un objet, un champ obligatoire incomplet empêche l’enregistrement d’un formulaire personnalisé.

</br>
</br>

**Bonne pratique**

Faites preuve de prudence lors de la modification des noms de champ sur un formulaire personnalisé, car cela peut affecter les champs calculés qui appellent ce champ.

**Voici pourquoi :**

Lorsque vous modifiez le nom d’un champ, celui-ci doit être mis à jour lorsqu’il est utilisé dans un champ personnalisé calculé sur un formulaire personnalisé ou dans un calcul intégré au mode texte. La modification du nom d’un champ peut interrompre les calculs et générer des informations inexactes.

</br>
</br>

**Bonne pratique**

Consultez régulièrement les formulaires et champs personnalisés (une fois par trimestre, par exemple) dans le cadre de la maintenance régulière du système Workfront.

**Voici pourquoi :**

Les formulaires et champs personnalisés ne sont pas utiles s’ils ne collectent pas les données dont votre entreprise a besoin pour que le travail soit fait.

Lorsque vous effectuez des mises à jour, tenez compte de la façon dont ces changements affectent d’autres aspects de Workfront. Par exemple, la modification du nom d’un champ peut interrompre un calcul qui utilise ce champ. Ou modifier le libellé ou le nom d’un formulaire peut empêcher l’affichage des informations nécessaires dans un rapport ou l’inexécution d’une intégration à un autre système.

Outre la mise à jour des formulaires personnalisés, il convient d’identifier les formulaires peu ou pas utilisés. Les formulaires peu utilisés peuvent-ils être combinés avec un autre formulaire ? Ou peut-être est-il temps d’abandonner ce formulaire, parce que vos équipes n’ont plus besoin des informations qu’il collecte.

Avant d’agir avec ces formulaires inutiles, lisez la section sur la désactivation ou la suppression de formulaires personnalisés et de champs personnalisés.

</br>
</br>

**Bonne pratique**

Désactivez les formulaires personnalisés inutiles au lieu de les supprimer.

**Voici pourquoi :**

Lorsque vous supprimez un formulaire personnalisé, vous supprimez toutes les données personnalisées qui ont été saisies via ce formulaire.
La désactivation d’un formulaire personnalisé conserve toutes les données historiques associées. Cela signifie que vous pouvez continuer à générer des rapports sur ces informations.

La désactivation empêche également le formulaire d’apparaître dans les menus déroulants où les utilisateurs et utilisatrices sélectionnent un formulaire personnalisé. Cependant, le formulaire s’affiche toujours sur tous les objets auxquels il est déjà attaché.

</br>
</br>

**Bonne pratique**

Masquez les champs personnalisés qui ne sont plus nécessaires dans un formulaire personnalisé sous un saut de section. Rendez ensuite cette section visible uniquement aux administrateurs et administratrices système.

**Voici pourquoi :**

La suppression d’un champ personnalisé existant ne le supprime pas seulement d’un formulaire personnalisé : elle supprime aussi toutes les données qu’il contient, quel que soit l’endroit où il est utilisé. Cela signifie que les données historiques, qui peuvent être nécessaires pour les rapports, sont supprimées.

Pour éviter toute perte de données, masquez le champ inutile dans le formulaire personnalisé lui-même. Les sauts de section dans les formulaires personnalisés vous permettent de masquer ou d’exposer les champs qui font partie de cette section en fonction de l’accès de l’utilisateur ou de l’utilisatrice à l’affichage, à la contribution ou à la gestion de l’objet Workfront auquel elle est attachée. Une section peut également être définie sur Admin uniquement, de sorte que seuls les utilisateurs et les utilisatrices disposant d’un niveau d’accès administrateur ou administratrice système peuvent voir toute cette section du formulaire.

</br>
</br>

**Bonne pratique**

Limitez les utilisateurs et utilisatrices autorisés à créer des formulaires personnalisés dans votre instance Workfront.


**Voici pourquoi :**

La présence d’un groupe de personnes sélectionnées pouvant créer des formulaires personnalisés permet de contrôler le nombre de formulaires personnalisés créés dans votre instance Workfront.

En outre, permettre à d’autres personnes de créer des formulaires peut alléger le travail de l’administrateur ou de l’administratrice système et permet à chaque groupe de contrôler régulièrement les mises à jour des formulaires personnalisés qu’ils utilisent.
