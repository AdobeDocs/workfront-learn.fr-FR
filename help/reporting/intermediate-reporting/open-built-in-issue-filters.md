---
title: Explorer les filtres de problème intégrés
description: Découvrez comment examiner les filtres de problèmes intégrés pour déterminer comment ils sont construits et créer votre propre filtre de problèmes dans Workfront.
activity: use
feature: Reports and Dashboards
thumbnail: 336819.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
last-substantial-update: '2025-07-25T00:00:00.000Z'
jira: KT-9085
exl-id: c1bdea98-e70a-4e93-935c-b8f7754afa21
doc-type: video
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
subfeature_v2:
  - id: c68e30a0-f1f0-47be-a6a9-f26cd55c41a1
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
autotag-review: '2026-05-06T02:09:28.024Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 279
ht-degree: 96%

---

# Explorer les filtres de problème intégrés

Dans cette vidéo, vous allez :

* Examiner les filtres de problèmes intégrés pour déterminer comment ils sont construits
* Découvrir quelques éléments utiles de reporting de problèmes
* Apprendre à créer votre propre filtre de problèmes

>[!VIDEO](https://video.tv.adobe.com/v/3412678/?captions=fre_fr&quality=12&learn=on&enablevpops=0)


## Activités Comprendre les filtres de problèmes intégrés


### Activité : créer un rapport de problème

Vous voulez voir tous les problèmes qui doivent encore être résolus sur tous les projets actifs que vous possédez, y compris les problèmes avec un objet de résolution. Créez un rapport de problème et nommez-le « Problèmes non résolus sur les projets dont je suis propriétaire ».

### Réponse

Voici à quoi devrait ressembler le filtre :

![Image de l’écran permettant de créer un filtre de problèmes.](assets/opening-built-in-issue-filters-1.png)

Dans le filtre intégré « Mes problèmes ouverts », l’une des règles de filtrage excluait tous les problèmes pour lesquels il existait un objet de résolution. La raison en est que vous n’avez pas à vous préoccuper de ces problèmes. Une personne a déjà créé un projet, une tâche ou un problème qui les résoudra, alors pourquoi s’inquiéter ? Mais ils ne sont pas encore résolus et, dans notre exemple, nous les incluons pour qu’ils soient faciles à identifier et à vérifier.

Pour ce faire, vous devez ajouter une colonne dans l’onglet de vue « Problème > Objet de résolution ». Cela indique le nom de l’objet de résolution, s’il y en a un, qu’il s’agisse d’un projet, d’une tâche ou d’un problème. Cliquez sur le nom pour accéder à l’objet de résolution.

Vous pouvez regrouper la liste en fonction du nom du projet.

Voici à quoi devrait ressembler le rapport :

![Image d’un rapport de problème.](assets/opening-built-in-issue-filters-2.png)
