---
title: Création d’invites personnalisées
description: Découvrez ce qu’est une invite personnalisée, comment créer une invite personnalisée à l’aide du mode texte et quelques exemples que vous pouvez utiliser dans les rapports dans Workfront.
activity: use
feature: Reports and Dashboards
thumbnail: 336822.png
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
kt: 9087
exl-id: 1bb0832e-e888-4154-b78d-24c6d69f629f
source-git-commit: 252ba3ba44f22519a35899fcda9c6bca597a6c2c
workflow-type: tm+mt
source-wordcount: '194'
ht-degree: 2%

---

# Création d’invites personnalisées

Dans cette vidéo, vous apprendrez :

* Présentation d’une invite personnalisée
* Création d’une invite personnalisée en mode texte
* Exemples que vous pouvez utiliser dans vos rapports

>[!VIDEO](https://video.tv.adobe.com/v/336822/?quality=12)

## Activité : Création d’invites personnalisées

1. Créez une invite personnalisée qui affiche les états de projet suivants dans le menu déroulant de l’invite :
   * Planification
   * Actuel
   * Terminé
   * Immobilisé
1. Modifiez l’invite pour afficher les projets en cours qui doivent être exécutés ce mois-ci.

## Réponses

1. Les invites personnalisées doivent ressembler à ceci et présenter le mode de texte suivant :

   ![Image de l’écran pour créer un nouveau filtre en mode texte](assets/cp-01.png)

   Une fois que vous avez enregistré l’invite personnalisée, le menu déroulant de l’invite doit se présenter comme suit :

1. Le mode texte de votre invite personnalisée doit se présenter comme suit :

![Image de l’écran pour créer un nouveau filtre en mode texte](assets/cp-02.png)

```
   status=CUR&plannedCompletionDate=$$TODAYbm&plannedCompletionDate_Mod=between&plannedCompletionDate_Range=$$TODAYem 
```

Le libellé de la liste déroulante des principales invites doit être mis à jour pour refléter le changement du code comme ceci :

![Image de l’écran pour créer un nouveau filtre en mode texte](assets/cp-02a.png)
