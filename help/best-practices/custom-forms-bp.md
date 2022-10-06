---
title: Bonne pratique - Formulaires personnalisés
description: Découvrez les recommandations de bonnes pratiques des experts d’Adobe Workfront concernant la configuration et la gestion des formulaires personnalisés Workfront.
feature: Digital Content and Documents
role: Admin, Leader, User
level: Beginner
kt: 10907
exl-id: 0c0fca34-2be0-4208-95d0-241d2e032ce7
source-git-commit: 444f059d3cc26d8e3074a7145bc5419407c786cf
workflow-type: tm+mt
source-wordcount: '2202'
ht-degree: 0%

---

# Bonne pratique - Formulaires personnalisés

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux formulaires personnalisés

* Diagramme d’un formulaire personnalisé (sur un tableau blanc ou un morceau de papier) avant de le créer dans Adobe Workfront.

* Joindre des formulaires personnalisés à un modèle de projet si les projets créés avec ce modèle ont toujours besoin de certains formulaires personnalisés joints. Vous pouvez même remplir les champs qui changent rarement ou qui requièrent des informations spécifiques.

* Créez un formulaire personnalisé pour effectuer le suivi des informations sur les clients ou fournisseurs externes que vous avez ajoutés à votre système Workfront en tant qu’entreprise.

* Créez un seul formulaire personnalisé &quot;général&quot; ou &quot;universel&quot; qui contient des champs communs et des champs calculés, plutôt que d’associer les champs individuels à plusieurs formulaires. Vous pouvez ainsi collecter des informations à l’échelle de l’entreprise de manière cohérente.

* Ajoutez des sauts de section à un formulaire personnalisé afin de l’organiser et de le comprendre facilement.

* Veillez à ce que les formulaires personnalisés restent plus courts pour vous assurer qu’ils sont entièrement remplis et que vous obtenez toutes les informations dont vous avez besoin.

* Utilisez des options de champ personnalisé prédéfinies, telles que des boutons radio et des menus déroulants, pour limiter les options de réponse en demandant aux utilisateurs de sélectionner des options spécifiques.

* Assurez-vous que les libellés de champ sont clairement écrits et descriptifs.

* Ajoutez des informations dans le champ Instructions des champs personnalisés pour indiquer les informations que la personne qui remplit le champ doit entrer.

* Utilisez la logique d’affichage pour afficher les champs nécessaires lorsqu’un autre champ est renseigné d’une manière spécifique. Utilisez la logique de saut dans les formulaires personnalisés pour masquer les champs qui ne sont pas liés au type de requête.

* Réduisez le nombre de calculs requis sur un formulaire personnalisé en extrayant les informations calculées d’un autre formulaire.

* Consultez la bibliothèque de champs avant de créer de nouveaux champs pour un formulaire personnalisé afin de vérifier si le champ existe déjà.

* Utilisez les champs requis pour vous assurer que les informations essentielles à votre processus ou organisation sont capturées.

* Soyez prudent lors de la modification des noms de champ sur un formulaire personnalisé, car cela peut affecter les champs calculés qui appellent ce champ.

* Consultez régulièrement les formulaires et champs personnalisés (une fois par trimestre, par exemple) dans le cadre de la maintenance régulière du système Workfront.

* Désactivez les formulaires personnalisés inutiles au lieu de les supprimer.

* Masquez les champs personnalisés qui ne sont plus nécessaires sur un formulaire personnalisé sous un saut de section. Rendez ensuite cette section visible uniquement aux administrateurs système.

* Limitez les utilisateurs autorisés à créer des formulaires personnalisés dans votre instance Workfront.

</br>
</br>

## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Diagramme d’un formulaire personnalisé (sur un tableau blanc ou un morceau de papier) avant de le créer dans Adobe Workfront.

**Voici pourquoi**

Assurez-vous que vous disposez de champs pour toutes les informations requises et que les champs sont organisés de manière à faciliter le remplissage du formulaire par les utilisateurs. Le diagramme du formulaire peut également vous aider à déterminer si certains champs peuvent être masqués/affichés à l’aide de la logique d’affichage.

</br>
</br>

**Bonne pratique**

Joindre des formulaires personnalisés à un modèle de projet si les projets créés avec ce modèle ont toujours besoin de certains formulaires personnalisés joints. Vous pouvez même remplir les champs qui changent rarement ou qui requièrent des informations spécifiques.

**Voici pourquoi**

Ainsi, le formulaire est déjà joint et certaines informations sont déjà remplies, ce qui accélère la création du projet et garantit que ces champs personnalisés sont remplis correctement et complètement dans tous les projets applicables.

</br>
</br>

**Bonne pratique**

Créez un formulaire personnalisé pour effectuer le suivi des informations sur les clients ou fournisseurs externes que vous avez ajoutés à votre système Workfront en tant qu’entreprise.

**Voici pourquoi**

Utilisez le formulaire personnalisé pour effectuer le suivi de l’adresse, du nom du Principal contact, etc., afin qu’il soit facilement accessible dans Workfront. Vous pourrez également extraire ces informations de formulaire personnalisées dans les rapports.

</br>
</br>

**Bonne pratique**

Créez un seul formulaire personnalisé &quot;général&quot; ou &quot;universel&quot; qui contient des champs communs et des champs calculés, plutôt que d’associer les champs individuels à plusieurs formulaires. Vous pouvez ainsi collecter des informations à l’échelle de l’entreprise de manière cohérente.

**Voici pourquoi**

Un formulaire &quot;général&quot; facilite la maintenance de ces champs, car ils vivent tous au même endroit. Vous pourrez mettre à jour un seul formulaire, plutôt que de disposer de champs individuels qui vivent sur plusieurs formulaires différents, que vous devrez ensuite mettre à jour individuellement.

</br>
</br>

**Bonne pratique**

Ajoutez des sauts de section à un formulaire personnalisé afin de l’organiser et de le comprendre facilement.

**Voici pourquoi**

Le regroupement des informations connexes dans des sections permet aux utilisateurs de parcourir le formulaire.

</br>
</br>

**Bonne pratique**

Veillez à ce que les formulaires personnalisés restent plus courts pour vous assurer qu’ils sont entièrement remplis et que vous obtenez toutes les informations dont vous avez besoin.

**Voici pourquoi**

Les formulaires longs peuvent être intimidants pour les utilisateurs et risquent souvent de ne pas être complètement remplis. Cela entraîne des informations d’affectation incomplètes et des données inexactes pour les rapports.

Si un formulaire personnalisé comporte de nombreux champs, placez les champs associés côte à côte, si possible, afin que l’utilisateur puisse moins faire défiler l’écran. Vous pouvez également utiliser la logique de saut pour masquer les champs qui n’ont pas besoin d’être remplis ou afficher la logique pour afficher des champs spécifiques.

</br>
</br>

**Bonne pratique**

Utilisez des options de champ personnalisé prédéfinies, telles que des boutons radio et des menus déroulants, pour limiter les options de réponse en demandant aux utilisateurs de sélectionner des options spécifiques.

**Voici pourquoi :**

Avec un champ prédéfini, les utilisateurs se contentent de cliquer sur une zone ou de sélectionner dans un menu, ce qui garantit que toutes les réponses à cette question sont identiques.

Des données cohérentes et précises sont essentielles pour la création de rapports précis. Des données incohérentes génèrent des rapports inexacts, ce qui peut affecter les décisions prises au niveau individuel. En outre, ces données cohérentes vous permettent d’ajouter des graphiques aux rapports pour une représentation visuelle de vos données. Les champs de texte ouverts ne peuvent pas être utilisés dans les graphiques.

</br>
</br>

**Bonne pratique**

Assurez-vous que les libellés de champ sont clairement écrits et descriptifs.

**Voici pourquoi :**

Ainsi, la personne qui remplit le formulaire personnalisé comprend les informations demandées.

</br>
</br>

**Bonne pratique**

Ajoutez des informations dans le champ Instructions des champs personnalisés pour indiquer les informations que la personne qui remplit le champ doit entrer.

**Voici pourquoi :**

Ces informations s’affichent sous forme de fenêtre contextuelle lorsque vous placez le pointeur de la souris sur l’icône ? Icône en regard d’un champ sur un formulaire personnalisé. Incluez les données à saisir dans le champ, y compris toute mise en forme requise pour les champs de texte.

Le fait de fournir plus de détails à l’utilisateur permet d’atténuer les conversations, les emails aller-retour ou la confusion supplémentaires. Lorsque des informations sont incomplètes ou manquantes, cela peut retarder le travail en cours.

</br>
</br>

**Bonne pratique**

Utilisez la logique d’affichage pour afficher les champs nécessaires lorsqu’un autre champ est renseigné d’une manière spécifique. Utilisez la logique de saut dans les formulaires personnalisés pour masquer les champs qui ne sont pas liés au type de requête.

**Voici pourquoi :**

L’affichage des champs nécessaires ou le masquage des champs qui ne le sont pas crée un formulaire personnalisé plus propre et moins de confusion pour les utilisateurs lorsqu’ils remplissent des formulaires personnalisés. Cela contribue également à un formulaire global plus court, qui décourage moins les utilisateurs et favorise un taux de réponse plus élevé.

L’utilisation de la logique d’affichage peut également vous aider à réduire le nombre de formulaires personnalisés que vous devez créer et gérer.

</br>
</br>

**Bonne pratique**

Réduisez le nombre de calculs requis sur un formulaire personnalisé en extrayant les informations calculées d’un autre formulaire.

**Voici pourquoi :**

Par exemple, vous disposez d’un champ calculé appelé &quot;Nombre de ressources&quot; sur un formulaire de problème qui calcule le nombre de ressources jointes à l’élément. Il est utilisé sur une file d’attente de demandes. Vous avez besoin de ces informations pour les transférer au projet lorsque la requête est convertie. Effectuez une copie du formulaire de problème et enregistrez-le en tant que formulaire de projet. Ajoutez ensuite le nom du champ calculé d’émission dans la zone de calcul du formulaire du projet. Dans cet exemple, dans le champ calculé du formulaire de projet appelé &quot;Nombre de ressources&quot;, saisissez littéralement &quot;Nombre de ressources&quot;. Cela empêche Workfront de réexécuter ce calcul sur le projet et d’utiliser à la place la valeur du formulaire personnalisé Problème.

</br>
</br>

**Bonne pratique**

Utilisez les champs existants de la bibliothèque de champs qui ont le même objectif, le cas échéant.

**Voici pourquoi :**

Deux champs de Workfront ne peuvent pas porter le même nom. Si le champ a un nom commun, il est possible que le champ existe déjà. Vérifiez la bibliothèque de champs avant de créer de nouveaux champs pour voir si le champ existe déjà.

Lorsque vous utilisez des champs que vous n’avez pas créés, n’oubliez pas que les modifications apportées à ce champ affectent TOUS les formulaires personnalisés dont le champ fait partie. Si vous devez modifier un calcul ou le type d’un champ (par exemple, du texte en boutons radio), vous devez créer un nouveau champ et lui donner un nom différent de celui de l’original. (Gardez à l’esprit que plusieurs champs portant des noms similaires peuvent dérouter les utilisateurs.)

</br>
</br>

**Bonne pratique**

Utilisez les champs requis pour vous assurer que les informations essentielles à votre processus ou organisation sont capturées.

**Voici pourquoi :**

Les données incomplètes sur un formulaire personnalisé peuvent retarder le travail et affecter la création de rapports. L’indicateur de champ obligatoire (un caractère rouge * en regard du nom du champ) rappelle aux utilisateurs que des informations spécifiques sont requises avant de les modifier, puis d’enregistrer ce formulaire personnalisé ou d’envoyer officiellement une requête.

Toutefois, les champs requis doivent être utilisés avec modération et prudence. Chaque champ requis peut empêcher les utilisateurs de remplir les champs avec des informations utiles et complètes. En outre, lors de la modification d’un formulaire personnalisé dans la zone Détails d’un objet, un champ obligatoire incomplet empêche l’enregistrement d’un formulaire personnalisé.

</br>
</br>

**Bonne pratique**

Soyez prudent lors de la modification des noms de champ sur un formulaire personnalisé, car cela peut affecter les champs calculés qui appellent ce champ.

**Voici pourquoi :**

Lorsque vous modifiez le nom d’un champ, il doit être mis à jour, où il est utilisé dans un champ personnalisé calculé sur un formulaire personnalisé ou dans un calcul intégré au mode texte. La modification du nom d’un champ peut interrompre les calculs et générer des informations inexactes.

</br>
</br>

**Bonne pratique**

Consultez régulièrement les formulaires et champs personnalisés (une fois par trimestre, par exemple) dans le cadre de la maintenance régulière du système Workfront.

**Voici pourquoi**

Les formulaires et champs personnalisés ne sont pas utiles s’ils ne collectent pas les données dont votre entreprise a besoin pour que le travail soit fait.

Lorsque vous effectuez des mises à jour, gardez à l’esprit la manière dont ces modifications affectent d’autres aspects de Workfront. Par exemple, la modification du nom d’un champ peut rompre un calcul qui utilise ce champ. Ou modifier le libellé ou le nom d&#39;un formulaire peut empêcher l&#39;affichage des informations nécessaires dans un rapport ou l&#39;inexécution d&#39;une intégration à un autre système.

Outre la mise à jour de formulaires personnalisés, identifiez les formulaires peu utilisés ou qui ne le sont pas du tout. Les formulaires qui ne sont pas fréquemment utilisés peuvent-ils être combinés à un autre formulaire ? Ou peut-être est-il temps d’abandonner ce formulaire, parce que vos équipes n’ont plus besoin des informations que le formulaire collecte.

Avant d’agir avec ces formulaires inutiles, lisez la section sur la désactivation ou la suppression de formulaires personnalisés et de champs personnalisés.

</br>
</br>

**Bonne pratique**

Désactivez les formulaires personnalisés inutiles au lieu de les supprimer.

**Voici pourquoi**

Lorsque vous supprimez un formulaire personnalisé, vous supprimez toutes les données personnalisées qui ont été saisies via ce formulaire personnalisé.
La désactivation d’un formulaire personnalisé conserve toutes les données historiques associées. Cela signifie que vous pouvez continuer à générer des rapports sur ces informations.

La désactivation empêche également le formulaire de s’afficher dans les menus déroulants où les utilisateurs sélectionnent un formulaire personnalisé. Cependant, le formulaire s’affiche toujours sur tous les objets auxquels il est déjà attaché.

</br>
</br>

**Bonne pratique**

Masquez les champs personnalisés qui ne sont plus nécessaires sur un formulaire personnalisé sous un saut de section. Rendez ensuite cette section visible uniquement aux administrateurs système.

**Voici pourquoi**

La suppression d’un champ personnalisé existant entraîne non seulement sa suppression d’un formulaire personnalisé, mais également la suppression de toutes les données contenues dans ce champ, quel que soit l’endroit où ce champ personnalisé est utilisé. Cela signifie que les données historiques, qui peuvent être nécessaires pour les rapports, sont supprimées.

Pour éviter toute perte de données, masquez le champ superflu dans le formulaire personnalisé lui-même. Les sauts de section dans les formulaires personnalisés vous permettent de masquer ou d’afficher les champs qui font partie de cette section selon que l’utilisateur a accès à l’objet Workfront auquel il est associé, ou s’il y a accès. Une section peut également être définie sur Admin uniquement, de sorte que seuls les utilisateurs disposant d’un niveau d’accès administrateur système peuvent voir toute cette section du formulaire.

</br>
</br>

**Bonne pratique**

Limitez les utilisateurs autorisés à créer des formulaires personnalisés dans votre instance Workfront.


**Voici pourquoi**

La présence d’un groupe de personnes sélectionnées pouvant créer des formulaires personnalisés permet de contrôler le nombre de formulaires personnalisés créés dans votre instance Workfront.

En outre, permettre à d’autres personnes de créer des formulaires peut alléger le travail de l’administrateur système et permet à chaque groupe de contrôler régulièrement les mises à jour des formulaires personnalisés qu’ils utilisent.
