---
title: Créer des instructions OR dans les filtres
description: Découvrez comment utiliser une instruction OR pour indiquer à Workfront que vous voulez voir ceci OU cela dans votre rapport.
activity: use
team: Technical Marketing
feature: Reports and Dashboards
thumbnail: create-or-statements-in-filters.png
type: Tutorial
role: User
level: Intermediate
jira: KT-9987
exl-id: 1a56f2f6-12df-43a5-943c-986a85661efa
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '915'
ht-degree: 100%

---

# Créer des instructions OR dans les filtres

Lorsque vous créez un filtre avec plusieurs lignes de critères, Workfront place par défaut le mot AND entre chaque ligne. Cela signifie que chaque résultat de la liste sur laquelle ce filtre est appliqué répond à toutes les règles de filtrage.

Dans cet exemple, nous avons trois critères, ou règles, pour un filtre de projet :

1. La date d’achèvement prévue du projet doit être fixée pendant le mois en cours.
1. Le projet doit faire partie du portfolio de marketing événementiel.
1. Le projet doit être actif, c’est-à-dire qu’il doit avoir le statut « En cours ».

![Une image de la création d’un filtre à l’aide d’instructions AND dans [!DNL Workfront]](assets/or-statement-1.png)

Les projets figurant dans la liste des résultats répondent à ces trois critères, ce qui vous permet d’affiner les résultats de la recherche afin d’obtenir les informations exactes dont vous avez besoin.

![Une image d’une liste filtrée dans [!DNL Workfront]](assets/or-statement-2.png)

Cependant, il peut arriver que vous souhaitiez filtrer les résultats selon des critères différents, et c’est là que les instructions OR peuvent se révéler utiles. Avec une instruction OR, vous indiquez que vous voulez voir les éléments qui correspondent à N’IMPORTE laquelle de vos instructions OR, et non à TOUTES vos instructions AND.

## Utiliser les instructions OR

Les instructions OR élargissent ou augmentent la quantité d’informations trouvées par le filtre car, pour apparaître dans la liste des résultats, un élément ne doit satisfaire qu’une seule des règles du filtre, et non toutes.

Prenons une simple déclaration OR : vous êtes le ou la chef de projet (propriétaire) de projets OR que vous avez créés.

![Une image de la création d’un filtre avec des instructions OR dans [!DNL Workfront]](assets/or-statement-3.png)

Après avoir défini les deux règles de filtrage, cliquez sur AND entre les deux et basculez sur OR.

![Une image de la création d’un filtre avec des instructions OR dans [!DNL Workfront]](assets/or-statement-4.png)

L’instruction OR entre les deux règles de filtrage élargit vos critères de recherche, indiquant à Workfront de trouver les projets qui répondent à l’une ou l’autre de ces options : votre nom figure dans le champ du ou de la propriétaire du projet ou vous êtes la personne qui a créé le projet.

## Règles de filtrage multiples avec instructions OR

Examinons maintenant une instruction OR qui contient plusieurs règles de filtrage de chaque côté. Cette méthode utilise les deux mêmes règles que précédemment, mais en ajoute une autre : les projets doivent également avoir le statut « En cours ».

![Une image de la création d’un filtre avec des instructions OR dans [!DNL Workfront]](assets/or-statement-5.png)

Remarquez que Workfront a « regroupé » les règles de filtrage de chaque côté de l’instruction OR (elles sont entourées d’une bordure grise). Cela indique à Workfront d’exécuter les règles de chaque côté de l’instruction OR ensemble, en trouvant des projets qui répondent à ces deux critères parce qu’ils sont reliés par le mot AND.

Dans cet exemple, Workfront recherche :

* Les projets pour lesquels votre nom figure dans le champ du ou de la propriétaire du projet et dont le statut est également « En cours ».
* **PLUS (OR)**
* Les projets que vous avez créés et dont le statut est également « En cours ».

Le fait de placer la règle « Le statut du projet est égal à En cours » de chaque côté de l’instruction OR permet de s’assurer que cette règle fonctionne conjointement avec chacune des autres règles. Cette règle commune est parfois appelée « constante ».

>[!NOTE]
>
>Il n’est pas obligatoire de se limiter à une règle de filtrage répétée de chaque côté de l’instruction OR. En fonction de vos besoins, vous pouvez en avoir plusieurs. Workfront recommande de limiter autant que possible ces règles répétées, afin que le filtre fournisse les résultats dont vous avez besoin.

## Que se passe-t-il sans la règle du filtre commun ?

Si vous n’utilisez pas la règle du filtre commun, vous risquez de ne pas obtenir les résultats de recherche escomptés.

Par exemple, si vous placez la règle « Le statut du projet est égal à En cours » uniquement d’un côté de l’instruction OR, cela ne fonctionnera qu’avec les autres règles de filtrage de cette section. Dans l’image ci-dessous, vous voyez que la règle « Le statut du projet est égal à En cours » se trouve uniquement dans la partie supérieure.

![Une image de la création d’un filtre avec des instructions OR dans [!DNL Workfront]](assets/or-statement-6.png)

Cela signifie que Workfront recherchera :

* Des projets pour lesquels votre nom figure dans le champ du ou de la propriétaire du projet et dont le statut est « En cours ».
* **PLUS (OR)**
* Tous les projets que vous avez créés.

Comme vous pouvez le constater, cette configuration de filtre donne des résultats légèrement différents de ceux du filtre ayant la règle de filtre répété. C’est pourquoi il est important de s’assurer que le filtre est correctement configuré pour que vous obteniez les résultats souhaités et dont vous avez besoin.

Les instructions OR ne sont pas forcément recommandées lors de la création de filtres. Mais elles peuvent vous aider à réduire le nombre de filtres à créer. Veillez simplement à ce que vos filtres ne renvoient pas trop de résultats - une longue liste peut rendre la recherche plus difficile pour les utilisateurs et utilisatrices.

## Activité du filtre OR

Vous voulez trouver les tâches incomplètes qui vous sont attribuées ou qui ne sont attribuées à personne. Vous configurez un filtre qui ressemble à celui présenté ci-dessous. Ce filtre vous donnera-t-il les résultats que vous souhaitez ? Pourquoi ou pourquoi pas ?

![Image d’une instruction OR créée de manière incorrecte dans [!DNL Workfront]](assets/or-statement-your-turn-1.png)

### Réponses

Non, ce filtre ne fournira pas les résultats que vous espérez (les tâches non terminées qui vous sont assignées ou qui ne sont assignées à personne) parce que la règle de filtrage pour le statut de la tâche ne concerne qu’un seul aspect de l’instruction OU.

Au lieu de cela, ce filtre génère une liste qui indique :

* Les tâches qui vous sont attribuées et dont le statut est En cours ou Nouveau.
* **PLUS (OR)**
* Toutes les tâches non assignées, quel que soit leur statut.

Le filtre doit ressembler à l’illustration ci-dessous. Remarquez que ce filtre comporte la règle de filtrage du statut de la tâche des deux côtés de l’instruction OU.

![Image d’une instruction OR correctement créée dans [!DNL Workfront]](assets/or-statement-your-turn-2.png)
