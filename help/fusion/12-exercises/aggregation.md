---
title: Exercice d’agrégation
description: Découvrez comment agréger plusieurs bundles d’informations en une seule valeur.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11047
thumbnail: KT11047.png
recommendations: noDisplay,catalog
exl-id: 4626b623-8b05-41be-9cfc-917e28222855
product_v2: id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2: id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
subfeature_v2: id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
autotag-review: '2026-05-06T16:46:06.511Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 302
ht-degree: 100%

---

# Exercice d’agrégation

Découvrez comment agréger plusieurs bundles d’informations en une seule valeur.

## Vue d’ensemble de l’exercice

En utilisant le scénario « Introduction à l’itération » que vous avez créé lors de l’exercice précédent, agrégez le nombre d’heures prévues sur chaque tâche opérationnelle du projet et envoyez-vous un e-mail contenant ces informations.

![Image d’agrégation 1](../12-exercises/assets/aggregation-walkthrough-1.png)

## Étapes à suivre

**Ajoutez un filtre et faites la SOMME du nombre d’heures prévues.**

1. Clonez le scénario « Introduction à l’itération » que vous avez créé lors de l’exercice précédent et nommez-le « Introduction à l’agrégation ».
1. Ajoutez un filtre entre le module Lire les tâches du projet et le module Compter le nombre de tâches. Nommez le filtre « Uniquement les tâches opérationnelles ».
1. Définissez la condition sur Nombre d’enfants [Opérateur numérique : égal à] 0.

   ![Image d’agrégation 2](../12-exercises/assets/aggregation-walkthrough-2.png)

1. Après le module Math aléatoire, ajoutez un module d’outil Agrégateur numérique.
1. Définissez le module source sur Lire les tâches du projet.
1. Définissez la fonction Agrégat sur SOMME.
1. Définissez la Valeur sur le champ Travail à partir du module Lire les tâches du projet.
1. Renommez ce module « SOMME de toutes les heures de planification de la tâche ».

   ![Image d’agrégation 3](../12-exercises/assets/aggregation-walkthrough-3.png)

   **Notez l’ombre qui indique que l’agrégation termine l’itération.**

   ![Image d’agrégation 4](../12-exercises/assets/aggregation-walkthrough-4.png)

   **Envoyez un e-mail avec les heures agrégées.**

1. Ajoutez un module Envoyer un e-mail à partir de l’application de messagerie, après l’agrégateur numérique.
1. Envoyez-vous l’e-mail.
1. L’objet est « Détails du projet ».
1. Dans le champ Contenu, indiquez « Il existe un projet appelé [nom du projet] qui a un nombre total du [résultat] d’heures prévues ». Le « [nom du projet] » provient du module Lecture d’un enregistrement et « [résultat] » provient du module d’agrégation.

   ![Image d’agrégation 5](../12-exercises/assets/aggregation-walkthrough-5.png)

1. Enregistrez et exécutez une fois. Recherchez l’e-mail dans votre boîte de réception.

Au sein de l’itération, il est possible d’accéder aux différents paquets. En dehors de l’itération, dans le module Envoyer un e-mail, seuls les champs agrégés sont accessibles.
