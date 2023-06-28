---
title: Présentation des routeurs
description: Découvrez comment utiliser un routeur pour transmettre les lots Pokemon et superhéros vers le chemin correct dans [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-9013
exl-id: 6c111e5b-1c8f-43fd-9e2d-16599de2a337
doc-type: video
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '878'
ht-degree: 0%

---

# Présentation des routeurs

Utilisez un routeur pour transmettre les lots Pokemon et superhéros vers le chemin approprié, puis créez une tâche pour chaque caractère.

![Une image du scénario Fusion](assets/universal-connectors-and-routing-2.png)

## Présentation des routeurs

Workfront recommande de regarder la vidéo de présentation de l’exercice avant d’essayer de recréer l’exercice dans votre propre environnement.

>[!VIDEO](https://video.tv.adobe.com/v/335272/?quality=12&learn=on)

## URL d’exercice

* Site web de l’API Superhero : `https://www.superheroapi.com/`
* Première URL pour l’exercice : `https://www.superheroapi.com/api/{access-token}/{character-id}/appearance`
* Deuxième URL pour l’exercice : `https://www.superheroapi.com/api/{access-token}/{character-id}/powerstats`

Si vous rencontrez des problèmes pour accéder à votre propre jeton superhero, vous pouvez utiliser ce jeton partagé : 10110256647253588. Veuillez tenir compte du nombre de fois que vous appelez à l’API superhero pour que ce jeton partagé continue à fonctionner pour tout le monde.

>[!TIP]
>
>Pour obtenir des instructions détaillées sur la manière d’effectuer la présentation, accédez à la section [Présentation des routeurs](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/fusion/exercises/routers.html?lang=en) exercice.


## Recherche d’éléments dans le panneau de mappage

Le champ Éléments de recherche situé en haut des panneaux de mappage vous permet de trouver rapidement des champs dans le panneau, même s’ils sont imbriqués dans des tableaux. La recherche n’est pas sensible à la casse.

![Image du premier panneau de recherche](assets/universal-connectors-and-routing-3.png)

![Image du deuxième panneau de recherche](assets/universal-connectors-and-routing-4.png)

## Conseils et astuces pour utiliser les API

Jusqu’à présent, vous avez travaillé avec une API très simple (interface de programmation d’application) qui ne nécessite aucune authentification supplémentaire pour extraire les informations nécessaires dans le scénario. Voici quelques conseils pour vous aider à naviguer avec les API et les connecteurs universels.

## Étape 1 : Détermination du type d’API

Workfront et de nombreux systèmes logiciels sont créés à l’aide d’une API REST (Really State Transfer), qui est aujourd’hui le type d’API le plus simple et le plus standard. Il existe toutefois d’autres exemples, tels que :

* SOAP (Simple Object Access Protocol) (l’API BAT Workfront est basée sur SOAP)
* FTP (protocole de transfert de fichiers)
* SFTP (protocole de transfert de fichiers sécurisé)
* Pour en savoir plus, effectuez une recherche web sur les types d’API et les mots-clés qui vous intéressent.

>[!NOTE]
>
>Lors de la connexion à des plateformes plus volumineuses comme Salesforce, différentes zones de ces plateformes fournissent différentes API. Assurez-vous de trouver le service auquel vous souhaitez vous connecter.

## Étape 2 : Déterminer le type d’authentification requis par l’API

L’authentification API est une forme d’identification utilisée pour contrôler l’accès à un service, par exemple lorsque vous essayez de vous connecter par le biais de Workfront Fusion. Il vous aide à prouver à un autre système que vous êtes autorisé à accéder au système. OAuth 2 est le type d’authentification le plus courant utilisé aujourd’hui. En savoir plus avec une recherche Internet sur l’authentification API.

L’authentification peut être l’aspect le plus difficile de l’utilisation d’une API. L’une des fonctionnalités les plus précieuses des connecteurs universels de Workfront Fusion est que Workfront Fusion peut gérer l’authentification pour vous lors de l’utilisation de méthodes d’authentification courantes, telles que l’authentification de base (OAuth 2, API Key, etc.). Une fois que vous avez créé une connexion à l’aide du module de fusion Workfront approprié pour votre méthode d’authentification (par exemple, OAuth 2), Workfront Fusion génère continuellement des clés d’API et/ou des jetons chaque fois que vous souhaitez exécuter votre scénario.

Découvrez les différents types d’authentification proposés par Workfront dans l’article Présentation de l’authentification améliorée sur Experience League.

## Étape 3 : Lisez la documentation de l’API et recherchez les points de terminaison nécessaires.

Lorsqu’une API interagit avec un autre système, les points de contact de cette communication sont considérés comme des points de terminaison. Un point de terminaison est l’emplacement où les API envoient des requêtes et où réside la ressource.

Lorsque vous interagissez avec une API à l’aide d’un connecteur universel, vous devez comprendre les points de terminaison pris en charge par l’API et les données requises pour chaque requête. La documentation de l’API doit décrire les points de terminaison d’une API et comment effectuer des opérations courantes comme créer, lire, mettre à jour ou supprimer. L’exécution de ces appels nécessite une certaine pratique, en particulier si vous commencez à effectuer des appels d’API ou à utiliser une nouvelle API.

Découvrez les connecteurs universels de Workfront Fusion et comment les configurer pour se connecter aux API dont vous avez besoin sur Experience League.

## Note finale

Vous pouvez consulter la liste complète de nos connecteurs d’applications préconfigurés dans Experience League. Si vous souhaitez proposer un nouveau connecteur d’application à l’équipe produit de Workfront Fusion, soumettez votre idée à Innovation Lab. Si vous ne l&#39;avez pas déjà fait, découvrez le laboratoire de l&#39;innovation, et comment voter pour des idées et participer à la priorisation du classement par deux ans. Si vous avez déjà accès au laboratoire de l&#39;innovation, connectez-vous et soumettez vos idées.

## Votre tour

>[!NOTE]
>
>Les exercices pratiques et les défis sont facultatifs et ne sont pas nécessaires pour terminer la formation Fusion.

Cet exercice repose sur ce que vous avez appris dans la présentation, mais la solution n’est pas fournie.

Dans le module Définir plusieurs variables pour les caractères Pokemon, créez une variable appelée &quot;Démarrage (niveau)&quot;. Mappez le nom des statistiques de pokemon dans cette variable. Utilisez la fonctionnalité de valeur de tableau pour modifier l’affichage du tableau, de sorte que chaque état soit une nouvelle ligne, comme illustré ci-dessous.

**Conseil :** Il n’existe que six statistiques Pokemon différentes avec un niveau correspondant.

![Une image des statistiques](assets/universal-connectors-and-routing-5.png)

**Défi :** Voyez si vous pouvez utiliser les formules du tableau pour obtenir les Possibilités d’afficher la même manière que ci-dessus sous la forme de lignes différentes plutôt que sous la forme d’une chaîne de valeurs séparées par une virgule. Il y a un indice dans la capture d&#39;écran ci-dessous.

![Image d’un nom de tableau](assets/universal-connectors-and-routing-6.png)

## Vous souhaitez en savoir plus ? Nous vous recommandons ce qui suit :

[Documentation de Workfront Fusion](https://experienceleague.adobe.com/docs/workfront/using/adobe-workfront-fusion/workfront-fusion-2.html?lang=en)
