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
source-git-commit: d17df7162ccaab6b62db34209f50131927c0a532
workflow-type: tm+mt
source-wordcount: '414'
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

>[!VIDEO](https://video.tv.adobe.com/v/335230/?quality=12&learn=on&enablevpops)

## Réviser des groupes, des utilisateurs et des utilisatrices

Lorsque vous configurez votre système de [!UICONTROL gestion des ressources numériques Workfront], il est important de tenir compte des rôles que jouent les utilisateurs, les utilisatrices et les groupes dans l’ensemble.

Les groupes contrôlent l’accès aux dossiers de ressources dans [!UICONTROL Workfront DAM]. Les paramètres de groupe contrôlent également ce que les utilisateurs peuvent faire avec les ressources (affichage, téléchargement, modification, etc.) auxquelles ils ont accès.

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
* -->
