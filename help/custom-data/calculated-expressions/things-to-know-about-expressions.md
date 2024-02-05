---
title: Informations à connaître sur les expressions de champ calculées
description: Découvrez la liste des concepts utiles pour l’utilisation des champs calculés personnalisés dans  [!DNL Workfront].
feature: Custom Forms
type: Tutorial
role: Admin, Leader, User
level: Experienced
activity: use
team: Technical Marketing
thumbnail: to-know-expressions.png
exl-id: 512a3071-f47f-4fd4-bf5f-9b18bef8ba59
source-git-commit: 409147f9a62302d28e14b834981992a0421d4e4b
workflow-type: ht
source-wordcount: '959'
ht-degree: 100%

---

# Informations à connaître sur les expressions de champ calculées

Voici une liste des concepts à connaître lorsque vous utilisez des champs calculés personnalisés dans Workfront.

## La casse est importante dans les noms d’expression.

En matière de noms d’expression, la casse est importante. Lors de l’écriture initiale d’un nom d’expression, vous pouvez utiliser des majuscules, des minuscules ou un mélange des deux.

![Message d’erreur sans majuscules dans le nom de l’expression](assets/T2K01.png)

Cependant, l’expression doit être écrite tout en majuscules pour que le système reconnaisse l’expression et enregistre le champ.



## Les heures sont enregistrées sous forme de minutes.

Dans la base de données de Workfront, les heures sont enregistrées sous forme de minutes. Si vous référencez des champs tels que Nombre d’heures prévues ou Heures effectives, divisez par 60 pour afficher l’heure en heures et non en minutes.

## L’espacement n’influe pas sur les expressions.

La méthode recommandée pour écrire des expressions consiste à utiliser peu ou pas d’espacement entre chaque expression.

* IF(ISBLANK({description}),&quot;No Description&quot;,&quot;Has Description&quot;)

![Expressions sans espacement entre les champs](assets/T2K02.png)

Toutefois, si l’espacement permet de mieux voir ce qui se passe, il peut être ajouté aux expressions. Les espaces supplémentaires ne doivent pas empêcher l’expression de collecter ou de calculer une valeur dans [!DNL Workfront].

* IF (ISBLANK ({description}), &quot;No Description&quot; , &quot;Has Description&quot; )

![Expressions avec espacement entre les champs](assets/T2K03.png)

Les seuls éléments qui ne peuvent pas être séparés par des espaces sont les champs et les accolades. Sinon, vous recevrez un message d’erreur et ne pourrez pas enregistrer le champ ou le formulaire personnalisé.

![Erreur avec l’espacement entre le nom du champ et l’accolade](assets/T2K04.png)

## Les guillemets doivent être droits.

Lorsque vous utilisez des guillemets dans une expression, veillez à ce qu’ils soient droits (&quot;). Si les guillemets sont incurvés (&quot;), le système [!DNL Workfront] continuera à afficher le message « Expression personnalisée non valide ».

![Erreur avec des guillemets courbes](assets/T2K05.png)

## Mise à jour des calculs lors de l’enregistrement de formulaire et de la modification d’objet

Cet aspect des champs calculés doit être bien compris.

Les informations affichées dans un champ calculé restent les mêmes et deviennent obsolètes, sauf si le formulaire personnalisé est recalculé.

Vous pouvez actualiser les expressions à l’aide de l’option Recalculer les expressions du menu Plus d’un objet.

Vous souhaitez connaître le nombre de jours pendant lesquels une question a été ouverte. Créez un champ calculé appelé « Jours d’ouverture » avec l’expression DATEDIFF.

* Nom du champ = Jours d’ouverture
* Expression = DATEDIFF({entryDate},$$TODAY)

Une fois enregistré, le nombre de jours entre la création du problème ou sa saisie dans Workfront, et la date du jour peut être affiché sur la page de détails d’un objet ou dans une vue de rapport.

Lorsque vous consultez la même page de détails ou le même rapport le lendemain, ce nombre devrait être incrémenté d’une unité. Si le nombre est de 5 aujourd’hui, il doit être de 6 demain. Le jour suivant, il doit être de 7, puis de 8, etc.

Cependant, le champ continuera d’afficher 5 chaque jour. Pour que les informations soient actualisées, le champ doit être « réexécuté ».

Pour mettre à jour un champ à l’aide de l’option Recalculer les expressions :

* Cliquez sur le nom de l’objet pour l’ouvrir.
* Cliquez sur le menu Plus.
* Sélectionnez Recalculer les expressions dans la liste.

![Option Recalculer l’expression dans l’objet](assets/T2K06.png)

Vous pouvez également recalculer plusieurs expressions en même temps en utilisant la fonction « modifier en masse » dans une liste ou un rapport. Supposons que vous ayez créé un rapport présentant une liste de problèmes, le calcul des jours d’ouverture apparaissant dans une colonne. Si vous souhaitez recalculer tous les problèmes à la fois :

* Sélectionnez tous les problèmes du rapport.
* Sélectionnez l’option Modifier pour modifier en masse tous les problèmes sélectionnés.
* Cliquez sur le libellé Formulaires personnalisés à gauche pour accéder à la section Formulaires personnalisés.
* Cochez la case Recalculer les expressions personnalisées au bas de la section Formulaires personnalisés.
* Cliquez sur Enregistrer les modifications.

![Option Recalculer l’expression pour plusieurs objets](assets/T2K07.png)

L’écran s’actualise pour afficher les informations mises à jour dans le champ calculé.

**Remarque** : bien qu’il existe d’autres façons de mettre à jour ou de recalculer les expressions dans un champ calculé, il s’agit de la méthode la plus simple et la plus rapide.

## Les calculs peuvent varier d’un formulaire à l’autre dans un même champ.

Dès qu’un champ calculé est enregistré dans un formulaire personnalisé et que le formulaire personnalisé est enregistré, le champ calculé est ajouté à la bibliothèque de champs afin de pouvoir être utilisé dans d’autres formulaires personnalisés.

Cependant, si vous avez un champ calculé dans le formulaire A et le même champ calculé dans le formulaire B, on pourrait penser de prime abord que les calculs sont exactement les mêmes. Ce n’est pas toujours le cas. Le champ calculé dans le formulaire A peut être calculé d’une manière totalement différente dans le formulaire B.

Lorsqu’un champ personnalisé calculé est sélectionné dans la bibliothèque de champs et ajouté à un formulaire personnalisé, le champ est ajouté mais le calcul est vide. Cela est dû au fait que le calcul peut faire référence à des champs qui n’existent pas pour un autre type d’objet.

Par exemple, vous avez créé un champ calculé « Jours nécessaires pour terminer », pour déterminer le temps nécessaire pour terminer une tâche dans un projet.

* WEEKDAYDIFF({actualStartDate},{actualCompletionDate})

Vous voulez faire la même chose pour une itération. Vous pouvez utiliser la même expression. Cependant, les champs disponibles pour un objet de tâche ne sont pas toujours disponibles pour un objet d’itération. Donc [!DNL Workfront] vous donne la possibilité de créer le calcul avec les champs d’objet appropriés.

**Astuce** : copiez l’expression calculée de la boîte de dialogue Calcul vers le champ Instructions lors de la création de champs personnalisés. Ce champ n’est pas effacé lorsqu’un champ personnalisé calculé est ajouté au formulaire personnalisé à partir de la bibliothèque de champs.

En fonction des besoins, les champs calculés dans les formulaires personnalisés peuvent être très simples ou très complexes. Les expressions peuvent incorporer, ou imbriquer, d’autres expressions et valeurs afin de fournir le niveau de détail nécessaire pour mieux comprendre les rouages du travail effectué au sein de votre organisation.

<!--Depending on the need, calculated fields in custom forms can be quite simple or very complex. Expressions can embed, or nest, other expressions and values to provide the level of detail needed to get a better picture of what is going on with the work being done at your organization. 

Most of the examples and exercises in this course have been relatively simple to provide a base understanding of the expressions most commonly used and how to build those expressions in a custom calculated field. 

Now you're ready to start building your own calculated custom fields.-->
