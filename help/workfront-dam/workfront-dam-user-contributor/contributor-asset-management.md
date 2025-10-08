---
title: Comprendre la gestion des ressources en tant que contributeur ou contributrice
description: Découvrez comment gérer des ressources dans [!UICONTROL Workfront DAM] pour améliorer votre workflow.
activity: use
feature: Digital Content and Documents
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
jira: KT-8996
exl-id: a09d0b0e-2631-414e-87e6-385ddbeb5cd2
doc-type: video
source-git-commit: bbdf99c6bc1be714077fd94fc3f8325394de36b3
workflow-type: ht
source-wordcount: '460'
ht-degree: 100%

---

# Comprendre la gestion des ressources en tant que contributeur ou contributrice

Dans cette vidéo, vous apprendrez à :

* Utiliser le menu Modifier d’une ressource
* Définir la date d’expiration
* Afficher les notifications
* Définir les paramètres de notification individuels
* Charger une version de la ressource
* Créer un dossier
* Appliquer un modèle de métadonnées à un dossier
* Définir les autorisations de dossier

>[!VIDEO](https://video.tv.adobe.com/v/335256/?quality=12&learn=on&enablevpops=1)

## Fonctionnement des versions des ressources

Une partie de votre workflow peut inclure la gestion de plusieurs versions (ou tours, épreuves, itérations, etc.) d’une ressource. Vous pouvez gérer toutes les versions via [!UICONTROL Workfront DAM].

Le système permet une gestion de versions automatique des ressources lorsqu’un fichier portant le même nom qu’un fichier existant est chargé dans le même dossier. Vérifiez auprès de votre administrateur ou administratrice système si cette fonctionnalité a été activée.

Si la gestion de versions automatique est activée, une ressource sera versionnée uniquement si elle est chargée dans le dossier contenant la ressource originale. Les deux fichiers doivent porter le même nom. Si la ressource est chargée dans un autre dossier, elle y est insérée en tant que nouveau fichier.
Si la gestion de versions n’est pas activée, un fichier portant le même nom qu’un fichier existant est chargé comme un nouveau fichier, quel que soit le dossier dans lequel il est placé. Cela peut entraîner l’affichage de deux ressources portant le même nom dans le même dossier.

Vous pouvez également charger manuellement les versions d’une ressource spécifique. Cliquez sur l’icône de modification de la ressource, puis sélectionnez **[!UICONTROL Charger une nouvelle version]**.

Si vous publiez une ressource avec des versions sur Brand Connect, l’utilisateur ou l’utilisatrice de Brand Connect ne voit que la dernière version de la ressource.

## Statut et expiration des dossiers et ressources

Les statuts permettent également de gérer l’accès aux dossiers et aux ressources dans [!UICONTROL Workfront DAM]. Les statuts peuvent être utilisés pour masquer certaines ressources ou certains dossiers des utilisateurs ou des utilisatrices de [!UICONTROL Brand Connect] ou pour faire expirer une ressource ou un dossier pour que seuls les responsables de l’administration puissent y accéder.

* **[!UICONTROL Actif]** : utilisé pour les ressources et les dossiers. Les ressources et les dossiers ayant le statut [!UICONTROL Actif] sont visibles par tous les utilisateurs et toutes les utilisatrices disposant d’autorisations et peuvent être publiés sur [!UICONTROL Brand Connect]. [!UICONTROL Actif] est indiqué par un point vert sur une ressource ou un dossier.
* **[!UICONTROL Inactif]** : utilisé pour les ressources et les dossiers. Les ressources et les dossiers ayant le statut [!UICONTROL Inactif] sont visibles pour les utilisateurs et utilisatrices de [!UICONTROL Workfront DAM], mais ne sont pas visibles dans [!UICONTROL Brand Connect]. [!UICONTROL Inactif] est indiqué par un point rouge sur une ressource ou un dossier.
* **[!UICONTROL Non expirée]** : utilisé pour les ressources uniquement. Il s’agit de l’état par défaut de toutes les ressources. Les ressources non expirées également [!UICONTROL Actives] sont visibles dans [!UICONTROL Brand Connect].
* **[!UICONTROL Expirée]** : utilisé pour les ressources uniquement. Les ressources dont le statut est [!UICONTROL Expirée] ne peuvent être téléchargées par aucun utilisateur ou aucune utilisatrice, à l’exception des responsables de l’administration système. Les ressources expirées sont visibles/non visibles dans [!UICONTROL Brand Connect], selon les configurations système.
