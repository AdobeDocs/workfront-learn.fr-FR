---
title: Accessibilité et clarté
description: Découvrez quelques bonnes pratiques de base pour faciliter la lecture, le partage et la compréhension des scénarios.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11037
recommendations: noDisplay,catalog
exl-id: ba2c5c64-ab4d-42d3-8a69-6b9df1373b29
source-git-commit: dfcca5f02a6d9f7ee44a1e894106ae48259eea91
workflow-type: tm+mt
source-wordcount: '697'
ht-degree: 99%

---

# Accessibilité et clarté

Au début de la formation Workfront Fusion, vous avez appris quelques bonnes pratiques de base pour rendre les scénarios faciles à lire, à partager et à comprendre. Ces pratiques facilitent la tâche des futures utilisatrices et futurs utilisateurs de Workfront Fusion ou de toute personne chargée du dépannage ou de l’assistance de votre instance de Workfront Fusion. Affûtez vos connaissances en suivant les instructions ci-dessous lors de la conception de scénarios.

## Libellés et notes

En règle générale, l’objectif principal de Workfront Fusion est toujours d’avoir des scénarios simples. Voici quelques façons de créer des conceptions simples à interpréter.

* Veillez à nommer tous les modules. Cliquez avec le bouton droit de la souris sur un module et sélectionnez Renommer. Les libellés des modules doivent être courts, mais indiquer clairement l’objectif du module. Par exemple, « Créer un profil Mktg avec modèle Ch ».
  ![Une image d’un scénario avec gestion des erreurs](assets/design-optimization-and-testing-1.png)
* Ajoutez également un libellé aux chemins de routage. Même si un chemin n’utilise pas de filtre directement après un routeur, vous pouvez appliquer un libellé sans remplir la logique du filtre. Ainsi, les tiers peuvent comprendre quels lots passent par quels chemins et pourquoi. Pour créer un libellé pour un chemin de routeur sans filtre, cliquez avec le bouton droit sur le chemin, ajoutez un libellé et enregistrez.
  ![Une image d’un scénario avec gestion des erreurs](assets/design-optimization-and-testing-2.png)
* Le cas échéant, vous pouvez ajouter des notes dans un scénario, dans le cas où un libellé de module ou de chemin de routage est trop court pour apporter une description claire. Vous pouvez ajouter des notes lorsque vous le souhaitez tout au long du processus de conception et d’itération.

Cependant, la lecture et la compréhensions seront facilitées si vous ajoutez des notes à la toute fin de la conception du scénario, lorsque ce dernier est prêt à être lancé. Partez de la fin de votre scénario (le coin inférieur droit) pour retourner vers l’arrière. Ainsi, les notes qui s’appliquent au début de votre scénario se trouvent en haut de la liste lorsque vous ouvrez le panneau Notes.

Lorsque vous enregistrez ou fermez le panneau Notes, les notes se classent avec les plus récentes en haut de la page. Dans l’image ci-dessous, la première note créée apparaît en bas de la liste. Les notes ont été intentionnellement créées à partir de la partie inférieure droite vers le chemin supérieur et enfin vers le déclencheur - essentiellement dans l’ordre inverse de celui dans lequel un lot de données traverserait le scénario. Cela fait apparaître les notes dans l’ordre dans lequel le scénario s’exécute réellement sur le lot de données.

![Une image d’un scénario avec gestion des erreurs](assets/design-optimization-and-testing-3.png)

## Modèles Workfront Fusion

L’utilisation des modèles est un excellent moyen de rationaliser l’étiquetage des modules et des chemins de routage. Les modèles de bonnes pratiques peuvent accélérer la création de scénarios pour les cas d’utilisation courants.

### Exemple de modèle

Lorsque vous commencez un scénario, vérifiez d’abord s’il existe un modèle qui pourrait vous aider. Par exemple, vous souhaitez créer un scénario qui commence par télécharger un document CSV à partir de Workfront, puis l’analyse.

Cliquez sur la section Modèles pour voir si d’éventuels modèles publics répondent à vos besoins.

![Une image d’un scénario avec gestion des erreurs](assets/design-optimization-and-testing-4.png)

Cliquez sur l’onglet Modèles d’équipe pour voir si un membre de votre équipe a créé un modèle qui peut se révéler utile.

Si vous trouvez un modèle à utiliser, cliquez sur son nom pour l’ouvrir.

![Une image d’un scénario avec gestion des erreurs](assets/design-optimization-and-testing-5.png)

Ensuite, accédez au coin supérieur droit, cliquez sur Options, puis sélectionnez Créer un scénario.

![Une image d’un scénario avec gestion des erreurs](assets/design-optimization-and-testing-6.png)

### Créer un modèle

Vous pouvez créer un modèle dans la section Modèles d’équipe. Le modèle que vous créez est disponible pour vous et votre équipe, mais lorsque vous cliquez sur le bouton Publier, vous pouvez le partager avec des personnes extérieures à votre équipe.

![Une image d’un scénario avec gestion des erreurs](assets/design-optimization-and-testing-7.png)

Lors de la création du modèle, vous pouvez inclure un assistant qui guidera les personnes dans la création des scénarios, la modification des connexions, les données mappées et d’autres champs de panneau, le cas échéant.

Cochez la case « Utiliser dans l’assistant » pour ajouter des instructions qui seront disponibles lorsqu’une personne construira un scénario à l’aide de votre modèle. Cette information apparaîtra dans le champ Aide. Pour permettre aux utilisateurs et utilisatrices de voir ce texte lorsqu’ils utilisent le modèle, activez l’option Utiliser comme valeur par défaut.

![Une image d’un scénario avec gestion des erreurs](assets/design-optimization-and-testing-8.png)

## Vous voulez en savoir plus ? Nous recommandons ce qui suit :

[Documentation sur Workfront Fusion](https://experienceleague.adobe.com/en/docs/workfront-fusion/using/get-started-with-fusion/understand-workfront-fusion/workfront-fusion-overview)
