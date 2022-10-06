---
title: Bonne pratique - Aperçu d’un environnement de test
description: Découvrez les recommandations de bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation de l’environnement de prévisualisation Sandbox pour Workfront.
feature: Strategic Planning
role: Admin, Leader, User
level: Beginner
kt: 10917
exl-id: 5e172ad5-7e75-41cd-bce0-858095d13c6c
source-git-commit: 444f059d3cc26d8e3074a7145bc5419407c786cf
workflow-type: tm+mt
source-wordcount: '431'
ht-degree: 0%

---

# Bonne pratique - Aperçu d’un environnement de test

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives à l’aperçu des environnements de test

* Définissez, diagramme et testez les modifications apportées aux processus ou paramètres Workfront existants dans l’environnement Preview Sandbox avant d’effectuer des mises à jour dans votre instance de production.

</br>
</br>

## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Définissez, diagramme et testez les modifications apportées aux processus ou paramètres Workfront existants dans l’environnement Preview Sandbox avant d’effectuer des mises à jour dans votre instance de production.

**Voici pourquoi**

L’environnement de prévisualisation Sandbox sert de réplique à votre environnement en ligne. Bien qu’il ne soit pas recommandé de créer un environnement complet dans l’environnement de test avant de le créer dans l’instance de production, car cela crée un travail supplémentaire, il est conseillé de l’utiliser comme environnement de test pour les modifications que vous souhaitez implémenter.

Effectuer des tests d’acceptation par les utilisateurs (UAT) et impliquer des utilisateurs sélectionnés lors de la phase de test d’une modification peut vous aider à mieux comprendre les besoins et les workflows de vos utilisateurs. Il s’agit d’un excellent moyen d’améliorer les processus Workfront et de les adopter au sein de votre entreprise.


**Remarque**: Chaque modification que vous souhaitez implémenter dans Workfront n’a pas à être créée dans l’environnement de prévisualisation Sandbox en premier. De nombreuses modifications Workfront, comme la création d’une file d’attente de demandes ou d’un modèle de projet, peuvent être effectuées dans l’environnement de production. Lors du test dans l’instance de production, une bonne règle consiste à contrôler la visibilité de vos objets jusqu’à ce que vous soyez prêt à publier pour une plus grande audience. Veillez à supprimer tout ce que vous n’avez pas l’intention d’utiliser afin que le système reste propre et gérable.
