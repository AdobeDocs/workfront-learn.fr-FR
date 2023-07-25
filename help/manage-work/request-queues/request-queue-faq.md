---
title: Réponses aux questions courantes sur les files d’attente de requêtes
description: Obtenir des réponses aux questions courantes sur les files d’attente dans [!DNL  Workfront].
feature: Work Management
type: Tutorial
role: Admin, User
level: Beginner, Intermediate
last-substantial-update: 2023-07-18T00:00:00Z
jira: KT-10101
exl-id: bfa3ae5f-9618-444c-9eb8-5d82db9a77c7
source-git-commit: ce2aad1cd0ecb7d568ed9a01d97147cbd126ca05
workflow-type: tm+mt
source-wordcount: '414'
ht-degree: 0%

---

# Questions courantes à propos des files d’attente de requêtes

**Pourquoi puis-je voir une file d’attente de demandes, mais pas mon utilisateur ?**

Dans le [!UICONTROL Détails de la file] dans l’onglet de votre file d’attente de requêtes/projet, assurez-vous que votre utilisateur correspond aux critères de &quot;Qui peut ajouter des requêtes à cette file d’attente ?&quot;. champ .

**J’ai donné aux utilisateurs l’accès à la file d’attente, mais ils peuvent désormais aussi voir le projet de la file d’attente des demandes. Pourquoi ?**

Cela a à voir avec la manière dont vous leur avez donné accès à la file d’attente des demandes.

Si vous avez utilisé la variable [!UICONTROL Partage] à partir de la page d’entrée du projet de la file d’attente des demandes, vous avez donné à ces utilisateurs l’accès pour afficher le projet dans la liste des projets.

Si, toutefois, vous souhaitez ne leur accorder l’accès que pour envoyer une requête à la file d’attente, accédez à Configuration de la file d’attente et sélectionnez l’option appropriée sous &quot;Qui peut ajouter des requêtes à ce projet&quot;.

**Puis-je transformer une demande en projet ?**

Oui. Vous pouvez convertir des problèmes en tâches ou en projets en fonction des besoins.

Consultez cet article pour plus d’informations : [Problèmes de conversion](https://experienceleague.adobe.com/docs/workfront/using/manage-work/issues/convert-issues/convert-issues-overview.html?lang=en).

**Où puis-je trouver une file d’attente de demandes pour apporter des modifications ?**

Vous pouvez utiliser la variable [!UICONTROL Rechercher] dans la barre de navigation ou recherchez-la répertoriée dans le [!UICONTROL Projets] zone.

Si vous ouvrez une requête à partir de la file d’attente des demandes, vous pouvez cliquer sur le nom du projet dans la zone des chemins de navigation.

**Puis-je transférer les informations d’un formulaire personnalisé de demande vers un formulaire personnalisé de projet ?**

Oui. Lorsque vous créez un formulaire personnalisé, sélectionnez les deux [!UICONTROL Projet] et [!UICONTROL Problème] comme type d’objet. Joignez le formulaire personnalisé à la requête. Lorsque vous convertissez la demande en projet, le formulaire personnalisé est automatiquement joint au nouveau projet et les valeurs contenues dans tous les champs apparaissent à la fois dans les formulaires personnalisés de demande et de projet.

**Je consulte un rapport de projet ou de tâche. Comment puis-je savoir de quelle requête provient cet objet ?**

Vous pouvez accéder aux champs du **[!UICONTROL Problème converti]** et le **[!UICONTROL Émetteur de problème converti]** sources de champ pour ajouter ces informations aux rapports de projet et de tâche.

**Quel est le meilleur moyen de filtrer les files d’attente de requête dans un rapport ?**

Si le filtre de votre projet inclut **File D’Attente &quot; Est Publique > Egal > Aucun** votre rapport affiche uniquement les projets qui **NOT** files d’attente.

Si le filtre de votre projet inclut **File d’attente &quot; Est Publique > N’Est Pas Égal > Aucun** votre rapport affiche uniquement les projets qui **ARE** files d’attente.
