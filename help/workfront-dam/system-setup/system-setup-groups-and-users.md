---
title: Présentation des groupes et des utilisateurs dans [!UICONTROL Gestion des actifs numériques Workfront]
description: Découvrez comment créer des dossiers, des groupes et des utilisateurs dans [!UICONTROL Gestion des actifs numériques Workfront]. Comprendre les types de rôles utilisateur et accorder des autorisations aux dossiers.
activity: use
feature: Digital Content and Documents
type: Tutorial
role: Admin
level: Intermediate
team: Technical Marketing
kt: 8967
exl-id: 4ebf675c-b72d-447e-b131-a89acb449e15
doc-type: video
source-git-commit: 650e4d346e1792863930dcebafacab4c88f2a8bc
workflow-type: tm+mt
source-wordcount: '416'
ht-degree: 0%

---

# Configuration du système : groupes et utilisateurs

Dans cette vidéo, vous apprendrez à :

* Comprendre comment les configurations de groupe affectent l’accès aux ressources
* Création de dossiers, de groupes et d’utilisateurs dans un ordre spécifique
* Présentation des types de rôles utilisateur
* Octroi d’autorisations aux dossiers
* Création et modification de groupes
* Ajout et modification d’utilisateurs

>[!VIDEO](https://video.tv.adobe.com/v/335230/?quality=12&learn=on)

## Révision des groupes et des utilisateurs

Lorsque vous configurez votre [!UICONTROL Gestion des actifs numériques Workfront] système, il est important de tenir compte des rôles que jouent les utilisateurs et les groupes dans l’ensemble.

Les groupes contrôlent l’accès aux dossiers de ressources dans [!UICONTROL Gestion des actifs numériques Workfront]. Les paramètres de groupe contrôlent également ce que les utilisateurs peuvent faire des ressources (affichage, téléchargement, modification, etc.) ils ont la permission d&#39;y accéder.

Lors de la création de groupes, il est essentiel de garder à l’esprit les dossiers de ressources auxquels les membres de ce groupe auront accès dans [!UICONTROL Gestion des actifs numériques Workfront].

Les utilisateurs sont les individus qui disposent de connexions à [!UICONTROL Gestion des actifs numériques Workfront]. Un utilisateur ne peut accéder à rien dans [!UICONTROL Gestion des actifs numériques Workfront] sauf s’ils sont affectés à un groupe. Selon leurs besoins, les utilisateurs peuvent appartenir à plusieurs groupes.

## Groupes par défaut

Deux groupes par défaut sont fournis avec [!UICONTROL Gestion des actifs numériques Workfront]. Tous les utilisateurs appartiennent automatiquement à ces groupes, selon qu’ils ont ou non [!UICONTROL Gestion des actifs numériques Workfront] informations de connexion. Vous ne pouvez pas ajouter ni supprimer d’utilisateurs de ces groupes :

* **Groupe d’invités**: utilisé pour contrôler l’accès d’un utilisateur anonyme. Il peut s’agir d’une personne sans informations d’identification de connexion ou d’un utilisateur qui n’est pas actuellement connecté.
* **Connecté**-Dans le groupe : tous les utilisateurs connectés appartiennent à ce groupe.

Le groupe Admin et ses paramètres existent également par défaut. Vous pouvez ajouter des utilisateurs à ce groupe, mais vous ne pouvez pas modifier les paramètres.

## Types de rôles

À mesure que des groupes sont créés, un type de rôle leur est attribué. Le type de rôle détermine la partie de [!UICONTROL Gestion des actifs numériques Workfront] les utilisateurs système reçoivent lorsqu’ils se connectent — [!UICONTROL Gestion des actifs numériques Workfront] ou [!UICONTROL Brand Connect].

Trois types de rôles sont disponibles avec [!UICONTROL Gestion des actifs numériques Workfront] licences :

* **[!UICONTROL Brand Portal]**: ces utilisateurs n’ont accès qu’à [!UICONTROL Brand Connect], où ils peuvent afficher et télécharger les ressources approuvées.
* **[!UICONTROL Contributeur]**: ces utilisateurs peuvent accéder à [!UICONTROL Gestion des actifs numériques Workfront] et [!UICONTROL Brand Connect]. Ils disposent de droits d’accès complets aux ressources et aux dossiers : affichage, téléchargement, chargement, modification, déplacement et suppression.
* **[!UICONTROL Administrateur]**: les administrateurs système ont accès à tout ce qui se trouve dans [!UICONTROL Brand Connect] et [!UICONTROL Gestion des actifs numériques Workfront], plus la possibilité d’établir les paramètres système globaux pour chacun d’eux. Ils peuvent également accéder aux ressources qui ont expiré ou qui ont été définies comme inactives.

<!-- 
Learn more graphic & documentation article link, below
* Understanding the difference between Workfront licenses and Workfront DAM role types
* -->
