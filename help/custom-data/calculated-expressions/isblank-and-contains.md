---
title: Utiliser les expressions ISBLANK et CONTAINS
description: Découvrez comment utiliser et créer les expressions ISBLANK et CONTAINS dans un champ calculé dans Adobe [!DNL Workfront].
feature: System Setup and Administration
type: Tutorial
role: Admin, Leader, User
level: Experienced
activity: use
team: Technical Marketing
thumbnail: isblank-contains.png
exl-id: 819ffec8-e7e6-4a3c-a589-1348aa09e27d
source-git-commit: 37a222dd921c0c3ffe72a8e091f6dbf1f18cee68
workflow-type: tm+mt
source-wordcount: '404'
ht-degree: 0%

---

# Utiliser les expressions ISBLANK et CONTAINS

Les expressions CONTAINS et ISBLANK sont utilisées pour fournir des valeurs simples true ou false. La différence est que l’expression ISBLANK vérifie si le champ contient une valeur alors que l’expression de texte CONTAINS recherche une chaîne spécifique dans un champ.

Par exemple, pour voir si un projet a une description, utilisez l’expression ISBLANK. Si le champ de description est vide, l’expression renvoie la valeur true. Si le champ de description n’est pas vide, il renvoie la valeur false.

![Équilibreur de charge de travail avec rapport d’utilisation](assets/isblank01.png)

Pour rechercher une valeur spécifique dans la description, telle que &quot;événement caritatif&quot;, utilisez l’expression de texte CONTAINS . S’il trouve &quot;événement caritatif&quot; dans la description, le champ calculé indique &quot;true&quot;. Il affiche &quot;false&quot; s’il ne trouve pas &quot;événement caritatif&quot;.

![Équilibreur de charge de travail avec rapport d’utilisation](assets/isblank02.png)

## ISBLANK

L’expression de texte ISBLANK comprend le nom de l’expression et un point de données.

**ISBLANK({point de données})**

![Équilibreur de charge de travail avec rapport d’utilisation](assets/isblank03.png)

Dans l’exemple ci-dessus, où vous souhaitez savoir si le projet comporte une description, l’expression serait :

ISBLANK({description})

## CONTIENT

L’expression de texte CONTAINS inclut le nom de l’expression, le mot ou l’expression que vous recherchez et le champ à rechercher.

**CONTAINS(&quot;expression&quot;,{fields})**

Veillez à placer des guillemets autour du mot ou de l’expression que vous recherchez, sinon l’expression ne sera pas valide.

Dans l’exemple ci-dessus (en recherchant &quot;événement caritatif&quot; dans la description du projet), l’expression serait :

**CONTAINS(&quot;événement caritatif&quot;,{description})**

![Équilibreur de charge de travail avec rapport d’utilisation](assets/isblank04.png)

**Remarque**: L’expression CONTAINS est sensible à la casse. Par exemple, si &quot;Charity Event&quot; est mis en majuscules dans le champ de description, mettez cette expression en majuscules dans l’expression.

**CONTAINS(&quot;Charity Event&quot;,{description})**

Les expressions ISBLANK et CONTAINS sont très utiles si vous souhaitez voir si une valeur est présente. Cependant, il peut s’avérer plus utile de connaître la valeur, de la voir réellement ou d’avoir une sorte de descripteur pour fournir une meilleure information.

Par exemple, au lieu de simplement savoir qu’un projet a été converti à partir d’une requête, vous souhaitez connaître le nom de la requête d’origine.

Dans ce cas, utilisez l’expression CONTAINS conjointement avec une expression IF.

La plupart du temps, les expressions de texte ISBLANK et CONTAINS sont utilisées avec une expression de texte IF.
