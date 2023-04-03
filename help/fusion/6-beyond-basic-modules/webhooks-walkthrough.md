---
title: Présentation détaillée de Webhooks
description: Découvrez comment utiliser un webhook pour créer une application afin de déterminer si un client est assez âgé pour acheter de l’alcool, le tout dans [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
kt: 9051
exl-id: 7870c9db-d538-440a-8972-e7bc5ac5af93
doc-type: video
source-git-commit: 650e4d346e1792863930dcebafacab4c88f2a8bc
workflow-type: tm+mt
source-wordcount: '372'
ht-degree: 0%

---

# Présentation détaillée de Webhooks

## Vue d’ensemble

Ce scénario crée une application de commerce de proximité qui leur permet de déterminer facilement si un client est assez âgé pour acheter de l’alcool. La caisse doit simplement publier le nom et la date de naissance du client ET un jeton client vérifié sur une URL fournie. Une fois saisie, notre scénario est déclenché pour calculer la réponse appropriée et la renvoyer au demandeur.

![Une image à l’aide du module switch](assets/beyond-basic-modules-5.png)

## Présentation détaillée de Webhooks

Workfront recommande de regarder la vidéo de présentation de l’exercice avant d’essayer de recréer l’exercice dans votre propre environnement.

>[!VIDEO](https://video.tv.adobe.com/v/335292/?quality=12&learn=on)

>[!TIP]
>
>Pour obtenir des instructions détaillées sur la manière d’effectuer la présentation, accédez à la section [Présentation détaillée de Webhooks](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/fusion/exercises/webhooks.html?lang=en) exercice.

## Configuration de Postman

Pour suivre l’exercice pas à pas, vous devez télécharger l’application Postman gratuite. Suivez les étapes ci-dessous pour accéder à la zone droite de Postman pour l’exercice.

1. Créez un espace de travail, puis ouvrez-le.
1. Cliquez sur l’onglet Nouveau et créez une collection nommée Age de la boisson.
1. Cliquez à nouveau sur l’onglet Nouveau et créez une demande de GET nommée GET de la date de naissance.
1. Modifiez l’action de requête de GET en POST.
1. Accédez à la zone Sous-onglet Corps sous le champ URL du POST .
1. Sélectionnez les données de formulaire sous le sous-onglet Autorisation .
1. Créez trois clés pour Name, Birthdate et clientToken.

![Une image à l’aide du module switch](assets/beyond-basic-modules-6.png)

## Votre tour

>[!NOTE]
>
>Les exercices pratiques et les défis sont facultatifs et ne sont pas nécessaires pour terminer la formation Fusion.

Cet exercice repose sur ce que vous avez appris dans la présentation, mais la solution n’est pas fournie.

Créez un webhook Workfront qui attend les nouvelles mises à jour créées, puis consigne la date, le nom de la personne qui a effectué la mise à jour et ce que dit la mise à jour. Envoyez-vous cette information par courriel.

**Conseil**: Utilisez le module de déclenchement Événements de contrôle Workfront pour créer votre webhook. En outre, dans Workfront, les mises à jour sont appelées notes.

**Défi**: Pouvez-vous trouver et ajouter l’URL de l’emplacement où la mise à jour a été effectuée pour un accès facile ?


## Vous souhaitez en savoir plus ? Nous vous recommandons ce qui suit :

[Documentation de Workfront Fusion](https://experienceleague.adobe.com/docs/workfront/using/adobe-workfront-fusion/workfront-fusion-2.html?lang=en)
