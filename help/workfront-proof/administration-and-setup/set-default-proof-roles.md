---
title: Définir des rôles de BAT par défaut
description: Découvrez comment définir le rôle d’épreuve par défaut affecté lors de la création de nouveaux utilisateurs ou de nouvelles utilisatrices ou lorsque des personnes ouvrent une épreuve.
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User, Admin
level: Intermediate
thumbnail: set-default-proof-roles.png
jira: KT-10235
last-substantial-update: '2024-01-24T00:00:00.000Z'
exl-id: 77dfb9f1-3242-47ca-a0ce-203b535af156
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
autotag-review: '2026-05-05T20:03:40.797Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 362
ht-degree: 87%

---

# Définir des rôles de BAT par défaut



Le premier paramètre par défaut à définir est un rôle d’épreuve par défaut qui sera affecté lorsque de nouveaux utilisateurs ou de nouvelles utilisatrices seront créés ou que des personnes ouvriront une épreuve.

Les rôles de BAT déterminent ce qu’un utilisateur peut faire avec une épreuve (la regarder, la commenter, l’approuver, etc.). [!DNL Workfront] recommande de définir les valeurs par défaut du rôle de BAT pour tous les utilisateurs, afin d’ajouter plus rapidement et plus facilement des destinataires aux BAT et de configurer des workflows.

![Les rôles d’épreuve peuvent être sélectionnés lors du chargement d’une épreuve.](assets/proof-system-setups-proof-role-example.png)

Cependant, ce rôle d’épreuve par défaut peut être modifié au fur et à mesure du chargement des épreuves, ce qui permet à chacun de remplir le rôle requis dans le processus de révision et d’approbation.


## Définir des rôles de BAT par défaut

1. Sélectionnez **Configuration** dans le [!UICONTROL menu principal].
1. Sélectionnez **Révision et approbation** dans le menu de gauche.
1. Cliquez sur le bouton en regard du rôle de BAT par défaut souhaité pour les nouveaux utilisateurs et utilisatrices et pour les utilisateurs et utilisatrices invités de [!DNL Workfront] pour les personnes « destinataires désignées » : toute personne ajoutée au workflow de BAT, soit manuellement, soit via un modèle de workflow.
1. Cliquez sur le bouton en regard du rôle de BAT par défaut souhaité pour les nouveaux utilisateurs et utilisatrices et pour les utilisateurs et utilisatrices invités de [!DNL Workfront] pour les personnes « non destinataires ». Il s’agit généralement d’utilisateurs et d’utilisatrices de [!DNL Workfront] qui ont accès à un BAT, mais qui ne font pas partie des personnes affectées au workflow.
1. Enregistrez les modifications.

![Paramètres de révision et d’approbation dans Workfront](assets/proof-system-setups-workfront-defaults.png)

Réfléchissez à ce que la plupart de vos utilisateurs, utilisatrices et personnes invitées devront faire lorsqu’ils seront ajoutés à un workflow de relecture. Il doit s’agir de vos paramètres par défaut.

## Bonnes pratiques

| Bonne pratique | Voici pourquoi |
|---|---|
| Utilisez uniquement les rôles Lecture seule ou Réviseur ou réviseuse pour le paramètre « Rôles pour les personnes non destinataires qui ouvrent un BAT de document » dans Workfront. | Les autres options de ce paramètre requièrent toutes un statut de décision du BAT, ce qui peut faire dérailler votre workflow de relecture. En règle générale, les personnes qui n’ont pas été ajoutées au workflow de BAT ont juste besoin de consulter le BAT ou de faire des commentaires, et non de l’approuver, de sorte que les options « Lecture seule » ou « Réviseur ou réviseuse » sont les mieux adaptées. <br> <br>Remarque : ce paramètre se trouve dans le menu principal de Workfront > Configuration > Révision et approbation. |
