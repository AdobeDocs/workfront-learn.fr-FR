---
title: Comprendre les filtres EXISTS
description: Découvrez ce qu’est un filtre EXISTS, ce qu’il peut vous apporter et comment en créer un à partir de zéro. Consultez également de nombreux exemples utiles de filtres EXISTS.
activity: use
team: Technical Marketing
feature: Reports and Dashboards
type: Tutorial
role: User
level: Intermediate
jira: KT-1880
last-substantial-update: 2025-08-25T00:00:00Z
doc-type: video
exl-id: f518a919-0c44-4122-873a-e2f10e3162d5
source-git-commit: bbdf99c6bc1be714077fd94fc3f8325394de36b3
workflow-type: tm+mt
source-wordcount: '682'
ht-degree: 100%

---

# Comprendre les filtres EXISTS

Les filtres EXISTS sont des filtres avancés en mode texte, qui nous permettent de contourner la limitation de 2 sauts de table/champ dans un créateur de rapports standard. Ils peuvent également être utilisés pour identifier des objets du système qui ne sont pas associés à une condition de relation spécifique via NOTEXISTS.

Dans cette vidéo, vous apprendrez à créer un filtre EXISTS pour voir « Approbations d’épreuves pour les projets actuels » dans un rapport d’approbation d’épreuves.

Pour une présentation plus détaillée du fonctionnement de l’instruction EXISTS, reportez-vous à la documentation [Créer des filtres complexes en mode texte à l’aide d’instructions EXISTS](https://experienceleague.adobe.com/fr/docs/workfront/using/reporting/reports/text-mode/create-complex-text-mode-filters-using-exists-statements).

>[!VIDEO](https://video.tv.adobe.com/v/3471205/?quality=12&learn=on&enablevpops=1&captions=fre_fr)

## Exemples de filtres EXISTS

### Rapport de projet avec instruction EXISTS

Cette méthode utilise la tâche comme objet de liaison, en comparant l’ID de projet trouvé au niveau de la tâche et en le faisant correspondre au champ ID au niveau du projet. Cela nous permet de comparer ensuite les utilisateurs et utilisatrices de l’affectation sur la tâche à un caractère générique $$USER.ID. Cela renvoie uniquement les projets pour lesquels la personne qui consulte est affectée à une tâche, qu’elle soit ou non la personne cessionnaire principale.

```
EXISTS:A:$$OBJCODE=TASK
EXISTS:A:assignmentsUsersMM:ID=$$USER.ID
EXISTS:A:assignmentsUsersMM:ID_Mod=in
EXISTS:A:projectID=FIELD:ID
```


Cette méthode utilise le problème (optask) comme objet de liaison, en comparant également l’ID de projet trouvé au niveau du problème (optask) et en le faisant correspondre au champ d’ID au niveau du projet. Cette opération vérifie ensuite si l’un de ces problèmes (optasks) comporte une date d’entrée dans la période spécifiée. Dans ce cas, elle renvoie tous les projets qui n’ont pas eu de problème (optask) enregistré au cours des 30 derniers jours, en raison de l’instruction NOTEXISTS.

```
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:$$OBJCODE=OPTASK
EXISTS:A:entryDate=$$TODAY
EXISTS:A:entryDate_Mod=between
EXISTS:A:entryDate_Range=$$TODAY-30d
EXISTS:A:projectID=FIELD:ID
```

### Rapport de modèle avec instruction EXISTS

Ce filtre affiche tous les modèles qui n’ont pas été utilisés pour créer un projet ou qui n’ont pas été associés à un projet au cours de l’année écoulée. Une mise en garde s’impose : pour savoir si un modèle a été utilisé ou non en tant que pièce jointe, cela dépend de l’existence de tâches dans ce modèle.

```
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:$$OBJCODE=TASK
EXISTS:A:entryDate=$$TODAY-1y
EXISTS:A:entryDate_Mod=gte
EXISTS:A:templateTask:templateID=FIELD:ID
EXISTS:B:$$EXISTSMOD=NOTEXISTS
EXISTS:B:$$OBJCODE=PROJ
EXISTS:B:entryDate=$$TODAY-1y
EXISTS:B:entryDate_Mod=gte
EXISTS:B:templateID=FIELD:ID
```

### Rapport de tâche avec instruction EXISTS

Cette méthode utilise le tableau des utilisateurs et utilisatrices comme objet de liaison, en établissant une connexion entre l’ID de tâche des affectations et l’ID des tâches. Cette opération vérifie ensuite la collection d’ID des équipes auprès des ID d’équipe de l’utilisateur ou de l’utilisatrice, renvoyant la tâche si l’une des personnes cessionnaires fait partie de la même équipe que la personne qui consulte.

```
EXISTS:1:$$OBJCODE=USER
EXISTS:1:teams:ID=$$USER.teamIDs
EXISTS:1:userAssignments:taskID=FIELD:ID
```

### Rapport sur les utilisateurs et utilisatrices avec instruction EXISTS

Cette action renvoie toutes les personnes qui n’ont pas publié de mise à jour au cours des 3 dernières semaines. Cette méthode utilise l’objet note pour faire le lien et compare l’ID de personne propriétaire à un ID d’utilisateur ou d’utilisatrice. Elle renvoie ensuite cette personne si aucune note lui appartenant n’a de date d’entrée antérieure à 3 semaines plus tôt.

```
EXISTS:A:$$OBJCODE=NOTE
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:ownerID=FIELD:ID
EXISTS:A:entryDate=$$TODAY-3w
EXISTS:A:entryDate_Mod=gt
```

Cela renvoie toutes les personnes qui n’ont pas consigné d’heures au cours de la dernière semaine. Cette méthode est extrêmement similaire à l’exemple ci-dessus, mais elle utilise à la place les informations sur la personne propriétaire des heures et la date de saisie des heures pour déterminer les utilisateurs et utilisatrices qu’elle renvoie.

```
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:$$OBJCODE=HOUR
EXISTS:A:entryDate=$$TODAY-1w
EXISTS:A:entryDate_Mod=gte
EXISTS:A:ownerID=FIELD:ID
```

Dans un rapport sur les utilisateurs et utilisatrices, affichez une liste d’utilisateurs et d’utilisatrices correspondant à l’onglet Personnes d’un projet.

```
EXISTS:1:$$OBJCODE=PRTU
EXISTS:1:projectID=<projectID>
EXISTS:1:userID=FIELD:ID
```

### Rapport de catégorie (formulaire personnalisé) avec instruction EXISTS

Ce texte vous donne une liste de tous les formulaires de projet qui n’ont jamais été utilisés sur un projet. Il doit être utilisé conjointement avec la spécification du type d’objet du formulaire sur lequel nous nous concentrons. Dans ce cas, l’accent est mis sur PROJ. Nous devons donc inclure les annotations dans les lignes objTypes. Cela pourrait être utilisé pour d’autres types d’objet en modifiant les parties liées au code de l’objet. Cela vérifie l’ensemble des formulaires joints aux projets par rapport aux formulaires répertoriés et renvoie un résultat s’il n’existe aucune correspondance.

```
EXISTS:A:$$OBJCODE=PROJ
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:objectCategories:categoryID=FIELD:ID
objTypes=PROJ
objTypes_Mod=in
```

### Rapport de paramètre (champ personnalisé) avec instruction EXISTS

Cette opération renvoie tout champ personnalisé qui n’est actuellement pas joint à un formulaire personnalisé dans le système.

```
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:$$OBJCODE=CTGYPA
EXISTS:A:parameterID=FIELD:ID
```

### Rapport sur les rapports avec instruction EXISTS

Cela renvoie tous les rapports utilisant une valeur spécifique dans ses filtres.

```
EXISTS:1:$$OBJCODE=UIFT
EXISTS:1:ID=FIELD:filterID
EXISTS:1:preference:value=<value here>
EXISTS:1:preference:value_Mod=cicontains
```

Cela renvoie tous les rapports joints à un tableau de bord.

```
EXISTS:A:$$OBJCODE=PRTBSC
EXISTS:A:internalSectionID=FIELD:ID
EXISTS:A:portalTab:ID_Mod=notblank
```

### Rapport d’approbation d’épreuve avec instruction EXISTS

Cela ne renvoie les approbations d’épreuves que pour les projets dont le statut est En cours. Cette méthode utilise l’objet Document pour faire le lien entre l’approbation de l’épreuve et le projet en vérifiant la valeur currentVersionID par rapport à la valeur documentVersionID. À partir de là, nous accédons au statut du projet.

```
EXISTS:1:$$OBJCODE=DOCU
EXISTS:1:currentVersionID=FIELD:documentVersionID
EXISTS:1:project:status=CUR
EXISTS:1:project:status_Mod=in
```
