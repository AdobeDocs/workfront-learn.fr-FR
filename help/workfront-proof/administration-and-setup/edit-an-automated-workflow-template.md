---
title: Modifier un modèle de workflow automatisé
description: Découvrez comment apporter des modifications à un modèle de workflow de vérification automatisé existant dans  [!DNL  Workfront].
activity: use
feature: Workfront Proof
type: Tutorial
role: User, Admin
level: Intermediate
team: Technical Marketing
thumbnail: 335131.png
last-substantial-update: 2024-08-08T00:00:00Z
jira: KT-8831
exl-id: 03841b1f-741d-4427-ae84-ddb9f890fc95
doc-type: video
source-git-commit: d17df7162ccaab6b62db34209f50131927c0a532
workflow-type: tm+mt
source-wordcount: '572'
ht-degree: 100%

---

# Modifier un modèle de workflow automatisé

Au fur et à mesure que les processus de révision et d&#39;approbation de BAT sont affinés ou que des changements organisationnels sont apportés, les modèles de workflow automatisés doivent être mis à jour pour refléter les opérations actuelles de vos équipes utilisant Workfront.

La mise à jour des modèles permet de garantir la cohérence de vos processus de révision et d’approbation et permet aux personnes qui importent les épreuves de gagner du temps, car elles n’ont pas à ajuster constamment leur workflow.

1. Sélectionnez **[!UICONTROL Vérification]** dans le **[!UICONTROL Menu principal]** dans [!DNL Workfront].
1. À partir de là, sélectionnez **[!UICONTROL Workflows]** dans le menu du panneau de gauche.
1. Cliquez sur le menu à 3 points situé à droite du nom du modèle et sélectionnez **[!UICONTROL Afficher les détails du modèle]**.

Les options de partage, de copie et de suppression du modèle se trouvent en haut de la fenêtre des détails du modèle pour chaque modèle. La suppression d’un modèle n’affecte pas les épreuves en cours sur lesquels ce modèle est appliqué, mais le modèle ne pourra plus être utilisé.

![Fenêtre des détails du modèle](assets/proof-system-setup-edit-templates-details-area.png)


Cliquez sur la flèche située à gauche du mot « [!UICONTROL Détails] » pour développer ou réduire la section.

## Modifier les étapes et les destinataires

Des modifications peuvent être nécessaires dans la zone [!UICONTROL Workflow] lorsqu’un processus simplifié signifie une date d’échéance plus courte ou lorsqu’une personne rejoint l’équipe et révise les BAT.

Chaque étape d’un workflow automatisé comporte sa propre section, qui permet de modifier indépendamment les échéances, la confidentialité, les personnes destinataires du BAT et d’autres informations.

Cette vidéo présente brièvement certaines des modifications que vous pouvez apporter dans la zone [!UICONTROL Workflow]. Reportez-vous à la liste à puces figurant sous cette vidéo, qui passe en revue ces paramètres.

>[!VIDEO](https://video.tv.adobe.com/v/335131/?quality=12&learn=on&enablevpops)

Pour rappel, voici les modifications que vous pouvez apporter au modèle de BAT dans la section [!UICONTROL Workflow] :

* Cliquez sur le champ Nom de l’étape ou Date d’échéance pour mettre à jour ces informations.
* Cliquez sur la flèche à gauche de la date d’échéance pour verrouiller l’étape, déterminer le moment où l’étape sera activée, ou exiger qu’elle ne nécessite qu’une seule décision.
* Dans la liste des destinataires, cliquez sur les champs [!UICONTROL Rôle] ou [!UICONTROL Alertes e-mail] pour sélectionner une autre option.
* Le menu à trois points situé complètement à droite du nom des destinataires permet de les supprimer de la liste, d’en faire les principaux responsables de la prise de décision pour cette étape du workflow, ou de modifier le rôle de l’épreuve et les informations relatives à l’alerte par e-mail.
* Vous avez deux possibilités pour ajouter des destinataires à la liste.
   1. Dans le coin supérieur droit de chaque section d’étape, accédez au menu [!UICONTROL Plus] et sélectionnez [!UICONTROL Ajouter des personnes à l’étape]. Une fois que vous avez ouvert la fenêtre [!UICONTROL Ajouter des personnes à l’étape], cliquez sur l’étape à laquelle vous souhaitez les ajouter. Saisissez ensuite leur nom ou leur adresse e-mail dans la liste des destinataires et attribuez un rôle de BAT et une alerte par e-mail. Cliquez sur le bouton [!UICONTROL Ajouter des personnes] lorsque vous avez terminé.
   1. En haut de la zone [!UICONTROL Workflow], sélectionnez [!UICONTROL Ajouter des personnes à l’étape].

## Partage de modèles

La zone [!UICONTROL Partagé avec] affiche les utilisateurs et utilisatrices de BAT qui peuvent utiliser le modèle. Supprimez les personnes qui n’ont plus besoin d’utiliser le modèle en cliquant sur le menu à 3 points complètement à droite de leur nom et en sélectionnant [!UICONTROL Supprimer].

Liste ![[!UICONTROL Partagé avec]](assets/proof-system-setups-edit-template-shared-with.png)

Cependant, vous ne pouvez pas ajouter de personnes à la liste de partage à partir de cette section. Pour ce faire, revenez en haut de la fenêtre des détails du modèle et cliquez sur le bouton [!UICONTROL Partager le modèle].

## Informations supplémentaires

[!DNL Workfront] conserve un historique d’audit du moment où des modifications ont été apportées au modèle. Vous pouvez voir la date, la personne qui a effectué la modification et quelques informations brèves sur les modifications apportées.

Cette section n’enregistre pas d’informations sur le moment où le modèle a été utilisé pour des BAT.

![Liste des activités de BAT](assets/proof-system-setups-edit-template-activity.png)
