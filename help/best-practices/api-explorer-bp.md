---
title: Bonne pratique - Explorateur d’API
description: Découvrez les bonnes pratiques recommandées par les expertes et experts d’Adobe Workfront en matière de configuration, de gestion et d’utilisation de l’explorateur d’API de Workfront.
feature: Workfront API
role: Admin, Leader, User
level: Beginner
jira: KT-10902
exl-id: 0f3fc5ba-d01a-4337-829f-def0830ddf81
TQID: https://experienceleague.adobe.com/RUQeNzEb0eg9DKSKepugb0HD4O2ODql-0mWBn-ptgxk
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: b58ad82f-df6b-4b01-81a3-3a02ab9567a0
  - id: f48b5020-b9cd-4d99-bc6e-42c35e90c1f8
subfeature_v2:
  - id: bb1dd007-4a34-496d-9d3b-2278fdaadac1
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
source-git-commit: 36674ed53c8645f556862bb2d99f3bfd6c993c1e
workflow-type: tm+mt
source-wordcount: 410
ht-degree: 75%

---

# Bonne pratique - Explorateur d’API

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques pour ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La zone « Pourquoi ces bonnes pratiques ? », qui se trouve après la liste de haut niveau, fournit plus de détails sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., que vous devez envisager d’implémenter avec votre instance Workfront.

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

Un projet constitue l’emplacement idéal pour consigner les noms de champ personnalisés, l’intégration à laquelle ils sont utilisés, etc. Cela vous aidera à éviter de créer des champs personnalisés redondants ou d’utiliser le même champ personnalisé avec plusieurs intégrations.

</br>
</br>


**Bonne pratique**

Ajoutez le champ ID de l’objet aux rapports utilisés par l’administrateur ou l’administratrice système.

**Voici pourquoi**

Les administrateurs et administratrices système ont souvent besoin de se référer aux objets de Workfront par leur numéro d’identification lorsqu’ils utilisent des API ou d’autres intégrations. Insérez le champ d’ID dans les vues des objets sur lesquels vous travaillez (projets, tâches, événements, modèles, formulaires personnalisés, etc.) pour faciliter l’accès et la copie.
