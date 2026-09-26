---
title: Réponses aux questions à propos des formulaires personnalisés
description: Obtenez des réponses aux questions courantes sur les formulaires personnalisés.
feature: Custom Forms
type: Tutorial
role: Admin, Leader, User
level: Beginner, Intermediate
activity: use
team: Technical Marketing
jira: KT-10058
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
    internal-label: Leader
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
    internal-label: Beginner
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
source-git-commit: 54883ad8c8df3aaee06ba8f8dca64227594c1c77
workflow-type: tm+mt
source-wordcount: '326'
ht-degree: 88%
---
# Questions courantes sur les formulaires personnalisés

**Puis-je modifier le type d’affichage d’un champ après l’avoir créé ? Par exemple, puis-je passer d’un menu déroulant à des cases à cocher ?**

Oui. Le type d’affichage peut être remplacé par un autre type similaire : du texte au paragraphe, des listes déroulantes aux cases à cocher ou aux boutons radio, etc. Pour plus d’informations sur la modification du type d’affichage, consultez l’article Création d’un formulaire personnalisé .


**Puis-je utiliser le même formulaire personnalisé pour plusieurs objets ? Par exemple, un formulaire que j’ai créé pour une tâche, sur un projet ?**

Non. Les formulaires personnalisés possèdent une relation de un-à-un avec un objet. Vous pouvez toutefois copier le formulaire personnalisé puis remplacer l’objet par l’objet souhaité.


**Un formulaire personnalisé peut-il être associé à un modèle de projet ?**

Oui. Ainsi, le formulaire personnalisé sera déjà associé à tout projet créé à partir de ce modèle.


**Le nombre de champs dont je peux disposer sur un formulaire personnalisé est-il limité ?**

Vous pouvez ajouter jusqu’à 500 champs sur un seul formulaire personnalisé. Cependant, une dégradation des performances peut se produire lorsque le formulaire comporte plus de 100 champs, en fonction de la complexité de votre formulaire personnalisé. Parmi les exemples de formulaires complexes, citons les formulaires avec des paramètres en cascade, des champs de données personnalisés calculés et plusieurs options de valeur dans un champ donné.


**Le nombre de formulaires personnalisés que je peux associer à un projet est-il limité ?**

Oui. Vous pouvez associer jusqu’à 10 formulaires personnalisés à un objet. Pour plus d’informations, reportez-vous à l’article Appliquer des formulaires personnalisés à des objets.


**Puis-je désactiver un formulaire personnalisé ?**

Oui. Dans l’onglet Paramètres du formulaire personnalisé, décochez la case Actif. Cette opération supprime le formulaire personnalisé de tous les menus déroulants de Workfront. Cependant, si le formulaire personnalisé est déjà associé à un projet, il reste présent et conserve toutes les données déjà saisies.