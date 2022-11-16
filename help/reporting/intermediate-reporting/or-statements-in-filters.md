---
title: Création d’instructions OU dans des filtres
description: Découvrez comment utiliser une instruction OU pour indiquer à Workfront que vous souhaitez afficher cet OU dans votre rapport.
activity: use
team: Technical Marketing
feature: Reports and Dashboards
thumbnail: create-or-statements-in-filters.png
type: Tutorial
role: User
level: Intermediate
kt: 9987
exl-id: 1a56f2f6-12df-43a5-943c-986a85661efa
source-git-commit: 252ba3ba44f22519a35899fcda9c6bca597a6c2c
workflow-type: tm+mt
source-wordcount: '901'
ht-degree: 0%

---

# Création d’instructions OU dans des filtres

Lorsque vous créez un filtre avec plusieurs lignes de critères, place par défaut un ET entre chaque ligne. Cela signifie que chaque résultat dans la liste lorsque vous utilisez ce filtre répond à toutes les règles de filtrage.

Dans cet exemple, nous avons trois critères, ou règles, pour un filtre de projet :

1. La date d’achèvement prévue du projet doit être fixée au mois en cours.
1. Le projet doit se trouver dans le portefeuille Marketing des événements.
1. Le projet doit être un principal projet, ce qui signifie qu’il doit avoir le statut Actuel.

![Image de création d’un filtre avec des instructions ET dans [!DNL Workfront]](assets/or-statement-1.png)

Les projets figurant dans la liste des résultats répondent à ces trois critères, ce qui vous permet de réduire les résultats de la recherche pour vous permettre de consulter les informations exactes dont vous avez besoin.

![Image d’une liste filtrée dans [!DNL Workfront]](assets/or-statement-2.png)

Cependant, il peut arriver que vous souhaitiez que les résultats du filtre répondent à différents critères, et c’est à ce moment-là que les instructions OU peuvent vous aider. Avec une instruction OR, vous indiquez au filtre que vous souhaitez voir cet OR.

## Utilisation d’instructions OR

Les instructions OR étendent ou augmentent la quantité d’informations trouvées par le filtre car, pour s’afficher dans la liste de résultats, un élément ne doit respecter qu’une seule des règles de filtre, pas toutes.

Examinons une instruction OU simple : les projets que vous êtes le chef de projet (propriétaire) pour les projets OU que vous avez créés.

![Image de création d’un filtre avec des instructions OU dans [!DNL Workfront]](assets/or-statement-3.png)

Après avoir configuré les deux règles de filtrage, cliquez sur l’opérateur ET entre elles et basculez-le sur OU.

![Image de création d’un filtre avec des instructions OU dans [!DNL Workfront]](assets/or-statement-4.png)

L’opérateur OU entre les deux règles de filtrage étend vos critères de recherche, en demandant à Workfront de rechercher les projets qui correspondent à l’une ou l’autre de ces options. Votre nom figure dans le champ propriétaire du projet ou vous êtes la personne qui a créé le projet.

## Règles de filtrage multiples avec instructions OR

Examinons maintenant une instruction OU qui contient plusieurs règles de filtrage de chaque côté de l’OR. Cette règle utilise les mêmes deux règles que précédemment, mais ajoute une règle : les projets doivent également avoir l’état Actuel .

![Image de création d’un filtre avec des instructions OU dans [!DNL Workfront]](assets/or-statement-5.png)

Notez que Workfront &quot;a regroupé&quot; les règles de filtrage de chaque côté de l’OR (il y a une zone grise autour d’elles). Cela indique à Workfront d’exécuter les règles de chaque côté de l’OU ensemble, en recherchant les projets qui répondent à ces deux critères car ils sont associés à l’opérateur AND.

Dans cet exemple, Workfront recherche les éléments suivants :

* Projets dont le nom figure dans le champ du propriétaire du projet et dont l’état est également Actuel.
* **PLUS (OU)**
* Les projets que vous avez créés ont également l’état Actuel.

Placer la règle &quot;état du projet égal à actuel&quot; de chaque côté de l’OU garantit que la règle fonctionne conjointement avec les autres règles. Cette règle commune est parfois appelée &quot;constante&quot;.

>[!NOTE]
>
>Vous n’êtes pas limité à une règle de filtrage répétée de chaque côté de l’OR. En fonction de vos besoins, vous pouvez en avoir plusieurs. Workfront recommande de conserver au minimum ces règles répétées, afin de s’assurer que le filtre fournit les résultats dont vous avez besoin.

## Que se passe-t-il sans la règle de filtre commune ?

Sans la ou les règles de filtrage courantes, vous risquez de ne pas obtenir les résultats de recherche que vous aviez attendus.

Par exemple, si vous placez la règle &quot;état du projet égal à actuel&quot; uniquement d’un côté de l’OU, elle ne fonctionne qu’avec les autres règles de filtrage de cette section. Dans l’image ci-dessous, la règle &quot;l’état du projet est égal à Actuel&quot; apparaît uniquement dans la section supérieure.

![Image de création d’un filtre avec des instructions OU dans [!DNL Workfront]](assets/or-statement-6.png)

Cela signifie que Workfront recherche les éléments suivants :

* Projets dont le nom figure dans le champ du propriétaire du projet et dont l’état est Actuel.
* **PLUS (OU)**
* Tous les projets que vous avez créés.

Comme vous pouvez le voir, cette configuration de filtre donne des résultats légèrement différents de ceux du filtre avec la règle de filtre répétée. C’est pourquoi il est important de s’assurer que le filtre est correctement configuré pour vous assurer que vous obtenez les résultats souhaités et dont vous avez besoin.

Vous ne pouvez pas utiliser fréquemment des instructions OU lors de la création de filtres. Mais cela peut vous aider à réduire le nombre de filtres que vous devez créer. Assurez-vous simplement que vos filtres ne renvoient pas trop de résultats : une longue liste peut rendre plus difficile la recherche des informations exactes requises pour les utilisateurs.

## Activité de filtre OU

Vous souhaitez trouver des tâches incomplètes qui vous sont assignées ou qui ne sont assignées à personne. Vous configurez un filtre qui ressemble à celui ci-dessous. Ce filtre vous donnera-t-il les résultats que vous souhaitez ? Pourquoi ou pourquoi pas ?

![Image d’une instruction OU incorrectement créée dans [!DNL Workfront]](assets/or-statement-your-turn-1.png)

### Réponses

Non, ce filtre ne fournira pas les résultats que vous espérez (tâches qui ne sont pas terminées et qui vous sont affectées ou qui ne sont affectées à personne), car la règle de filtrage pour l’état de la tâche se trouve uniquement d’un côté de l’OR.

Ce filtre génère plutôt une liste qui affiche :

* Tâches qui vous sont affectées et dont l’état est En cours ou Nouveau.
* **PLUS (OU)**
* Toutes les tâches non affectées, quel que soit l’état.

Le filtre doit ressembler à celui ci-dessous. Notez que ce filtre comporte la règle de filtrage pour l’état de la tâche des deux côtés de l’OR.

![Image d’une instruction OU correctement créée dans [!DNL Workfront]](assets/or-statement-your-turn-2.png)
