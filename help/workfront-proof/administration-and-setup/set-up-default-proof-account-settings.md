---
title: Configurer des paramètres par défaut du compte du BAT
description: Découvrez comment configurer les paramètres de compte par défaut qui s’appliquent globalement à tous les utilisateurs et toutes les utilisatrices de BAT et en charge de la relecture.
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User, Admin
level: Intermediate
thumbnail: set-up-proof-actual-default-settings.png
jira: KT-10236
last-substantial-update: '2024-01-24T00:00:00.000Z'
exl-id: 6eda8bcd-ab0f-4e02-9080-64b6051b327f
product_v2: id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2: id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
subfeature_v2: id: b18b693b-6d59-4359-95fd-a386b7a615fe
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
level_v2: id: b5a62a22-46f7-4f0d-b151-3fc640bef588
autotag-review: '2026-05-05T20:04:10.059Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 569
ht-degree: 95%

---

# Configurer des paramètres par défaut du compte du BAT

Établissez des paramètres de compte par défaut qui s’appliquent globalement à tous les BAT et utilisateurs et utilisatrices en charge de la relecture - pays, langue et fuseau horaire. Si vous disposez d’utilisateurs ou d’utilisatrices dans plusieurs fuseaux horaires ou pays, vous pouvez ajuster ces paramètres sur le profil de chaque personne, si nécessaire.

![Fenêtre des paramètres du compte pour la relecture](assets/proof-system-setups-default-account-settings.png)

1. Sélectionnez **[!UICONTROL Relecture]** dans le [!UICONTROL Menu principal] de [!DNL Workfront's].
1. Sélectionnez **[!UICONTROL Paramètres du compte]** dans la barre de navigation supérieure.
1. Sélectionnez l’onglet **[!UICONTROL Détails]**.
1. Accédez au champ [!UICONTROL Pays] et sélectionnez **[!UICONTROL Modifier]**. Choisissez par défaut le pays où se trouvent la majorité de vos utilisateurs et utilisatrices de relecture.
1. Sélectionnez **[!UICONTROL Enregistrer]** pour ce paramètre.
1. Accédez au champ [!UICONTROL Langue par défaut] et sélectionnez **[!UICONTROL Modifier]**. Choisissez comme paramètre par défaut la langue qu’utilisera la majorité de vos utilisateurs et utilisatrices en charge de la relecture.
1. Sélectionnez **[!UICONTROL Enregistrer]** pour ce paramètre.
1. Accédez au champ [!UICONTROL Fuseau horaire par défaut] et sélectionnez **[!UICONTROL Modifier]**. Choisissez comme paramètre par défaut le fuseau horaire dans lequel se trouve la majorité des utilisateurs et utilisatrices de votre système de relecture. Il s’agit du fuseau horaire reconnu par les workflows de BAT configurés manuellement. Il s’applique également aux modèles de workflows de BAT, mais chaque modèle peut avoir un fuseau horaire défini.
1. Sélectionnez **[!UICONTROL Enregistrer]** pour ce paramètre.

## Bonnes pratiques


| Bonne pratique | Voici pourquoi |
|---|---|
| Ajustez les paramètres back-end de l’épreuve pour que les utilisateurs et les utilisatrices voient les échéances au format 12 heures. | Sélectionnez l’option F j, Y, gi:a dans les paramètres de l’épreuve pour les utilisateurs qui souhaitent afficher les échéances/heures de l’épreuve au format AM/PM. Pour les régions qui utilisent le format 12 heures, cela permet de clarifier les échéances. <br> <br>Remarque : ce paramètre se trouve dans le menu principal de Workfront > Relecture > Paramètres du compte > Utilisateurs et utilisatrices > en modifiant le champ Format de date pour chaque utilisateur ou utilisatrice. |
| Fixez une date d’échéance par défaut pour la relecture dans les paramètres système. | Lorsqu’une date d’échéance pour la relecture est définie par défaut (date de chargement + x nombre de jours ouvrables), si la personne ayant créé le BAT oublie d’ajouter une échéance, Workfront applique automatiquement cette échéance à chaque BAT chargé. <br> <br>Remarque : ce paramètre se trouve dans le menu principal Workfront > Relecture > Paramètres du compte > Paramètres > Valeurs par défaut des BAT > champ Échéance (+ jours ouvrables). |
| Masquez l’option non pertinente de statut de décision de l’épreuve. | Cette option de décision est souvent source de confusion pour les personnes chargées de l’approbation, car les organisations ne définissent pas toujours quand l’option Non pertinent doit être utilisée. L’option Non pertinent indique généralement que l’épreuve n’est pas pertinente pour la personne destinataire de l’épreuve et qu’elle n’a pas besoin de prendre une décision d’approbation ou de rejet. En sélectionnant Non pertinent, le workflow de BAT peut continuer.<br> <br>L’option Non pertinent n’est pas nécessaire dans la plupart des workflows de BAT.<br> <br>Remarque : ce paramètre se trouve dans le menu principal de Workfront > Relecture > Paramètres du compte > Décisions. |
| Ne réorganisez pas les options de statut de décision de l’épreuve les paramètres de l’épreuve. | Chaque paramètre de statut de décision de l’épreuve contient une valeur/un poids spécifique qui, s’ils sont réorganisés, peuvent semer la confusion dans vos configurations d’épreuve. L’ordre de décision et la valeur/le poids sont utilisés comme déclencheurs d’activation de l’étape de BAT et dans les rapports.<br> <br>Remarque : ce paramètre se trouve dans le menu principal de Workfront > Relecture > Paramètres du compte > Décisions. |
| Définissez les valeurs par défaut des utilisateurs et des utilisatrices pour les rôles d’épreuve et les alertes par e-mail. | Ces paramètres sont automatiquement renseignés lors de l’affectation d’un workflow de BAT, ce qui accélère le processus et contribue à la cohérence des workflows de BAT.<br> <br>Remarque : les paramètres d’utilisation par défaut se trouvent dans le menu principal de Workfront, en choisissant Relecture > Paramètres du compte > Utilisateurs et utilisatrices, et en sélectionnant le profil pour lequel les paramètres par défaut doivent être définis. |
