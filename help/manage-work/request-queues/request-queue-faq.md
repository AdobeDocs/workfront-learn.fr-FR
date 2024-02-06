---
title: Réponses aux questions courantes sur les files d’attente de demandes
description: Obtenez des réponses aux questions courantes sur les files d’attente des demandes dans  [!DNL  Workfront].
feature: Work Management
type: Tutorial
role: Admin, User
level: Beginner
last-substantial-update: 2023-07-18T00:00:00Z
jira: KT-10101
exl-id: bfa3ae5f-9618-444c-9eb8-5d82db9a77c7
source-git-commit: ec82cd0aafb89df7b3c46eb716faf3a25cd438a2
workflow-type: tm+mt
source-wordcount: '406'
ht-degree: 100%

---

# Réponses aux questions courantes sur les files d’attente de demandes

**Pourquoi puis-je voir une file d’attente des demandes, mais pas mon utilisateur ou utilisatrice ?**

Dans l’onglet [!UICONTROL Détails de la file d’attente] de votre file d’attente des demandes/projet, assurez-vous que votre utilisateur ou utilisatrice répond aux critères du champ « Qui peut ajouter des demandes à cette file d’attente ? ».  

**J’ai donné aux utilisateurs et aux utilisatrices l’accès à la file d’attente, mais maintenant ils peuvent aussi voir le projet de file d’attente des demandes. Pourquoi ?**

Cela a à voir avec la manière dont vous leur avez donné accès à la file d’attente des demandes.

Si vous avez utilisé l’outil [!UICONTROL Partage] à partir de la page de destination du projet de la file d’attente des demandes, vous avez donné à ces utilisateurs et utilisatrices l’accès pour afficher le projet dans la liste des projets.

Si, toutefois, vous souhaitez ne leur accorder l’accès que pour envoyer une demande à la file d’attente, accédez à Configuration de la file d’attente et sélectionnez l’option appropriée sous « Qui peut ajouter des demandes à ce projet ».

**Puis-je transformer une demande en projet ?**

Oui. Vous pouvez convertir des problèmes en tâches ou en projets en fonction des besoins.

Consultez cet article pour plus d’informations : [Problèmes de conversion](https://experienceleague.adobe.com/docs/workfront/using/manage-work/issues/convert-issues/convert-issues-overview.html?lang=fr).

**Où puis-je trouver une file d’attente des demandes pour apporter des modifications ?**

Vous pouvez utiliser le champ [!UICONTROL Rechercher] dans la barre de navigation ou la trouver répertoriée dans la zone [!UICONTROL Projets].

Si vous ouvrez une demande à partir de la file d’attente des demandes, vous pouvez cliquer sur le nom du projet dans la zone des chemins de navigation.

**Puis-je transférer les informations d’un formulaire personnalisé de demande vers un formulaire personnalisé de projet ?**

Oui. Lorsque vous créez un formulaire personnalisé, sélectionnez à la fois [!UICONTROL Projet] et [!UICONTROL Problème] comme types d’objet. Joignez le formulaire personnalisé à la demande. Lorsque vous convertissez la demande en projet, le formulaire personnalisé est automatiquement joint au nouveau projet et les valeurs contenues dans tous les champs apparaissent à la fois dans les formulaires personnalisés de demande et de projet.

**Je regarde un rapport de projet ou de tâche. Comment puis-je savoir de quelle demande provient cet objet ?**

Vous pouvez accéder aux champs du **[!UICONTROL Problème converti]** et les sources de champ **[!UICONTROL Créateur du problème converti]** pour ajouter ces informations aux rapports de projet et de tâche.

**Quel est le meilleur moyen de filtrer les files d’attente des demandes dans un rapport ?**

Si le filtre de votre projet inclut **File d’Attente > Est publique > Est égal à > Aucun**, votre rapport affiche uniquement les projets qui **NE SONT PAS** des files d’attente des demandes.

Si le filtre de votre projet inclut **File d’attente > Est publique > N’est pas égal à > Aucun**, votre rapport affiche uniquement les projets qui **SONT** des files d’attente des demandes.
