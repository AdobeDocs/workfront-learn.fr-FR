---
title: Comprendre les processus d’approbation propres à chaque groupe
description: Découvrez comment les administrateurs et administratrices de groupes peuvent créer ou modifier les processus d’approbation pour les groupes qu’ils ou elles gèrent.
feature: Approvals
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Intermediate
jira: KT-10017
hide: true
exl-id: 9986469c-b02f-48ac-b71e-055473a2855b
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
autotag-review: '2026-05-05T19:17:51.764Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 214
ht-degree: 100%

---

# Comprendre les processus d’approbation propres à chaque groupe

Les administrateurs et administratrices système et de groupes peuvent créer des processus d’approbation dans [!DNL Workfront]. Les administrateurs et administratrices système peuvent créer des processus destinés à l’ensemble du système [!DNL Workfront] ou des processus réservés à un groupe spécifique. Les administrateurs et administratrices de groupes peuvent uniquement créer ou modifier des processus pour le groupe qu’ils ou elles gèrent.

Pour un processus d’approbation destiné à être utilisé par tout le monde dans [!DNL Workfront], assurez-vous que le champ [!UICONTROL « Ce processus d’approbation peut être utilisé par »] est défini sur [!UICONTROL Tous les groupes].

Fenêtre ![[!UICONTROL Modifier un processus d’approbation] avec le champ du groupe en surbrillance](assets/admin-fund-approval-processes-1.png)

Les statuts disponibles dans le menu [!UICONTROL « Démarrer le processus d’approbation lorsque le statut est défini sur »] dépendent de la sélection dans le champ « utilisé par ». Si l’option [!UICONTROL Tous les groupes] est sélectionnée, seuls les statuts verrouillés à l’échelle du système sont disponibles.

Pour limiter un processus d’approbation à un groupe spécifique, sélectionnez le nom de ce groupe dans la liste du champ [!UICONTROL « Ce processus d’approbation peut être utilisé par »].

Fenêtre ![[!UICONTROL Modifier un processus d’approbation] avec le champ du groupe étendu](assets/admin-fund-approval-processes-2.png)

L’option [!UICONTROL Tous les groupes] n’est pas disponible pour les administrateurs ett administratrices de groupes.

Lorsqu’un groupe spécifique est sélectionné, seuls les statuts disponibles pour ce groupe apparaissent dans le menu [!UICONTROL « Démarrer le processus d’approbation lorsque le statut est défini sur »].

Fenêtre ![[!UICONTROL Modifier un processus d’approbation] avec le champ de statut en surbrillance](assets/admin-fund-approval-processes-3.png)
