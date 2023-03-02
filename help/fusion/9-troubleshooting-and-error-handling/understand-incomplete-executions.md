---
title: Présentation des exécutions incomplètes
description: Découvrez les exécutions incomplètes et comment gérer une erreur qui entraîne une exécution incomplète dans [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
kt: 9066
exl-id: 3b7bf669-4736-4ba5-bcec-0d3fe0b2ce74
doc-type: video
source-git-commit: d39754b619e526e1a869deedb38dd2f2b43aee57
workflow-type: tm+mt
source-wordcount: '270'
ht-degree: 0%

---

# Présentation des exécutions incomplètes

Les exécutions incomplètes peuvent être stockées dans Workfront Fusion, où elles pourront être revues et résolues ultérieurement. Découvrez comment tirer parti de cette fonctionnalité extraordinaire.

Dans cette vidéo, vous apprendrez :

* Quelles exécutions incomplètes
* Comment gérer une erreur qui entraîne une exécution incomplète

>[!VIDEO](https://video.tv.adobe.com/v/335307/?quality=12)

## Erreurs résultant en exécutions incomplètes

Il existe plusieurs catégories d’erreurs qui entraînent le stockage d’exécutions incomplètes.

Les différents types d’erreur reçus dépendent des API auxquelles vous vous connectez. L’erreur peut être une erreur de validation provenant de données incomplètes ou erronées, principalement en raison d’un élément manquant qui est attendu pour traiter avec succès toutes les données passant par un module. Les erreurs peuvent également provenir de l’indisponibilité de la destination finale en raison d’un échec temporaire ou à long terme de la connexion (par exemple, lors de la connexion à un serveur de messagerie ou FTP distant).

Si une erreur se produit sur le premier module du scénario, l’exécution s’arrête immédiatement et aucune exécution incomplète n’est stockée.

Si une erreur se produit sur un autre module et qu’aucun itinéraire de gestionnaire d’erreur n’est associé, alors :

* Si le type d’erreur est ConnectionError, RateLimitError, OutOfSpaceError ou ModuleTimeoutError, un enregistrement d’exécution incomplet AVEC reprise automatique est stocké.
* Si le type d’erreur est DataError, InvalidConfigurationError, InvalidAccessTokenError, UnpendingError, MaxFileSizeExceededError ou MaxResultsExceededError, un enregistrement d’exécution incomplet SANS reprise automatique est stocké.
* Si le type d&#39;erreur est autre que ci-dessus, l&#39;exécution échoue.

## Vous souhaitez en savoir plus ? Nous vous recommandons ce qui suit :

[Documentation de Workfront Fusion](https://experienceleague.adobe.com/docs/workfront/using/adobe-workfront-fusion/workfront-fusion-2.html?lang=en)
