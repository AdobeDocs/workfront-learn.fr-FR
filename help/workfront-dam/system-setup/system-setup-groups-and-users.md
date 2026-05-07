---
title: Configurer des groupes et des utilisateurs
description: Découvrez comment créer des dossiers, des groupes, des utilisateurs et des utilisatrices dans [!UICONTROL Workfront DAM]. Comprenez les types de fonctions et accordez des autorisations aux dossiers.
activity: use
feature: Digital Content and Documents
type: Tutorial
role: Admin
level: Intermediate
team: Technical Marketing
jira: KT-8967
exl-id: 4ebf675c-b72d-447e-b131-a89acb449e15
doc-type: video
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
autotag-review: '2026-05-05T20:28:55.491Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 416
ht-degree: 95%

---

# Configurer des groupes et des utilisateurs

Dans cette vidéo, vous apprendrez à :

* Comprendre comment les configurations de groupe affectent l’accès aux ressources
* Créer des dossiers, des groupes, des utilisateurs et des utilisatrices dans un ordre spécifique
* Comprendre les types de fonctions
* Octroyer des autorisations aux dossiers
* Créer et modifier des groupes
* Ajouter et modifier des utilisateurs et des utilisatrices

>[!VIDEO](https://video.tv.adobe.com/v/335230/?quality=12&learn=on&enablevpops=1)

## Réviser des groupes, des utilisateurs et des utilisatrices

Lorsque vous configurez votre système de [!UICONTROL gestion des ressources numériques Workfront], il est important de tenir compte des rôles que jouent les utilisateurs, les utilisatrices et les groupes dans l’ensemble.

Les groupes contrôlent l’accès aux dossiers de ressources dans [!UICONTROL Workfront DAM]. Les paramètres de groupe contrôlent également ce que les utilisateurs peuvent faire avec les ressources (affichage, téléchargement, modification, etc.) ils ont l’autorisation d’accès.

Lors de la création de groupes, il est essentiel de garder à l’esprit les dossiers de ressources auxquels les personnes membres de ce groupe auront accès dans la [!UICONTROL gestion des ressources numériques Workfront].

Les utilisateurs et utilisatrices sont les personnes qui ont un accès à [!UICONTROL Workfront DAM]. Une personne utilisatrice ne peut accéder à rien dans [!UICONTROL Workfront DAM] si elle n’est pas assignée à un groupe. Selon leurs besoins, les utilisateurs et utilisatrices peuvent appartenir à plusieurs groupes.

## Groupes par défaut

Deux groupes par défaut sont fournis avec [!UICONTROL Workfront DAM]. Tous les utilisateurs et toutes les utilisatrices appartiennent automatiquement à ces groupes, en fonction de leurs identifiants de connexion à [!UICONTROL Workfront DAM]. Vous ne pouvez pas ajouter ni supprimer d’utilisateurs ou d’utilisatrices de ces groupes :

* **Groupe de personnes invitées** : utilisé pour contrôler l’accès d’une personne anonyme. Il peut s’agir d’une personne sans informations d’identification de connexion ou d’une personne qui n’est pas actuellement connectée.
* **Groupe de personnes connectées** : tous les utilisateurs et utilisatrices connectés appartiennent à ce groupe.

Le groupe Admin et ses paramètres existent également par défaut. Vous pouvez ajouter des personnes à ce groupe, mais vous ne pouvez pas modifier les paramètres.

## Types de rôles

Lors de la création des groupes, un type de rôle leur est attribué. Le type de rôle détermine la partie du système de [!UICONTROL Workfront DAM] à laquelle les utilisateurs et les utilisatrices accèdent lorsqu’ils se connectent ([!UICONTROL Workfront DAM] ou [!UICONTROL Brand Connect]).

Trois types de rôles sont disponibles avec les licences de [!UICONTROL Workfront DAM] :

* **[!UICONTROL Brand Portal]** : ces personnes ont accès uniquement à [!UICONTROL Brand Connect], où elles peuvent afficher et télécharger les ressources approuvées.
* **[!UICONTROL Contributeur et contributrice]** : ces personnes peuvent accéder à [!UICONTROL Workfront DAM] et à [!UICONTROL Brand Connect]. Elles disposent de droits d’accès complet aux ressources et aux dossiers (affichage, téléchargement, chargement, modification, déplacement et suppression).
* **[!UICONTROL Administrateur et administratrice]** : les administrateurs et administratrices système ont accès à tous les éléments de [!UICONTROL Brand Connect] et de [!UICONTROL Workfront DAM], ainsi qu’à la possibilité de définir les paramètres globaux du système pour chacun. Ils peuvent également accéder aux ressources qui ont expiré ou qui ont été définies comme inactives.

<!-- 
Learn more graphic & documentation article link, below
* Understanding the difference between Workfront licenses and Workfront DAM role types
* 
-->
