---
title: Présentation de Webhooks
description: Découvrez comment utiliser un webhook pour créer une application afin de déterminer si un client ou une cliente est assez âgé pour acheter de l’alcool, le tout dans  [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-9051
exl-id: 7870c9db-d538-440a-8972-e7bc5ac5af93
recommendations: noDisplay,noCatalog
doc-type: video
source-git-commit: a4e61514567ac8c2b4ad5c9ecacb87bd83947731
workflow-type: ht
source-wordcount: '339'
ht-degree: 100%

---

# Présentation de Webhooks

Ce scénario crée une application pour les commerces de proximité afin qu’ils puissent facilement déterminer si un client ou une cliente est assez âgé pour acheter de l&#39;alcool. Le caissier ou la caissière doit simplement envoyer le nom et la date de naissance du client ou de la cliente ET un jeton de client ou de cliente vérifié vers une URL qui lui a été fournie. Une fois les informations saisies, notre scénario se déclenche pour calculer la réponse appropriée et la renvoyer au demandeur ou à la demandeuse.

![Image montrant l’utilisation du module Switch](assets/beyond-basic-modules-5.png)

## Présentation de Webhooks

Workfront recommande de regarder la vidéo de présentation de l’exercice avant d’essayer de recréer l’exercice dans votre propre environnement.

>[!VIDEO](https://video.tv.adobe.com/v/335292/?quality=12&learn=on)


## Configuration de Postman

Pour poursuivre l’exercice de présentation, vous devez télécharger l’application gratuite Postman. Suivez les étapes ci-dessous pour accéder à la zone de droite dans Postman pour l’exercice.

1. Créez un espace de travail, puis ouvrez-le.
1. Cliquez sur l’onglet Nouveau et créez une collection nommée Âge requis pour la consommation d’alcool.
1. Cliquez à nouveau sur l’onglet Nouveau et créez une requête GET nommée GET date de naissance.
1. Modifiez l’action de requête de GET en POST.
1. Accédez à la zone de sous-onglet Corps sous le champ URL POST.
1. Sélectionnez les données de formulaire sous le sous-onglet Autorisation.
1. Créez trois clés pour Nom, Date de naissance et Jeton client.

![Image montrant l’utilisation du module Switch](assets/beyond-basic-modules-6.png)

## À vous

>[!NOTE]
>
>Les exercices pratiques et les défis sont facultatifs et ne sont pas nécessaires pour terminer la formation Fusion.

Cet exercice repose sur ce que vous avez appris dans la présentation, mais la solution n’est pas fournie.

Créez un webhook Workfront qui attend la création de nouvelles mises à jour, et qui enregistre ensuite la date, le nom de la personne qui a réalisé la mise à jour et le contenu de la mise à jour. Envoyez-vous ces informations par e-mail.

**Conseil** : utilisez le module de déclenchement Événements de contrôle Workfront pour créer votre webhook. En outre, dans Workfront, les mises à jour sont appelées notes.

**Défi** : pouvez-vous trouver et ajouter l’URL de l’emplacement où la mise à jour a été effectuée pour qu’elle soit facile d’accès ?


## Vous voulez en savoir plus ? Nous recommandons ce qui suit :

[Documentation sur Workfront Fusion](https://experienceleague.adobe.com/docs/workfront/using/adobe-workfront-fusion/workfront-fusion-2.html?lang=fr)
