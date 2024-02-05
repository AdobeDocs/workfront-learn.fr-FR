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
source-git-commit: 409147f9a62302d28e14b834981992a0421d4e4b
workflow-type: ht
source-wordcount: '317'
ht-degree: 100%

---

# Questions courantes sur les formulaires personnalisés

**Puis-je modifier le type d’affichage d’un champ après l’avoir créé ? Par exemple, puis-je passer d’un menu déroulant à des cases à cocher ?**

Oui. Le type d’affichage peut être remplacé par un autre type d’affichage similaire : de texte à paragraphe, de liste déroulante aux cases à cocher ou boutons radio, etc.  Pour plus d’informations sur le changement de type d’affichage, reportez-vous à l’article Créer un formulaire personnalisé.


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