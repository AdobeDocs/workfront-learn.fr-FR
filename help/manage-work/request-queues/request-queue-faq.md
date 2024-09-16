---
title: Réponses aux questions courantes sur les files d’attente de demandes
description: Obtenez des réponses aux questions courantes sur les files d’attente des demandes dans  [!DNL  Workfront].
feature: Work Management
type: Tutorial
role: Admin, User
level: Beginner
last-substantial-update: 2024-09-16T00:00:00Z
recommendations: noDisplay,noCatalog
jira: KT-10101
exl-id: bfa3ae5f-9618-444c-9eb8-5d82db9a77c7
source-git-commit: e9a4f2bcd39e2598ff540bb4f300e891e817e939
workflow-type: tm+mt
source-wordcount: '683'
ht-degree: 50%

---

# Réponses aux questions courantes sur les files d’attente de demandes

**Pourquoi puis-je voir une file d’attente des demandes, mais pas mon utilisateur ou utilisatrice ?**

Dans l’onglet [!UICONTROL Détails de la file d’attente] de votre file d’attente des demandes/projet, assurez-vous que votre utilisateur ou utilisatrice répond aux critères du champ « Qui peut ajouter des demandes à cette file d’attente ? ».  

Pour plus d’informations, visionnez cette vidéo :

>[!VIDEO](https://video.tv.adobe.com/v/3434156/?quality=12&learn=on)

**J’ai donné aux utilisateurs et aux utilisatrices l’accès à la file d’attente, mais maintenant ils peuvent aussi voir le projet de file d’attente des demandes. Pourquoi ?**

Dans &quot;Qui peut ajouter des requêtes à cette file d’attente ?&quot; Si vous sélectionnez &quot;Personnes ayant accès à ce projet&quot;, toute personne à qui vous accordez des droits d’affichage pour utiliser la file d’attente de demandes pourra également afficher la file d’attente de demandes dans une liste de projets. Pour éviter cela, utilisez l’option &quot;Personnes dans la société de ce projet&quot; ou &quot;Personnes dans le groupe de ce projet&quot;.

**Puis-je transformer une demande en projet ?**

Oui. Vous pouvez convertir des problèmes en tâches ou en projets en fonction des besoins.

Ces tutoriels vous montrent comment :

* [Convertir un problème/une demande en projet](/help/manage-work/issues-requests/create-a-project-from-a-request.md)

* [Convertir un problème/une requête en une tâche.](/help/manage-work/issues-requests/convert-issues-to-other-work-items.md)

**Où puis-je trouver une file d’attente des demandes pour apporter des modifications ?**

Vous pouvez utiliser le champ [!UICONTROL Rechercher] dans la barre de navigation ou la trouver répertoriée dans la zone [!UICONTROL Projets].

Si vous ouvrez une requête à partir de la file d’attente des demandes, vous pouvez cliquer sur le nom du projet dans la zone des chemins de navigation.

**Puis-je transférer les informations d’un formulaire personnalisé de demande vers un formulaire personnalisé de projet ?**

Oui. Lorsque vous créez un formulaire personnalisé, sélectionnez à la fois [!UICONTROL Projet] et [!UICONTROL Problème] comme types d’objet. Vous pouvez également modifier un formulaire personnalisé de projet pour inclure le type d’objet de problème et vice versa.

Joignez le formulaire personnalisé à la demande. Lorsque vous convertissez la demande en projet, le formulaire personnalisé est automatiquement joint au nouveau projet et les valeurs contenues dans tous les champs apparaissent à la fois dans les formulaires personnalisés de demande et de projet.

**Je regarde un rapport de projet ou de tâche. Comment puis-je savoir de quelle demande provient cet objet ?**

Vous pouvez accéder aux champs du **[!UICONTROL Problème converti]** et les sources de champ **[!UICONTROL Créateur du problème converti]** pour ajouter ces informations aux rapports de projet et de tâche.

Pour plus d’informations, visionnez cette vidéo :

>[!VIDEO](https://video.tv.adobe.com/v/3434176/?quality=12&learn=on)


**Quel est le meilleur moyen de filtrer les files d’attente des demandes dans un rapport ?**

Si le filtre de votre projet inclut **File d’Attente > Est publique > Est égal à > Aucun**, votre rapport affiche uniquement les projets qui **NE SONT PAS** des files d’attente des demandes.

Si le filtre de votre projet inclut **File d’attente > Est publique > N’est pas égal à > Aucun**, votre rapport affiche uniquement les projets qui **SONT** des files d’attente des demandes.

Pour plus d’informations, visionnez cette vidéo :

>[!VIDEO](https://video.tv.adobe.com/v/3434329/?quality=12&learn=on)

**Est-il préférable de créer un état personnalisé de la file d’attente des demandes ?**

Certains clients créent un état personnalisé de la file d’attente des demandes qui correspond à Actuel. Ils peuvent ensuite exécuter un rapport présentant toutes les files d’attente de requête ou exclure facilement les files d’attente d’un rapport. Bien que cela ait l’avantage d’être plus convivial que d’utiliser **Queue&quot;Is Public&quot;Not Equal&quot;None**, cela présente l’inconvénient que les personnes qui créent des files d’attente de demandes peuvent oublier de l’utiliser, puisque l’état actuel fonctionne également et est ce qu’elles verront dans la plupart des documents de formation. Pour cette raison, de nombreux clients choisissent de ne pas utiliser un état personnalisé de la file d’attente des demandes.

Cependant, si vous utilisez déjà l’état File d’attente des demandes dans votre entreprise et que vous souhaitez simplement vous assurer qu’il est utilisé correctement (ou pour corriger les cas où il ne l’est pas), vous pouvez créer le rapport **File d’attente des demandes actives** décrit dans la vidéo ci-dessus, et modifier le filtre pour **Projet&quot;État égal à&quot;Égal à actuel** à **Projet&quot;État>État>Égal&quot;> Current**. Vous affichez ainsi toutes les files d’attente de requête actives qui utilisent l’état actuel au lieu de l’état de file d’attente de requête que vous souhaitez qu’elles utilisent. Sélectionnez tous les projets qui s’affichent et effectuez une modification en masse pour modifier les états en File d’attente des demandes.

## Tutoriels recommandés sur cette rubrique

* [Comprendre les files d’attente de demandes](/help/manage-work/request-queues/understand-request-queues.md)
* [Créer une file d’attente de demandes](/help/manage-work/request-queues/create-a-request-queue.md)
* [Comprendre les paramètres d’un flux de requêtes](/help/manage-work/request-queues/understand-settings-for-a-flow-request.md)
* [Créer un flux de demandes](/help/manage-work/request-queues/create-a-request-flow.md)
* [Créer une file d’attente des demandes pour les commentaires de l’équipe d’administration système](/help/manage-work/request-queues/create-a-system-admin-feedback-request-queue.md)
