---
title: Bonne pratique - Préférences pour les projets, les tâches et les problèmes
description: Examinez les recommandations relatives aux bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation de projets, de tâches et de préférences de publication Workfront.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
kt: 10918
exl-id: 321af897-3791-4b06-a9dd-241b5246b2a0
source-git-commit: 444f059d3cc26d8e3074a7145bc5419407c786cf
workflow-type: tm+mt
source-wordcount: '702'
ht-degree: 0%

---

# Bonne pratique - Préférences pour les projets, les tâches et les problèmes

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux préférences en matière de projet, de tâche et de problème

* Définissez le type de durée de tâche par défaut sur Simple.

* Définissez la préférence d’un nouveau projet sur Planification ou Idée, et non Actuelle.

* Activez l’option Créer des lignes de base automatiquement dans les préférences globales du projet.

* Cochez toutes les options de la section Analyses de cas des préférences du projet système.

* Dans les préférences de résolution des problèmes, cochez l’option Mettre automatiquement à jour le statut Problème résolvable lorsque l’état de l’objet de résolution change.

</br>
</br>


## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Définissez le type de durée de tâche par défaut sur Simple.

**Voici pourquoi**

Les types de durée définissent la relation entre la durée de la tâche, les heures planifiées et le nombre de personnes affectées à la tâche.

Avec Simple comme valeur par défaut du système global, toutes les tâches créées manuellement ont ce type de durée. Les heures planifiées sont divisées uniformément entre les personnes désignées de la tâche sur toute la durée. Le type Durée simple peut simplifier la planification du projet, car il permet d’apporter des modifications aux personnes désignées et aux heures planifiées de la tâche sans affecter la durée de la tâche, la date de début prévue ou la date d’achèvement prévue.

</br>
</br>

**Bonne pratique**

Définissez la préférence d’un nouveau projet sur Planification ou Idée, et non Actuelle.

**Voici pourquoi**

Un état actuel indique qu’un projet est actif et que le travail est en cours. Il est rare qu’un projet ait besoin d’être dans ce statut lors de sa création. Même si vous utilisez un modèle de projet, il existe une &quot;planification&quot; nécessaire à l’obtention des affectations de tâche, à l’ajustement de la date d’achèvement prévue du projet, etc. L’état Planification supprime également les notifications aux personnes désignées des tâches et aux membres de l’équipe de projet. La réception de notifications avant que le projet ne soit actif peut dérouter les personnes impliquées.

</br>
</br>

**Bonne pratique**

Activez l’option Créer des lignes de base automatiquement dans les préférences globales du projet.

**Voici pourquoi**

Chaque fois que vous définissez l’état d’un projet sur Actuel, Workfront enregistre automatiquement une référence de projet. Cet &quot;instantané&quot; du projet fournit des informations historiques sur la façon dont le plan du projet a changé au fil du temps. Par exemple, vous pouvez comparer le plan de projet d’origine au plan actuel lorsque vous faites preuve de leadership quant à la façon dont les priorités changeantes ou la perte de portée ont affecté les délais du projet.

</br>
</br>

**Bonne pratique**

Cochez toutes les options de la section Analyses de cas des préférences du projet système.

**Voici pourquoi**

Activez les cinq options pour permettre aux chefs de projet, aux planificateurs et aux autres personnes d’inclure l’une de ces sections dans l’analyse de performances d’un projet. Si les options ne sont pas activées, elles n’apparaissent pas dans la fenêtre de cas d’entreprise. Les utilisateurs peuvent laisser l’un des champs vides s’il n’est pas nécessaire pour ce projet particulier, mais ils ne peuvent pas activer un champ au niveau du projet. Ces options ne peuvent être activées globalement que dans Configuration.

</br>
</br>

**Bonne pratique**

Dans les préférences de résolution des problèmes, cochez l’option Mettre automatiquement à jour le statut Problème résolvable lorsque l’état de l’objet de résolution change.

**Voici pourquoi**

Lorsqu’un problème est converti en projet, ce paramètre de préférence &quot;associe&quot; les états des deux éléments. La mise à jour de l’état du projet (l’objet de résolution) met automatiquement à jour l’état du problème. Cela signifie que le demandeur peut voir la progression de sa demande, même s’il n’est pas autorisé à voir l’intégralité du projet dans Workfront.
