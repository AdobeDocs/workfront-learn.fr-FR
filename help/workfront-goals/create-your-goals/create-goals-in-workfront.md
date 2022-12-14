---
title: Création d’objectifs dans [!DNL Workfront Goals]
description: Découvrez comment créer des objectifs dans [!DNL Workfront Goals] en utilisant trois options différentes.
activity: use
feature: Workfront Goals
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
kt: 10122
exl-id: 784b353f-cc6b-4a4b-9935-9e5d25c532b4
source-git-commit: 58a545120b29a5f492344b89b77235e548e94241
workflow-type: tm+mt
source-wordcount: '921'
ht-degree: 0%

---

# Création d’objectifs dans [!DNL Workfront Goals]

Dans [!DNL Workfront Goals], les cadres et les équipes de direction d’entreprise peuvent voir les progrès de l’ensemble de l’organisation à chaque niveau, jusqu’à l’individu. [!DNL Workfront Goals] offre la visibilité nécessaire pour obtenir des informations exploitables clés afin de faire avancer les priorités les plus élevées, d’identifier les objectifs à risque, de diagnostiquer les problèmes en temps réel et de corriger de manière proactive les cours.

[!DNL Workfront Goals] permet également aux contributeurs individuels de voir comment leur travail contribue à l’image globale. Le travail est plus significatif quand les individus peuvent voir où leur travail compte.

Il existe 3 façons de créer des objectifs avec [!DNL Workfront]:

## Créer un objectif à partir de zéro

Voici quelques éléments à prendre en compte lors de la création d’objectifs à partir de zéro :

* Vous ne pouvez pas créer d’objectifs avec des dates de fin dans le passé.
* Tous les membres de l’organisation doivent sélectionner les mêmes délais lors de la création d’objectifs ou d’objectifs similaires alignés.
* Les dates personnalisées sont limitées par la date initiale que vous avez sélectionnée. Cela signifie que si vous sélectionnez &quot;trimestre&quot; puis une date personnalisée, la date personnalisée ne peut pas dépasser le trimestre.
* L’état du nouvel objectif est toujours En création jusqu’à ce que vous l’activiez en ajoutant une activité ou un résultat.

Dans cette vidéo, vous apprendrez à :

* Accédez au [!UICONTROL Liste des objectifs] pour ajouter un nouvel objectif

>[!VIDEO](https://video.tv.adobe.com/v/335191/?quality=12)

## Copier un objectif existant

Disons que c&#39;est la fin d&#39;un trimestre et que vous voulez recréer un objectif existant pour la prochaine période. Ou peut-être que vous n&#39;avez pas atteint l&#39;objectif et que vous avez besoin de prolonger la période suivante. Quelle est la meilleure option pour créer cet objectif ? Vous souhaitez copier et modifier un objectif existant.

La copie d’un objectif existant s’avère également utile si plusieurs membres de l’équipe ont des objectifs similaires et que vous devez créer un objectif pour chacun d’eux.

Voici quelques éléments à prendre en compte avant de copier des objectifs :

* Toutes les informations de l’objectif d’origine seront copiées, à l’exception de la période d’objectif (car elle se situe dans le passé).
* Vous pouvez copier les résultats d’un objectif existant et les transférer vers le nouvel objectif.
* Par défaut, les résultats copiés sont attribués au même propriétaire.
* Vous ne pouvez pas copier la progression de l’objectif existant vers un nouvel objectif.
* Vous ne pouvez pas copier les activités d’un objectif lorsque vous copiez un objectif.

### Comment copier un objectif

1. Cliquez sur un nom d’objectif pour ouvrir la **[!UICONTROL Détails de l’objectif]** du panneau.
1. Cliquez sur l’icône à 3 points, puis sélectionnez **[!UICONTROL Copier]**.
1. Mettez à jour l’une des informations suivantes pour l’objectif copié :
   * **Nouvel objectif**— C’est le nom du nouveau but. La valeur par défaut est le nom de l’objectif d’origine.
   * **Période**: période pendant laquelle vous souhaitez atteindre l’objectif. Sélectionnez une période dans le menu déroulant ou cliquez sur Définir des dates personnalisées pour indiquer une période personnalisée. La période par défaut est toujours le trimestre en cours.
   * **Propriétaire**: propriétaire de l’objectif. Il peut s’agir d’un utilisateur, d’une équipe, d’un groupe ou d’une société. La valeur par défaut est le propriétaire de l’objectif d’origine.
   * **Description**: informations supplémentaires sur l’objectif.

1. Vérifiez les **[!UICONTROL Copie de résultats]** si des résultats ont été ajoutés à l’objectif d’origine et que vous souhaitez les copier dans le nouvel objectif. Les résultats de l’objectif copié ont les mêmes propriétaire, noms et valeurs mesurées que les résultats de l’objectif d’origine.

1. Cliquer sur **[!UICONTROL Enregistrer]**. L’objectif copié est enregistré avec l’état Brouillon.

   ![Une image de la fonction [!UICONTROL Détails de l’objectif] dans [!DNL Workfront Goals] avec le [!UICONTROL Copier] option](assets/03-workfront-goals-copy-a-goal.png)

1. Cliquez sur **[!UICONTROL Activer]**, qui met à jour l’état de l’objectif sur Principal. L’objectif doit être associé à une activité ou à un résultat pour être &quot;activé&quot;.

1. Cliquez sur le bouton **X** dans le coin supérieur droit du [!UICONTROL Détails de l’objectif] pour le fermer.

Si vous avez copié un objectif qui n’a pas été terminé au cours d’une période précédente et que vous souhaitez continuer à travailler dessus au cours de la période suivante, procédez comme suit :

1. Accédez à l’objectif d’origine dans la **[!UICONTROL Liste des objectifs]**, **[!UICONTROL Archivage]** ou **[!UICONTROL Pulse]** .
1. Commentaire sur l’objectif pour indiquer qu’il a été copié et qu’un objectif plus récent a été créé.
1. Fermez l&#39;objectif d&#39;origine pour préserver les progrès réalisés pendant sa période d&#39;origine. Cliquez sur l’icône à 3 points dans la **[!UICONTROL Détails de l’objectif]** et sélectionnez **[!UICONTROL Fermer]** dans le menu.
1. Mettez à jour le [!UICONTROL Initial] valeur du nouveau résultat pour correspondre à la variable **[!UICONTROL Cible]** de la valeur du résultat précédent, de sorte que la progression de votre nouvel objectif commence à calculer à partir du point atteint au cours de la période précédente.

## Convertir un résultat ou une activité en objectif

La dernière option permettant de créer des objectifs dans [!DNL Workfront Goals] consiste à convertir les résultats et/ou les activités d’un objectif existant en un autre objectif. Le résultat/l’activité converti devient un objectif enfant par rapport à l’objectif d’origine.

Vous pouvez le faire lorsqu’un résultat/une activité a une portée plus grande que prévu et qu’il serait bénéfique de convertir le résultat/l’activité en un objectif réel lui-même. Considérez cela comme une approche de bas en haut de l’alignement des objectifs.

Voici quelques éléments à garder à l’esprit avant de convertir un résultat ou une activité en objectif :

* Le résultat ou l’activité converti peut devenir l’objectif enfant de l’objectif d’origine. Les deux objectifs s&#39;alignent.
* Le résultat ou l’activité converti peut être supprimé de l’objectif d’origine et ajouté en conséquence ou activité à l’objectif nouvellement créé.
* L’objectif nouvellement créé devient l’indicateur de progression unique de l’objectif d’origine, s’il n’y a aucun résultat ou activité supplémentaire sur l’objectif d’origine.

Dans cette vidéo, vous apprendrez à :

* Convertir une activité en objectif aligné

>[!VIDEO](https://video.tv.adobe.com/v/335192/?quality=12)

Maintenant que vous avez exploré les trois façons de créer des objectifs dans [!DNL Workfront Goals], travaillons à activer ces objectifs.
