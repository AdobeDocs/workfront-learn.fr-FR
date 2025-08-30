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
source-git-commit: 7be0b8cce9cba04927d6704d0009b482bbcf4b41
workflow-type: tm+mt
source-wordcount: '682'
ht-degree: 0%

---

# Comprendre les filtres EXISTS

Les filtres EXISTS sont des filtres de mode texte avancés, qui nous permettent de contourner la limitation de 2 sauts de tableau/champ dans un Report Builder standard. Ils peuvent également être utilisés pour identifier des objets du système qui ne sont pas associés à une condition de relation spécifique via NOTEXISTS.

Dans cette vidéo, vous apprendrez à créer un filtre EXISTS pour voir « Validations de BAT pour les projets actuels » dans un rapport Validations de BAT.

Pour une présentation plus détaillée du fonctionnement de EXISTS, reportez-vous à la documentation [Création de filtres de mode texte complexes à l’aide d’instructions EXISTS](https://experienceleague.adobe.com/fr/docs/workfront/using/reporting/reports/text-mode/create-complex-text-mode-filters-using-exists-statements).

>[!VIDEO](https://video.tv.adobe.com/v/3471205/?quality=12&learn=on&enablevpops&captions=fre_fr)

## EXEMPLES DE FILTRES EXISTANTS

### Le rapport de projet EXISTE

Cette méthode utilise la tâche comme objet de liaison, en comparant l’ID de projet trouvé au niveau de la tâche et en le faisant correspondre au champ ID au niveau du projet . Cela nous permet de comparer ensuite les utilisateurs de l’affectation sur la tâche à un caractère générique $$USER.ID. Cela renvoie uniquement les projets pour lesquels l’utilisateur afficheur est affecté à un
, qu’ils soient ou non la personne désignée principale.

```
EXISTS:A:$$OBJCODE=TASK
EXISTS:A:assignmentsUsersMM:ID=$$USER.ID
EXISTS:A:assignmentsUsersMM:ID_Mod=in
EXISTS:A:projectID=FIELD:ID
```


Cette méthode utilise l’événement (optask) comme objet de liaison, en comparant également l’ID de projet trouvé au niveau de l’événement (optask) et en le faisant correspondre au champ d’ID au niveau du projet. Cette opération vérifie ensuite si l’un de ces problèmes (optasks) comporte une date d’entrée dans la période spécifiée. Dans ce cas, il renvoie tous les projets qui ont
Un problème (optask) n’a pas été enregistré au cours des 30 derniers jours en raison de l’existence de NOTEXISTS.

```
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:$$OBJCODE=OPTASK
EXISTS:A:entryDate=$$TODAY
EXISTS:A:entryDate_Mod=between
EXISTS:A:entryDate_Range=$$TODAY-30d
EXISTS:A:projectID=FIELD:ID
```

### Modèle de rapport EXISTE

Ce filtre affiche tous les modèles qui n’ont pas été utilisés pour créer un projet ou qui ont été associés à un projet au cours de l’année écoulée. L’un des avertissements est que, pour déterminer si un modèle a été utilisé ou non en tant que pièce jointe, il dépend de l’existence de tâches dans ce modèle.

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

### Le rapport de tâche EXISTE

Cette méthode utilise la table des utilisateurs comme objet de liaison, en établissant une connexion entre les affectations taskID et les tâches ID. Cette opération vérifie ensuite la collection d’ID des équipes auprès des ID d’équipe de l’utilisateur, renvoyant la tâche si l’une des personnes désignées fait partie de la même équipe que l’utilisateur affichant la tâche.

```
EXISTS:1:$$OBJCODE=USER
EXISTS:1:teams:ID=$$USER.teamIDs
EXISTS:1:userAssignments:taskID=FIELD:ID
```

### Rapport utilisateur EXISTE

Cette action renvoie tous les utilisateurs qui n’ont pas publié de mise à jour au cours des 3 dernières semaines. Cette méthode utilise l’objet note pour combler l’écart et compare le ownerID à un ID d’utilisateur. Renvoie ensuite cet utilisateur si aucune note qui lui appartient n’a une date d’entrée supérieure à 3 semaines.

```
EXISTS:A:$$OBJCODE=NOTE
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:ownerID=FIELD:ID
EXISTS:A:entryDate=$$TODAY-3w
EXISTS:A:entryDate_Mod=gt
```

Tous les utilisateurs qui n’ont pas enregistré d’heures au cours de la dernière semaine seront rétablis. Cette méthode est extrêmement similaire à l’exemple ci-dessus, mais elle utilise à la place les informations sur le propriétaire des heures et la date de saisie des heures pour déterminer les utilisateurs et utilisatrices qu’elle renvoie.

```
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:$$OBJCODE=HOUR
EXISTS:A:entryDate=$$TODAY-1w
EXISTS:A:entryDate_Mod=gte
EXISTS:A:ownerID=FIELD:ID
```

Dans un rapport d’utilisateur, affichez une liste d’utilisateurs correspondant à l’onglet Personnes d’un projet.

```
EXISTS:1:$$OBJCODE=PRTU
EXISTS:1:projectID=<projectID>
EXISTS:1:userID=FIELD:ID
```

### Rapport de catégorie (formulaire personnalisé) EXISTE

Ce texte vous donne une liste de tous les formulaires de projet qui n&#39;ont jamais été utilisés sur un projet. Cette fonction doit être utilisée conjointement avec la spécification du type d’objet du formulaire sur lequel nous mettons l’accent. Dans ce cas, le focus est sur PROJ. Nous devons donc inclure les légendes dans les lignes objTypes. Ceci pourrait être utilisé
pour d&#39;autres types d&#39;objet en modifiant les articles liés au code objet. Cette action vérifie l’ensemble des projets joints aux formulaires répertoriés et renvoie s’il n’existe aucune correspondance.

```
EXISTS:A:$$OBJCODE=PROJ
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:objectCategories:categoryID=FIELD:ID
objTypes=PROJ
objTypes_Mod=in
```

### Rapport de paramètres (champ personnalisé) EXISTE

Cette opération renvoie tout champ personnalisé qui n’est actuellement pas joint à un formulaire personnalisé dans le système.

```
EXISTS:A:$$EXISTSMOD=NOTEXISTS
EXISTS:A:$$OBJCODE=CTGYPA
EXISTS:A:parameterID=FIELD:ID
```

### Rapport EXISTS

Cela renvoie tout rapport utilisant une valeur spécifique dans ses filtres.

```
EXISTS:1:$$OBJCODE=UIFT
EXISTS:1:ID=FIELD:filterID
EXISTS:1:preference:value=<value here>
EXISTS:1:preference:value_Mod=cicontains
```

Cette option renvoie tous les rapports joints à un tableau de bord.

```
EXISTS:A:$$OBJCODE=PRTBSC
EXISTS:A:internalSectionID=FIELD:ID
EXISTS:A:portalTab:ID_Mod=notblank
```

### Le rapport d&#39;approbation d&#39;épreuve EXISTE

Cette option ne renvoie les validations d&#39;épreuves que pour les projets dont le statut est En cours. Cette méthode utilise l’objet Document pour combler l’écart entre l’approbation de l’épreuve et le projet en vérifiant la valeur currentVersionID et documentVersionID, de là nous passons au statut du projet.

```
EXISTS:1:$$OBJCODE=DOCU
EXISTS:1:currentVersionID=FIELD:documentVersionID
EXISTS:1:project:status=CUR
EXISTS:1:project:status_Mod=in
```
