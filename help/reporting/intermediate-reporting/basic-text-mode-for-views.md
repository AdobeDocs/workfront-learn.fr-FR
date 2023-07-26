---
title: Présentation du mode Texte de base pour les vues
description: Découvrez le mode texte, la casse des chameaux et un mode de texte "plug and play" de base que vous pouvez utiliser dans vos vues dans Workfront.
activity: use
feature: Text Mode Reporting
thumbnail: 336820.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
jira: KT-11367
exl-id: 156e5510-4a51-449f-9c8c-e16fdd8ea23d
doc-type: video
source-git-commit: 078fa7b82919ada1dcf35791b43f996b875cbf8f
workflow-type: tm+mt
source-wordcount: '685'
ht-degree: 0%

---

# Présentation du mode Texte de base pour les vues


>[!IMPORTANT]
>
>Conditions préalables :
>
>* [Présentation des éléments de reporting](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/reporting-elements.html?lang=en)
>* [Présentation des composants de création de rapports](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/reporting-components.html?lang=en)
>* [Créer une vue de base](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-a-basic-view.html?lang=en)

>[!TIP]
>
>* Pour mieux comprendre le mode texte, nous vous recommandons de regarder l’événement webinaire enregistré. [Demander à l’expert - Présentation du reporting en mode texte](https://experienceleague.adobe.com/docs/workfront-events/events/reporting-and-dashboards/introduction-to-text-mode-reporting.html?lang=en), qui dure une heure.
>* Pour en savoir plus sur le mode texte, nous vous recommandons de regarder la [Création de rapports avancés](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/advanced-reporting/welcome-to-advanced-reporting.html?lang=en) les tutoriels qui, ensemble, durent cinq heures et demie.

Dans cette vidéo, vous apprendrez :

* Quel mode de texte ?
* Quelle casse de chameau ?
* Un mode de texte simple &quot;Plug and play&quot; que vous pouvez utiliser dans vos vues

>[!VIDEO](https://video.tv.adobe.com/v/3410571/?quality=12&learn=on)

## Tâche - Vue 4 parents

Créez d’abord une colonne pour le Nom de la tâche et le Nom du parent, puis utilisez le mode texte suivant pour créer les trois autres colonnes.

### Tâche - Parent du nom parent

```
displayname=Parent of Parent Name
linkedname=parent
namekey=view.relatedcolumn
namekeyargkey.0=parent
namekeyargkey.1=name
querysort=parent:parent:name
textmode=true
valuefield=parent:parent:name
valueformat=HTML
```

### Tâche - Parent du nom parent

```
displayname=Parent of Parent of Parent Name
linkedname=parent
namekey=view.relatedcolumn
namekeyargkey.0=parent
namekeyargkey.1=name
querysort=parent:parent:parent:name
textmode=true
valuefield=parent:parent:parent:name
valueformat=HTML
```

### Tâche - Parent du parent du nom parent

```
displayname=Parent of Parent of Parent of Parent Name
linkedname=parent
namekey=view.relatedcolumn
namekeyargkey.0=parent
namekeyargkey.1=name
querysort=parent:parent:parent:parent:name
textmode=true
valuefield=parent:parent:parent:parent:name
valueformat=HTML
```

![Une image d&#39;écran montrant la vue 4 parents](assets/4-parents-view.png)

## Utilisateur : itérations affichant des listes dans les vues utilisateur

### Utilisateur - Tous les rôles de tâche

```
displayname=All job roles
listdelimiter=<p>
listmethod=nested(userRoles).lists
textmode=true
type=iterate
valuefield=role:name
valueformat=HTML
```

### Utilisateur : tous les rôles de tâche affichant la Principale

```
displayname=All Job Roles showing primary
listdelimiter=<p> 
listmethod=nested(userRoles).lists 
textmode=true
type=iterate 
valueexpression=IF({user}.{roleID}={role}.{ID},CONCAT("** ",{role}.{name}," **"),{role}.{name})
valueformat=HTML
```

### Utilisateur - Toutes les équipes

```
displayname=All teams
listdelimiter=<p>
listmethod=nested(teams).lists
textmode=true
type=iterate
valueexpression={name}
valueformat=HTML
```

>[!NOTE]
>
>Un champ Équipe est accessible par le biais de l’interface utilisateur. Il affiche toutes les équipes, séparées par des virgules, mais l’utilisation du mode de texte ci-dessus affiche chaque équipe sur une ligne distincte.


### Utilisateur - Tous les groupes

```
displayname=All groups
listdelimiter=<p>
listmethod=nested(userGroups).lists
textmode=true
type=iterate
valuefield=group:name
valueformat=HTML
```

### Utilisateur : tous les groupes affichant le groupe d’accueil

```
displayname=All groups showing home group
listdelimiter=<p>
listmethod=nested(userGroups).lists
textmode=true
type=iterate
valueexpression=IF({user}.{homeGroupID}={group}.{ID},CONCAT("** ",{group}.{name}," **"),{group}.{name})
valueformat=HTML
```


### Utilisateur - Rapports directs

```
displayname=Direct reports
listdelimiter=<p>
listmethod=nested(directReports).lists
textmode=true
type=iterate
valueexpression={name}
valueformat=HTML
```

### Utilisateur - Future PTO

```
displayname=Future PTO
listdelimiter=<br>
listmethod=nested(reservedTimes).lists
namekey=group.plural
textmode=true
type=iterate
valueexpression=IF({startDate}>$$TODAY,CONCAT({startDate}," - ",{endDate}),"")
valueformat=HTML
width=150
```

![Image d’écran affichant la vue Listes d’utilisateurs](assets/user-lists-view-large.png)

## Tâche - Comment afficher les affectations de tâche et travailler sur l’état

```
displayname=Assignments and Status
listdelimiter=<br>
listmethod=nested(assignments).lists
namekey=group.plural
textmode=true
type=iterate
valueexpression=CONCAT({assignedTo}.{name},IF(ISBLANK({assignedTo}.{name}),"",IF({status}="AA"," - Requested",IF({status}="AD"," - Working"," - Done"))))
valueformat=HTML
width=150
```

![Image d’écran affichant la vue Affectations et État](assets/assignments-and-status-view.png)


## Tâche - Comment afficher le rôle et l’attribution sur plusieurs affectations de tâche

### Tâche - Rôle + heures

```
displayname=Role+hours
listdelimiter=<li>
listmethod=nested(assignments).lists
textmode=true
type=iterate
valueexpression=CONCAT({role}.{name}," (",round({workRequired}/60,2),")")
valueformat=HTML
```

### Tâche - Attribution + affectation de pourcentage

```
displayname=Assignment+percent
valueexpression=CONCAT({assignedTo}.{name}," (",{assignmentPercent},")")
listdelimiter=<li>
listmethod=nested(assignments).lists
valueformat=HTML
textmode=true
type=iterate
```

![Image d’écran affichant la vue Affectations et Rôles](assets/assignments-roles-and-percent-view.png)

## Tâche : prédécesseurs et successeurs sur plusieurs projets

### Filtre de tâche (facultatif)

**Me montrer toutes les tâches ayant au moins un prédécesseur multi-projets ou au moins un successeur multi-projets sur les projets en cours**

```
predecessorsMM:ID_Mod=notblank
predecessorsMM:projectID=FIELD:projectID
predecessorsMM:projectID_Mod=ne
project:statusEquatesWith=CUR
project:statusEquatesWith_Mod=in
OR:1:project:statusEquatesWith=CUR
OR:1:project:statusEquatesWith_Mod=in
OR:1:successorsMM:ID_Mod=notblank
OR:1:successorsMM:projectID=FIELD:projectID
OR:1:successorsMM:projectID_Mod=ne
```

### Tâche : affichez les noms des prédécesseurs et le prédécesseur de projet est dans

```
displayname=Predecessor names
listdelimiter=<br>
listmethod=nested(predecessors).lists
namekey=group.plural
textmode=true
type=iterate
valueexpression=CONCAT("TASK = ",{predecessor}.{name}," >> PROJECT = ",{predecessor}.{project}.{name})
valueformat=HTML
width=150
```

### Tâche : affichez les noms des successeurs et le successeur du projet se trouve dans

```
displayname=Successor names
listdelimiter=<br>
listmethod=nested(successors).lists
namekey=group.plural
textmode=true
type=iterate
valueexpression=CONCAT("TASK = ",{successor}.{name}," >> PROJECT = ",{successor}.{project}.{name})
valueformat=HTML
width=150
```

### Tâche - Afficher la date d’achèvement prévue des prédécesseurs

```
displayname=Predecessor projected completion dates
valueformat=atDate
listdelimiter=
textmode=true
width=90
stretch=0
valuefield=predecessor:projectedCompletionDate
type=iterate
listmethod=nested(predecessors).lists
shortview=false
```

### Tâche - Afficher l’état de progression des prédécesseurs

```
displayname=Predecessor progress status
listdelimiter=<br>
listmethod=nested(predecessors).lists
shortview=false
stretch=0
textmode=true
type=iterate
valueexpression=IF({predecessor}.{progressStatus}="OT","On Time",IF({predecessor}.{progressStatus}="LT","Late",IF({predecessor}.{progressStatus}="BH","Behind","At Risk")))
valueformat=HTML
width=90
```

### Tâche : affichez le pourcentage d’achèvement du projet interprojet du prédécesseur

```
displayname=Predecessor project percent complete
listdelimiter=<br>
listmethod=nested(predecessors).lists
namekey=group.plural
textmode=true
type=iterate
valueexpression=IF({isCP}=true,CONCAT({predecessor}.{project}.{percentComplete},"%"),"")
valueformat=HTML
width=150
```

![Image d’écran montrant la vue des prédécesseurs et successeurs sur plusieurs projets](assets/cross-project-predecessors-and-successors.png)


## Tâche : itération indiquant toutes les personnes affectées et chacune d’elles affectée

```
displayname=All assignees and requesters
listdelimiter=<p>
listmethod=nested(assignments).lists
textmode=true
type=iterate
valueexpression=CONCAT("Assigned To: ",{assignedTo}.{name},"; Requested By: ",{assignedBy}.{name})
valueformat=HTML
```

![Une image d’écran montrant toutes les personnes affectées et qui ont chacune été affectées](assets/all-assignees-and-requesters.png)

## Tâche/projet : itération affichant tous les formulaires personnalisés sur un projet ou une tâche

```
displayname=All Forms Assigned
listdelimiter=<p>
listmethod=nested(objectCategories).lists
textmode=true
type=iterate
valuefield=category:name
valueformat=HTML
```

![Image d’écran affichant tous les formulaires personnalisés d’un projet](assets/all-custom-forms-on-a-project.png)


## Projet : itération affichant tous les contacts Principaux pour les éléments à résoudre en mode projet.

```
displayname=Requestor
listdelimiter=<br>
listmethod=nested(resolvables).lists
namekey=group.plural
textmode=true
type=iterate
valuefield=owner:name
valueformat=HTML
width=150
```

![Une image d’écran montrant les Principaux contacts pour les éléments à résoudre](assets/primary-contacts-for-resolvables.png)

## Projet : itération présentant tous les membres de l’équipe de projet

```
displayname=Project Team Members
listdelimiter=<br>
listmethod=nested(projectUsers).lists
namekey=group.plural
textmode=true
type=iterate
valuefield=user:name
valueformat=HTML
```

![Image d’écran montrant tous les membres de l’équipe de projet](assets/all-project-team-members.png)

## Projet : itération indiquant entryDate de tous les problèmes résolvables d’un projet.

```
displayname=Resolvables entry date
linkedname=direct
listdelimiter=<br>
listmethod=nested(project.resolvables).lists
listsort=string(description)
querysort=description
section=0
textmode=true
type=iterate
valuefield=entryDate
valueformat=HTML
```

![Image d’écran affichant entryDate de tous les problèmes résolvables d’un projet.](assets/resolvables-entry-date.png)

## Projet : affiche le groupe d’accueil du demandeur de projet d’origine.

```
displayname=Requestor home group
linkedname=direct
namekey=name
querysort=convertedOpTaskOriginator:homeGroup:name
textmode=true
valuefield=convertedOpTaskOriginator:homeGroup:name
valueformat=HTML
```

![Image d’écran montrant le groupe d’accueil du demandeur du projet](assets/requestor-home-group.png)

## Projet : indique si le projet est une file d’attente de demandes.

```
querysort=queueDef:isPublic
valueformat=val
description=0 (None), 1 (Public), 2 (Private), 3 (Company), 4 (Group)
linkedname=direct
textmode=true
enumtype=PROJ
valuefield=queueDef:isPublic
namekey=status
type=enum
enumclass=com.attask.common.constants.ProjectStatusEnum
displayname=Public Selection
```

![Image d’écran indiquant si le projet est une file d’attente de demandes](assets/project-is-a-request-queue.png)

## Problème : itération indiquant tous les membres de l’équipe de projet résolus

```
displayname=Resolve Project: Team Members
listdelimiter=<br>
listmethod=nested(resolveProject.projectUsers).lists
namekey=group.plural
textmode=true
type=iterate
valuefield=user:name
valueformat=HTML
width=150
```

![Image d’écran montrant tous les membres de l’équipe de projet de résolution](assets/all-resolve-project-team-members.png)

## Problème : itération montrant toutes les équipes du contact Principal du problème.

```
displayname=Requestor Teams
listdelimiter=<br>
listmethod=nested(owner.teams).lists
namekey=group.plural
textmode=true
type=iterate
valuefield=name
valueformat=HTML
width=150
```

![Image d’écran montrant toutes les équipes de contact Principales](assets/all-primary-contact-teams.png)

## Document : itération affichant le dossier dans un rapport de document

```
displayname=Folder
listdelimiter=<br><br>
listmethod=nested(folders).lists
textmode=true
type=iterate
valuefield=name
valueformat=HTML
```

![Image d’écran affichant un dossier dans un rapport de document](assets/folder-in-a-document-report.png)

## Document : itération affichant le dossier parent dans un rapport de document.

```
displayname=Parent Folder
listdelimiter=<br><br>
listmethod=nested(folders).lists
textmode=true
type=iterate
valuefield=parent:name
valueformat=HTML
```

![Image d’écran affichant le dossier parent dans un rapport de document](assets/parent-folder-in-a-document-report.png)

## Document - Dates de validation du document

```
displayname=Document approval dates
valueformat=HTML
listdelimiter=<br>
linkedname=direct
textmode=true
listsort=string(description)
valuefield=approvalDate
type=iterate
listmethod=nested(approvals).lists
shortview=false
section=0
```

![Image d’écran affichant la vue des dates d’approbation du document](assets/document-approval-dates.png)

## Approbations d&#39;épreuve

### Approbation du BAT - Afficher le nom du projet

```
displayname=Project Name
textmode=true 
valuefield=documentVersion:document:project:name 
valueformat=HTML
```

### Approbation du BAT - Afficher le nom de la tâche

```
displayname=Task Name
textmode=true 
valuefield=documentVersion:document:task:name 
valueformat=HTML
```

![Image d’écran montrant le projet et la tâche d’une validation de BAT](assets/proof-approval-project-and-task.png)
