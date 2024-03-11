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
last-substantial-update: 2024-01-24T00:00:00Z
exl-id: 77dfb9f1-3242-47ca-a0ce-203b535af156
source-git-commit: 30748311c14fb8aa6b10c03a74e83f46bdb5dfbf
workflow-type: ht
source-wordcount: '359'
ht-degree: 100%

---

# Définir des rôles de BAT par défaut



Le premier paramètre par défaut à définir est un rôle d’épreuve par défaut qui sera affecté lorsque de nouveaux utilisateurs ou de nouvelles utilisatrices seront créés ou que des personnes ouvriront une épreuve.

Les rôles d’épreuve déterminent ce que peut faire un utilisateur ou une utilisatrice avec une épreuve : la consulter, faire des commentaires, l’approuver, etc. [!DNL Workfront] recommande de définir les rôles d’épreuve par défaut pour toutes les personnes, afin de faciliter et d’accélérer l’ajout de destinataires aux épreuves et la configuration des workflows.

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
