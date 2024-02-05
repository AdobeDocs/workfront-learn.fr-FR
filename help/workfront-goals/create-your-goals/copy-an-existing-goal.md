---
title: Copier un objectif existant
description: Découvrez comment copier un objectif existant dans  [!DNL Workfront Goals].
activity: use
team: Technical Marketing
feature: Workfront Goals
type: Tutorial
role: User
level: Beginner
jira: KT-10121
exl-id: bf9ac10a-8419-458b-b4e8-bedb0ad3b98f
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: ht
source-wordcount: '525'
ht-degree: 100%

---

# Copier un objectif existant

Imaginons que nous soyons à la fin d’un trimestre et que vous souhaitiez recréer un objectif existant pour la période suivante. Il est aussi possible que vous n’ayez pas atteint l’objectif et que vous deviez l’étendre à la période suivante. Quelle est la meilleure option pour créer cet objectif ? Vous allez copier et modifier un objectif existant.

La copie d’un objectif existant est également utile si plusieurs membres de l’équipe ont des objectifs similaires et que vous devez créer un objectif pour chacun d’eux.

<!--
Pro-tips graphic
-->

Voici quelques éléments à prendre en compte avant de copier des objectifs :

* Toutes les informations issues de l’objectif original seront copiées, à l’exception de la période (puisqu’elle se situe dans le passé).
* Vous pouvez copier les résultats d’un objectif existant et les transférer vers le nouvel objectif.
* Par défaut, les résultats copiés sont affectés au même ou à la même propriétaire.
* Vous ne pouvez pas copier la progression de l’objectif existant vers un nouvel objectif.
* Vous ne pouvez pas copier les activités d’un objectif lorsque vous copiez un objectif.

## Copie d’un objectif

1. Cliquez sur le nom d’un objectif pour ouvrir le panneau **[!UICONTROL Détails de l’objectif]**.
1. Cliquez sur l’icône à trois points, puis sélectionnez **[!UICONTROL Copier]**.
1. Mettez à jour l’une des informations suivantes pour l’objectif copié :
   * **Nouvel objectif** : le nom du nouvel objectif. La valeur par défaut est le nom de l’objectif d’origine.
   * **Période** : période pendant laquelle vous souhaitez atteindre l’objectif. Sélectionnez une période dans le menu déroulant ou cliquez sur Définir des dates personnalisées pour indiquer une période personnalisée. La période par défaut est toujours le trimestre en cours.
   * **Propriétaire** : le ou la propriétaire de l’objectif. Il peut s’agir d’un utilisateur ou d’une utilisatrice, d’une équipe, d’un groupe ou d’une entreprise. Le ou la propriétaire de l’objectif initial est désigné par défaut.
   * **Description** : informations complémentaires sur l’objectif.

1. Cochez la case **[!UICONTROL Copier les résultats]** si des résultats ont été ajoutés à l’objectif initial et que vous souhaitez les copier dans le nouvel objectif. Les résultats de l’objectif copié ont les mêmes propriétaire, noms et valeurs mesurées que les résultats de l’objectif initial.

1. Cliquer sur **[!UICONTROL Enregistrer]**. L’objectif copié est sauvegardé avec un statut de Brouillon.

   ![Une image du panneau [!UICONTROL Détails de l’objectif] dans [!DNL Workfront Goals] avec l’option [!UICONTROL Copier]](assets/03-workfront-goals-copy-a-goal.png)

1. Cliquez sur **[!UICONTROL Activer]**, ce qui met à jour le statut de l’objectif en le rendant actif. L’objectif doit être associé à une activité ou à un résultat pour être « activé ».

1. Cliquez sur le bouton **X** en haut à droite du panneau [!UICONTROL Détails de l’objectif] pour le fermer.

Si vous avez copié un objectif qui n’a pas été atteint au cours d’une période précédente et que vous souhaitez continuer à y travailler au cours de la période suivante, procédez comme suit :

1. Allez à l’objectif initial dans la section **[!UICONTROL Liste d’objectifs]**, **[!UICONTROL Vérification]**, ou **[!UICONTROL Impression]**.
1. Commentez l’objectif pour indiquer qu’il a été copié et qu’un objectif plus actuel a été créé.
1. Fermez l’objectif initial afin de préserver la progression réalisée au cours de la période initiale. Cliquez sur l’icône à trois points dans le panneau **[!UICONTROL Détails de l’objectif]** et sélectionnez **[!UICONTROL Fermer]** dans le menu.
1. Mettez à jour la valeur [!UICONTROL Initiale] du nouveau résultat pour qu’elle corresponde à la valeur **[!UICONTROL Cible]** du résultat précédent, de sorte que la progression de votre nouvel objectif commence à être calculée à partir du point atteint au cours de la période précédente.
