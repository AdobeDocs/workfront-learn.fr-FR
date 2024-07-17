---
title: Bonne pratique - Préférences pour les projets, les tâches et les problèmes
description: Examinez les recommandations relatives aux bonnes pratiques des expertes et experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation de préférences de projets, de tâches et de problèmes dans Workfront.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10918
exl-id: 321af897-3791-4b06-a9dd-241b5246b2a0
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '702'
ht-degree: 100%

---

# Bonne pratique - Préférences pour les projets, les tâches et les problèmes

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques pour ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La zone « Pourquoi s’agit-il de bonnes pratiques ? » qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux préférences en matière de projets, de tâches et de problèmes

* Définissez le type de durée de tâche par défaut sur Simple.

* Définissez la préférence de statut d’un nouveau projet sur Planification ou Idée, et non Actif.

* Activez l’option Créer des références automatiquement dans les préférences globales du projet.

* Cochez toutes les options de la section Analyses de rentabilité des préférences du projet système.

* Dans les préférences de résolution des problèmes, cochez l’option Mettre automatiquement à jour le statut Problème résolvable lorsque le statut de l’objet de résolution change.

</br>
</br>


## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Définissez le type de durée de tâche par défaut sur Simple.

**Voici pourquoi**

Les types de durée définissent la relation entre la durée de la tâche, les heures planifiées et le nombre de personnes affectées à la tâche.

Avec Simple comme valeur par défaut du système global, toutes les tâches créées manuellement ont ce type de durée. Les heures prévues sont réparties de manière égale entre les personnes affectées à la tâche sur toute la durée de celle-ci. Le type de durée Simple peut simplifier la planification du projet, car il permet d’apporter des modifications aux personnes désignées et aux heures prévues de la tâche sans affecter la durée de la tâche, la date de début prévue ou la date d’achèvement prévue.

</br>
</br>

**Bonne pratique**

Définissez la préférence de statut d’un nouveau projet sur Planification ou Idée, et non Actif.

**Voici pourquoi**

Le statut « Actif » indique que le projet est en cours et que des travaux sont en cours. Il est rare qu’un projet doive avoir ce statut dès sa création. Même si vous utilisez un modèle de projet, une certaine « planification » est nécessaire pour attribuer les tâches, ajuster la date d’achèvement prévue du projet, etc. Le statut Planification supprime également les notifications aux personnes assignées à la tâche et aux personnes membres de l’équipe de projet. La réception de notifications avant que le projet ne soit actif peut dérouter les personnes impliquées.

</br>
</br>

**Bonne pratique**

Activez l’option Créer des références automatiquement dans les préférences globales du projet.

**Voici pourquoi**

Chaque fois que vous changez le statut d’un projet sur Actif, Workfront enregistre automatiquement une référence du projet. Cet « instantané » du projet fournit des informations historiques sur la manière dont le plan du projet a évolué au fil du temps. Par exemple, vous pouvez comparer le plan de projet d’origine au plan actuel lorsque vous faites preuve de leadership quant à la façon dont les priorités changeantes ou la diminution de la portée ont affecté les délais du projet.

</br>
</br>

**Bonne pratique**

Cochez toutes les options de la section Analyses de rentabilité des préférences du projet système.

**Voici pourquoi**

Activez les cinq options pour permettre aux personnes chargées de la gestion de projet et de la planification ainsi qu’aux autres personnes d’inclure l’une ou l’autre de ces sections dans l’analyse de rentabilité d’un projet. Si les options ne sont pas activées, elles n’apparaissent pas dans la fenêtre de l’analyse de rentabilité. Les personnes peuvent laisser un champ vide s’il n’est pas nécessaire pour ce projet particulier, mais elles ne peuvent pas activer un champ au niveau du projet. Ces options ne peuvent être activées globalement que dans Configuration.

</br>
</br>

**Bonne pratique**

Dans les préférences de résolution des problèmes, cochez l’option Mettre automatiquement à jour le statut Problème résolvable lorsque le statut de l’objet de résolution change.

**Voici pourquoi**

Lorsqu’un problème est converti en projet, ce paramètre de préférence « lie » les statuts des deux éléments. La mise à jour du statut du projet (l’objet de résolution) mettra automatiquement à jour le statut du problème. Cela signifie que la personne à l’origine de la demande peut voir la progression de sa demande, même si elle n’est pas autorisée à voir l’intégralité du projet dans Workfront.
