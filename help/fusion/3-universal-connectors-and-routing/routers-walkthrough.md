---
title: Présentation des routeurs
description: Découvrez comment utiliser un routeur pour faire passer les lots de Pokemon vs. super-héros par le bon chemin dans  [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-9013
exl-id: 6c111e5b-1c8f-43fd-9e2d-16599de2a337
recommendations: noDisplay,catalog
doc-type: video
source-git-commit: bbdf99c6bc1be714077fd94fc3f8325394de36b3
workflow-type: ht
source-wordcount: '853'
ht-degree: 100%

---

# Présentation des routeurs

Utilisez un routeur pour faire passer les bundles Pokémon vs. super-héros par le bon chemin, puis créez une tâche pour chaque personnage.

![Image du scénario Fusion](assets/universal-connectors-and-routing-2.png)

## Présentation des routeurs

Workfront recommande de regarder la vidéo de présentation de l’exercice avant d’essayer de recréer l’exercice dans votre propre environnement.

>[!VIDEO](https://video.tv.adobe.com/v/335272/?quality=12&learn=on&enablevpops=1)

## URL d’exercice

* Site web de l’API des super-héros : `https://www.superheroapi.com/`
* Première URL pour l’exercice : `https://www.superheroapi.com/api/{access-token}/{character-id}/appearance`
* Deuxième URL pour l’exercice : `https://www.superheroapi.com/api/{access-token}/{character-id}/powerstats`

Si vous avez des difficultés à accéder à votre propre jeton de super-héros, vous pouvez utiliser ce jeton partagé : 10110256647253588. Veuillez faire attention au nombre de fois où vous appelez l’API super-héros afin que ce jeton partagé continue de fonctionner pour tout le monde.



## Rechercher des éléments dans le panneau de mappage

Le champ Rechercher des éléments, situé en haut des panneaux de mappage, vous permet de trouver rapidement des champs dans le panneau, même s’ils sont imbriqués dans des tableaux. La recherche ne respecte pas la casse.

![Image du premier panneau de recherche](assets/universal-connectors-and-routing-3.png)

![Image du deuxième panneau de recherche](assets/universal-connectors-and-routing-4.png)

## Conseils et astuces pour utiliser les API

Jusqu’à présent, vous avez travaillé avec une API (interface de programmation d’applications) très simple qui ne nécessite aucune authentification supplémentaire pour obtenir les informations nécessaires au scénario. Voici quelques conseils pour vous aider à travailler avec les API et les connecteurs universels.

## Étape 1 : déterminer le type d’API

Workfront et de nombreux systèmes logiciels sont conçus à l’aide d’une API REST (Representational State Transfer), le type d’API le plus simple et le plus courant aujourd’hui. Il en existe toutefois quelques autres, comme par exemple :

* SOAP (Simple Object Access Protocol) (l’API des épreuves de Workfront est basée sur SOAP)
* FTP (File Transfer Protocol)
* SFTP (Secure File Transfer Protocol)
* Pour en savoir plus, effectuez une recherche web sur les types d’API et les mots-clés qui vous intéressent.

>[!NOTE]
>
>Lorsque vous vous connectez à des plateformes plus importantes telles que Salesforce, les différentes parties de ces plateformes fournissent des API différentes. Assurez-vous de trouver le service auquel vous souhaitez vous connecter.

## Étape 2 : déterminer le type d’authentification requis par l’API

L’authentification d’API est une forme d’identification utilisée pour contrôler l’accès à un service, par exemple lorsque vous essayez de vous connecter via Workfront Fusion. Elle vous permet de prouver à un autre système que vous avez l’autorisation d’y accéder. OAuth 2 est le type d’authentification le plus utilisé aujourd’hui. Pour en savoir plus, effectuez une recherche sur Internet concernant l’authentification d’API.

L’authentification peut être l’aspect le plus difficile de l’utilisation d’une API. L’une des caractéristiques les plus intéressantes des connecteurs universels de Workfront Fusion est que Workfront Fusion peut gérer l’authentification pour vous lorsque vous utilisez des méthodes d’authentification courantes telles que l’authentification de base, comme OAuth 2, la clé d’API, et d’autres. Lorsque vous créez une connexion en utilisant le module Workfront Fusion approprié pour votre méthode d’authentification (par exemple, OAuth 2), Workfront Fusion génère continuellement des clés d’API et/ou des jetons chaque fois que vous voulez exécuter votre scénario.

Pour en savoir plus sur les différents types d’authentification proposés par Workfront, consultez l’article sur l’authentification améliorée sur Experience League.

## Étape 3 : lire la documentation de l’API et trouver les points d’entrée nécessaires

Lorsqu’une API interagit avec un autre système, les touchpoints de cette communication sont considérés comme des points d’entrée. Un point d’entrée est l’endroit où les API envoient des requêtes et où la ressource est hébergée.

Lorsque vous interagissez avec une API à l’aide d’un connecteur universel, vous devez comprendre quels sont les points d’entrée pris en charge par l’API et quelles sont les données requises pour chaque requête. La documentation de l’API doit décrire les points d’entrée de l’API et la manière d’effectuer des opérations courantes telles que la création, la lecture, la mise à jour ou la suppression. L’exécution de ces appels nécessite un peu d’entraînement, surtout si vous n’avez pas l’habitude de faire des appels d’API ou de travailler avec une nouvelle API.

Découvrez les connecteurs universels de Workfront Fusion en détail et apprenez à les configurer pour vous connecter aux API dont vous avez besoin sur Experience League.

## Note finale

Vous pouvez consulter la liste complète de nos connecteurs d’applications préconfigurés dans Experience League. Si vous souhaitez suggérer un nouveau connecteur d’application à l’équipe produit de Workfront Fusion, soumettez votre idée à Innovation Lab. Si vous n’avez jamais soumis d’idées, découvrez Innovation Lab plus en détail et apprenez à voter pour des idées et à participer à l’établissement des priorités du classement qui a lieu deux fois par an. Si vous avez déjà accès à Innovation Lab, connectez-vous et soumettez vos idées.

## À vous

>[!NOTE]
>
>Les exercices pratiques et les défis sont facultatifs et ne sont pas nécessaires pour terminer la formation Fusion.

Cet exercice repose sur ce que vous avez appris dans la présentation, mais la solution n’est pas fournie.

Dans le module Définir plusieurs variables pour les personnages Pokemon, créez une variable appelée « Stat (Niveau) ». Mappez le nom des statistiques de Pokemon dans cette variable. Utilisez la capacité de valeur de tableau pour modifier l’affichage du tableau, de sorte que chaque statistique soit une nouvelle ligne, comme illustré ci-dessous.

**Indice :** il n’y a que six statistiques différentes de Pokemon avec un niveau correspondant.

![Image de statistiques](assets/universal-connectors-and-routing-5.png)

**Défi :** essayez d’utiliser les formules de tableau pour que les capacités s’affichent de la même manière que ci-dessus, sous la forme de lignes différentes plutôt que d’une chaîne de valeurs séparées par une virgule. Vous trouverez un indice dans la copie d’écran ci-dessous.

![Une image d’un nom de tableau](assets/universal-connectors-and-routing-6.png)

## Vous voulez en savoir plus ? Nous recommandons ce qui suit :

[Documentation sur Workfront Fusion](https://experienceleague.adobe.com/fr/docs/workfront-fusion/using/get-started-with-fusion/understand-workfront-fusion/workfront-fusion-overview)
