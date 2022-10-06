---
title: Réponses aux questions sur Forms personnalisé
description: Obtenez des réponses aux questions courantes sur les formulaires personnalisés.
feature: System Setup and Administration
type: Tutorial
role: Admin, Leader, User
level: Beginner, Intermediate
activity: use
team: Technical Marketing
kt: 10058
source-git-commit: 7cdce710ecc6fbcdccfe147a40623dc96f07ed2c
workflow-type: tm+mt
source-wordcount: '317'
ht-degree: 1%

---

# Questions courantes à propos des formulaires personnalisés

**Puis-je changer le type d&#39;affichage d&#39;un champ après l&#39;avoir créé ? Par exemple, puis-je passer d’un menu déroulant à des cases à cocher ?**

Oui. Le type d’affichage peut être basculé vers un autre type d’affichage similaire : texte au paragraphe, menu déroulant vers des cases à cocher ou des boutons radio, etc. Pour plus d’informations sur le changement de type d’affichage, voir l’article Créer un formulaire personnalisé .


**Puis-je utiliser le même formulaire personnalisé pour plusieurs objets ? Par exemple, un formulaire que j’ai créé pour une tâche à un projet ?**

Non. Les formulaires personnalisés ont une relation un-à-un avec un objet. Vous pouvez toutefois copier le formulaire personnalisé et remplacer l’objet par celui qui est nécessaire.


**Un formulaire personnalisé peut-il être joint à un modèle de projet ?**

Oui. Ainsi, tout projet créé à partir de ce modèle sera déjà associé au formulaire personnalisé.


**Le nombre de champs que je peux avoir sur un formulaire personnalisé est-il limité ?**

Vous pouvez ajouter jusqu’à 500 champs sur un seul formulaire personnalisé. Cependant, une dégradation des performances peut se produire lorsque plus de 100 champs existent sur un formulaire, selon la complexité de votre formulaire personnalisé. Parmi les exemples de formulaires complexes, citons les formulaires avec des paramètres en cascade, des champs de données personnalisés calculés et plusieurs options de valeur dans un champ donné.


**Existe-t-il une limite au nombre de formulaires personnalisés que je peux joindre à un projet ?**

Oui. Vous pouvez joindre jusqu’à 10 formulaires personnalisés à un objet. Pour plus d’informations, reportez-vous à cet article, Application d’un Forms personnalisé à des objets.


**Puis-je désactiver un formulaire personnalisé ?**

Oui. Dans l’onglet Paramètres de formulaire du formulaire personnalisé, décochez la case Est Principal . Cela supprime le formulaire personnalisé de tous les menus déroulants dans Workfront. Cependant, si le formulaire personnalisé est déjà joint à un projet, il reste et conserve toutes les données déjà saisies.