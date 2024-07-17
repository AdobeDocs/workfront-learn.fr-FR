---
title: Bonne pratique - Explorateur d’API
description: Découvrez les bonnes pratiques recommandées par les expertes et experts d’Adobe Workfront en matière de configuration, de gestion et d’utilisation de l’explorateur d’API de Workfront.
feature: Workfront API
role: Admin, Leader, User
level: Beginner
jira: KT-10902
exl-id: 0f3fc5ba-d01a-4337-829f-def0830ddf81
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 100%

---

# Bonne pratique - Explorateur d’API

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques pour ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La zone « Pourquoi s’agit-il de bonnes pratiques ? » qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques de l’explorateur d’API

* Établissez une convention de nommage pour les champs personnalisés utilisés avec des intégrations de systèmes tiers.

* Suivez tous les champs personnalisés utilisés dans les intégrations à l’aide d’un projet Workfront.

* Ajoutez le champ ID de l’objet aux rapports utilisés par l’administrateur ou l’administratrice système.

</br>
</br>

## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Établissez une convention de nommage pour les champs personnalisés utilisés avec des intégrations de systèmes tiers.

**Voici pourquoi**

Assurez-vous que toutes les personnes qui créent des formulaires personnalisés connaissent la convention de nommage, afin qu’elles n’utilisent pas accidentellement un champ réservé à une intégration. En fonction de vos intégrations et workflows, l’utilisation d’un même champ de plusieurs manières peut entraîner la modification ou le remplacement des données et générer des données incorrectes dans les rapports.

</br>
</br>


**Bonne pratique**

Suivez tous les champs personnalisés utilisés dans les intégrations à l’aide d’un projet Workfront.

**Voici pourquoi**

Un projet est l’endroit idéal pour enregistrer les noms des champs personnalisés, l’intégration avec laquelle ils sont utilisés, etc. Vous éviterez ainsi de créer des champs personnalisés redondants ou d’utiliser le même champ personnalisé avec plusieurs intégrations.

</br>
</br>


**Bonne pratique**

Ajoutez le champ ID de l’objet aux rapports utilisés par l’administrateur ou l’administratrice système.

**Voici pourquoi**

Les administrateurs et administratrices système ont souvent besoin de se référer aux objets de Workfront par leur numéro d’identification lorsqu’ils utilisent des API ou d’autres intégrations. Incluez le champ ID dans les vues des objets sur lesquels vous travaillez (projets, tâches, problèmes, modèles, formulaires personnalisés, etc.) afin d’en faciliter l’accès et la copie.
