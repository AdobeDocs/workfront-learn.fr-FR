---
title: Présentation des exécutions incomplètes
description: Découvrez ce que sont les exécutions incomplètes et comment gérer une erreur qui entraîne une exécution incomplète dans [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-9066
exl-id: 3b7bf669-4736-4ba5-bcec-0d3fe0b2ce74
recommendations: noDisplay,catalog
doc-type: video
autotag-review: '2026-05-06T16:07:51.152Z'
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
    internal-label: Beginner
source-git-commit: 54883ad8c8df3aaee06ba8f8dca64227594c1c77
workflow-type: tm+mt
source-wordcount: '280'
ht-degree: 93%
---
# Présentation des exécutions incomplètes

Les exécutions incomplètes peuvent être stockées dans Workfront Fusion où elles peuvent être revues et résolues ultérieurement. Découvrez comment tirer parti de cette fonctionnalité extraordinaire.

Dans cette vidéo, vous apprendrez :

* Présentation des exécutions incomplètes
* Gestion d’une erreur qui entraîne une exécution incomplète

>[!VIDEO](https://video.tv.adobe.com/v/335307/?quality=12&learn=on&enablevpops=1)

## Erreurs entraînant des exécutions incomplètes

Il existe plusieurs catégories d’erreurs qui entraînent le stockage d’exécutions incomplètes.

Les différents types d’erreurs reçues dépendent des API auxquelles vous vous connectez. Il peut s’agir d’une erreur de validation due à des données incomplètes ou erronées, le plus souvent cela vient d’un élément manquant qui est attendu pour traiter avec succès toutes les données passant par un module. Les erreurs peuvent également provenir de l’indisponibilité de la destination finale en raison d’un échec temporaire ou à long terme de la connexion (par exemple, lors de la connexion à un serveur de messagerie ou FTP distant).

Si une erreur se produit sur le premier module du scénario, l’exécution s’arrête immédiatement et aucune exécution incomplète n’est stockée.

Si une erreur se produit sur un autre module et qu’aucun itinéraire de gestionnaire d’erreur n’est associé, alors :

* Si le type d’erreur est ConnectionError, RateLimitError, OutOfSpaceError ou ModuleTimeoutError, un enregistrement d’exécution incomplet AVEC reprise automatique est stocké.
* Si le type d’erreur est DataError, InvalidConfigurationError, InvalidAccessTokenError, UnexpectedError, MaxFileSizeExceededError ou MaxResultsExceededError, un enregistrement d’exécution incomplet SANS reprise automatique est stocké.
* Si le type d’erreur est autre que ci-dessus, l’exécution échoue.

## Vous voulez en savoir plus ? Nous recommandons ce qui suit :

[Documentation de Workfront Fusion](https://experienceleague.adobe.com/fr/docs/workfront-fusion/using/get-started-with-fusion/understand-workfront-fusion/workfront-fusion-overview)
