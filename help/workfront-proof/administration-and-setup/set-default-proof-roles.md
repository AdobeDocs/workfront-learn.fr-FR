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
workflow-type: tm+mt
source-wordcount: '359'
ht-degree: 52%

---

# Définir des rôles de BAT par défaut



Le premier paramètre par défaut à définir est un rôle d’épreuve par défaut qui sera affecté lorsque de nouveaux utilisateurs ou de nouvelles utilisatrices seront créés ou que des personnes ouvriront une épreuve.

Les rôles d’épreuve déterminent ce que peut faire un utilisateur ou une utilisatrice avec une épreuve : la consulter, faire des commentaires, l’approuver, etc. [!DNL Workfront] recommande de définir les rôles d’épreuve par défaut pour toutes les personnes, afin de faciliter et d’accélérer l’ajout de destinataires aux épreuves et la configuration des workflows.

![Les rôles d’épreuve peuvent être sélectionnés lors du chargement d’une épreuve.](assets/proof-system-setups-proof-role-example.png)

Cependant, ce rôle d’épreuve par défaut peut être modifié au fur et à mesure du chargement des épreuves, ce qui permet à chacun de remplir le rôle requis dans le processus de révision et d’approbation.


## Définir des rôles de BAT par défaut

1. Sélectionnez **Configuration** dans le [!UICONTROL menu principal].
1. Sélectionnez **Révision et approbation** dans le menu de gauche.
1. Cliquez sur le bouton en regard du rôle de BAT par défaut souhaité pour les deux nouveaux [!DNL Workfront] utilisateurs et utilisateurs invités du BAT pour les &quot;destinataires désignés&quot; : toute personne ajoutée au workflow de BAT, soit manuellement, soit via un modèle de workflow.
1. Cliquez sur le bouton en regard du rôle de BAT par défaut souhaité pour les deux nouveaux [!DNL Workfront] utilisateurs et utilisateurs invités BAT pour les utilisateurs &quot;non-destinataires&quot;. Elles sont généralement [!DNL Workfront] les utilisateurs qui ont accès à un BAT, mais qui ne font pas partie des personnes affectées au workflow.
1. Enregistrez les modifications.

![Paramètres de révision et d’approbation dans Workfront](assets/proof-system-setups-workfront-defaults.png)

Réfléchissez à ce que la plupart de vos utilisateurs, utilisatrices et personnes invitées devront faire lorsqu’ils seront ajoutés à un workflow de relecture. Il doit s’agir de vos paramètres par défaut.

## Bonnes pratiques

| Bonne pratique | Voici pourquoi : |
|---|---|
| Utilisez uniquement Lecture seule ou Réviseur pour le paramètre &quot;Rôles pour les non-destinataires qui ouvrent un BAT de document&quot; dans Workfront. | Les autres options de ce paramètre nécessitent toutes une décision de BAT, ce qui peut faire dérailler votre workflow de vérification. En règle générale, les personnes qui ne sont pas ajoutées au workflow de BAT doivent simplement afficher le BAT ou faire des commentaires, ne pas approuver réellement le BAT. Par conséquent, les options Lecture seule ou Réviseur sont votre meilleur choix. <br> <br>Remarque : ce paramètre se trouve dans le menu principal de Workfront > Configuration > Révision et approbation. |
