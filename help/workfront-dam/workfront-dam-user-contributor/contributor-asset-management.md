---
title: Découvrez comment gérer les ressources dans [!UICONTROL Gestion des actifs numériques Workfront]
description: Découvrez comment gérer des ressources dans [!UICONTROL Gestion des actifs numériques Workfront] pour améliorer votre workflow.
activity: use
feature: Digital Content and Documents
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
kt: 8996
exl-id: a09d0b0e-2631-414e-87e6-385ddbeb5cd2
doc-type: video
source-git-commit: 650e4d346e1792863930dcebafacab4c88f2a8bc
workflow-type: tm+mt
source-wordcount: '459'
ht-degree: 0%

---

# Contributeur : gestion des ressources

Dans cette vidéo, vous apprendrez à :

* Utilisation du menu Modifier d’une ressource
* Définition d’une date d’expiration
* Affichage des notifications
* Définition des paramètres de notification individuels
* Téléchargement d’une version de ressource
* Création d’un dossier
* Application d’un modèle de métadonnées à un dossier
* Définition des autorisations de dossier

>[!VIDEO](https://video.tv.adobe.com/v/335256/?quality=12&learn=on)

## Fonctionnement des versions de ressources

Une partie de votre workflow peut inclure la gestion de plusieurs versions (ou tours, BAT, itérations, etc.) d’une ressource. Vous pouvez gérer toutes les versions via [!UICONTROL Gestion des actifs numériques Workfront].

Le système permet le contrôle automatique de la version des ressources lorsqu’un fichier portant le même nom qu’un fichier existant est chargé dans le même dossier. Vérifiez auprès de votre administrateur système si cette fonctionnalité a été activée.

Si le contrôle automatique des versions est activé, une ressource n’est convertie que si elle est chargée dans le dossier contenant la ressource d’origine. Les deux ressources doivent avoir le même nom de fichier. Si la ressource est chargée dans un autre dossier, elle est placée sous la forme d’un nouveau fichier.
Si le contrôle de version n’est pas activé, un fichier portant le même nom qu’un fichier existant est téléchargé en tant que nouveau fichier, quel que soit le dossier dans lequel il est placé. Cela peut entraîner l’affichage de deux ressources portant le même nom dans le même dossier.

Vous pouvez également charger manuellement des versions d’une ressource spécifique. Cliquez sur l’icône de modification de la ressource, puis sélectionnez **[!UICONTROL Chargement d’une nouvelle version]**.

Si vous publiez une ressource avec des versions sur Brand Connect, l’utilisateur de Brand Connect ne voit que la dernière version de la ressource.

## État et expiration des dossiers et ressources

Les états sont un autre moyen de gérer l’accès aux dossiers et aux ressources dans [!UICONTROL Gestion des actifs numériques Workfront]. Les états peuvent être utilisés pour masquer certaines ressources ou certains dossiers. [!UICONTROL Brand Connect] pour que personne, à l’exception de l’administrateur système, ne puisse y accéder.

* **[!UICONTROL Principal]**: utilisé pour les ressources et les dossiers. Ressources et dossiers avec [!UICONTROL Principal] sont visibles par tous les utilisateurs disposant d’autorisations et peuvent être publiés sur [!UICONTROL Brand Connect]. [!UICONTROL Principal] est indiqué par un point vert sur une ressource ou un dossier.
* **[!UICONTROL Inactif]**: utilisé pour les ressources et les dossiers. Ressources et dossiers avec [!UICONTROL Inactif] sont visibles à [!UICONTROL Gestion des actifs numériques Workfront] mais ne sont pas visibles dans la variable [!UICONTROL Brand Connect]. [!UICONTROL Inactif] est indiqué par un point rouge sur une ressource ou un dossier.
* **[!UICONTROL Non expiré]**: utilisé uniquement pour les ressources. Il s’agit de l’état par défaut de toutes les ressources. Ressources non expirées qui également [!UICONTROL Principal] sont visibles dans la variable [!UICONTROL Brand Connect].
* **[!UICONTROL Expiré]**: utilisé uniquement pour les ressources. Ressources avec la fonction [!UICONTROL Expiré] ne peut pas être téléchargé par un utilisateur, à l’exception de l’administrateur système. Les ressources expirées sont visibles/non visibles dans la variable [!UICONTROL Brand Connect], selon les configurations système.
