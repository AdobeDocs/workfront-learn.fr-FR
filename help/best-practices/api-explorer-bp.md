---
title: Bonne pratique - Explorateur d’API
description: Examinez les recommandations relatives aux bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation de l’explorateur d’API Workfront.
feature: Workfront API
role: Admin, Leader, User
level: Beginner
jira: KT-10902
exl-id: 0f3fc5ba-d01a-4337-829f-def0830ddf81
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 0%

---

# Bonne pratique - Explorateur d’API

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives à l’API Explorer

* Définissez une convention d’affectation des noms pour les champs personnalisés utilisés avec les intégrations de systèmes tiers.

* Suivez tous les champs personnalisés utilisés dans les intégrations à l’aide d’un projet Workfront.

* Ajoutez le champ Identifiant d’objet aux rapports utilisés par l’administrateur système.

</br>
</br>

## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Définissez une convention d’affectation des noms pour les champs personnalisés utilisés avec les intégrations de systèmes tiers.

**Voici pourquoi**

Assurez-vous que tous les utilisateurs qui créent des formulaires personnalisés connaissent la convention d’affectation des noms afin qu’ils n’utilisent pas accidentellement un champ réservé à une intégration. En fonction de vos intégrations et workflows, l’utilisation d’un même champ de plusieurs manières peut entraîner la modification ou le remplacement des données et générer des données incorrectes dans les rapports.

</br>
</br>


**Bonne pratique**

Suivez tous les champs personnalisés utilisés dans les intégrations à l’aide d’un projet Workfront.

**Voici pourquoi**

Un projet crée l’emplacement idéal pour consigner les noms de champ personnalisés, l’intégration avec laquelle ils sont utilisés, etc. Vous éviterez ainsi de créer des champs personnalisés redondants ou d’utiliser le même champ personnalisé avec plusieurs intégrations.

</br>
</br>


**Bonne pratique**

Ajoutez le champ Identifiant d’objet aux rapports utilisés par l’administrateur système.

**Voici pourquoi**

Les administrateurs système doivent souvent se référer aux objets dans Workfront par leur numéro d’ID lors de l’utilisation d’API ou d’autres intégrations. Incluez le champ Identifiant dans les vues des objets sur lesquels vous travaillez (projets, tâches, problèmes, modèles, formulaires personnalisés, etc.) pour faciliter l’accès et la copie.
