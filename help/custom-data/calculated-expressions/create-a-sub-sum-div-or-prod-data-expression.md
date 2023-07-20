---
title: Créer une expression de données SOB, SUM, DIV ou PROD
description: Découvrez comment utiliser et créer les expressions mathématiques de base dans un champ calculé dans Adobe [!DNL Workfront].
feature: Custom Forms
type: Tutorial
role: Admin, Leader, User
level: Experienced
activity: use
team: Technical Marketing
thumbnail: 335177.png
jira: KT-8914
exl-id: e767b73b-1591-4d96-bb59-2f2521e3efa3
doc-type: video
source-git-commit: 409147f9a62302d28e14b834981992a0421d4e4b
workflow-type: tm+mt
source-wordcount: '380'
ht-degree: 0%

---

# Créer une expression de données SOB, SUM, DIV ou PROD

Dans cette vidéo, vous apprendrez :

* Ce que font les expressions SUB, SUM, DIV et PROD
* Comment créer une expression de données SOB dans un champ calculé

>[!VIDEO](https://video.tv.adobe.com/v/335177/?quality=12&learn=on)

## Informations supplémentaires : Expression ROUND

### Création d’une expression ROUND

L’expression ROUND prend n’importe quel nombre et l’arrondit à un certain nombre de décimales.

La plupart du temps, l’expression de données ROUND est utilisée conjointement avec une autre expression de données et lorsque le champ de format est conservé sous la forme Texte ou Nombre.

Créez un champ calculé afin de déterminer la différence entre le nombre d’heures prévu et réellement connecté à une tâche, qui nécessitera l’expression SOUS-B et se présentera comme suit :

**SUB({workRequired},{actualWorkRequired})**

Et puisque le temps est suivi en minutes et que le format préféré est d&#39;afficher l&#39;information en heures, l&#39;expression doit également être divisée par 60 et se présenter comme suit :

**DIV(SUB({workRequired},{actualWorkRequired}),60)**

Si le format est remplacé par Nombre lors de la création du champ calculé dans le formulaire personnalisé, vous pouvez modifier le format du nombre lors de l’ajout du champ dans une vue.

![Équilibreur de charge de travail avec rapport d’utilisation](assets/round01.png)

Cependant, si le format du champ lors de la création d’un champ personnalisé est laissé sous la forme Texte, il ne peut pas être facilement modifié dans la vue. L’expression ROUND doit être utilisée pour éviter de voir des nombres comme celui-ci dans votre projet :

![Équilibreur de charge de travail avec rapport d’utilisation](assets/round02.png)

<b>Utiliser l’expression de données ROUND dans un champ calculé</b>

L’expression ROUND comprend le nom de l’expression (ROUND) et, généralement, deux points de données. Ces points de données peuvent être une expression ou un champ dans Workfront, suivis d’un nombre pour indiquer le nombre de décimales que vous souhaitez ajouter.

Une expression serait structurée comme suit : ROUND(point de données, #)

Dans l’expression calculant la différence entre les heures prévues et les heures réelles, utilisez cette expression —DIV(SUB({workRequired},{actualWorkRequired}),60), comme premier point de données. Assurez-vous ensuite que le nombre provenant de cette expression ne dépasse pas 2 chiffres à droite de la décimale.

![Équilibreur de charge de travail avec rapport d’utilisation](assets/round03.png)

L’expression peut être écrite comme suit : ROUND(DIV(SUB({workRequired},{actualWorkRequired}),60),2).
