---
title: Copier un objectif existant
description: Découvrez comment copier un objectif existant dans [!DNL Workfront Goals].
feature: Workfront Goals
type: Tutorial
role: User
level: Beginner
kt: 10121
exl-id: bf9ac10a-8419-458b-b4e8-bedb0ad3b98f
source-git-commit: 27e8f0aada77488bd6cfc2e786b997f759fd0a17
workflow-type: tm+mt
source-wordcount: '525'
ht-degree: 0%

---

# Copier un objectif existant

Disons que c&#39;est la fin d&#39;un trimestre et que vous voulez recréer un objectif existant pour la prochaine période. Ou peut-être que vous n&#39;avez pas atteint l&#39;objectif et que vous avez besoin de prolonger la période suivante. Quelle est la meilleure option pour créer cet objectif ? Vous souhaitez copier et modifier un objectif existant.

La copie d’un objectif existant s’avère également utile si plusieurs membres de l’équipe ont des objectifs similaires et que vous devez créer un objectif pour chacun d’eux.

<!--
Pro-tips graphic
-->

Voici quelques éléments à prendre en compte avant de copier des objectifs :

* Toutes les informations de l’objectif d’origine seront copiées, à l’exception de la période d’objectif (car elle se situe dans le passé).
* Vous pouvez copier les résultats d’un objectif existant et les transférer vers le nouvel objectif.
* Par défaut, les résultats copiés sont attribués au même propriétaire.
* Vous ne pouvez pas copier la progression de l’objectif existant vers un nouvel objectif.
* Vous ne pouvez pas copier les activités d’un objectif lorsque vous copiez un objectif.

## Comment copier un objectif

1. Cliquez sur un nom d’objectif pour ouvrir la **[!UICONTROL Détails de l’objectif]** du panneau.
1. Cliquez sur l’icône à 3 points, puis sélectionnez **[!UICONTROL Copier]**.
1. Mettez à jour l’une des informations suivantes pour l’objectif copié :
   * **Nouvel objectif**— C’est le nom du nouveau but. La valeur par défaut est le nom de l’objectif d’origine.
   * **Période**: période pendant laquelle vous souhaitez atteindre l’objectif. Sélectionnez une période dans le menu déroulant ou cliquez sur Définir des dates personnalisées pour indiquer une période personnalisée. La période par défaut est toujours le trimestre en cours.
   * **Propriétaire**: propriétaire de l’objectif. Il peut s’agir d’un utilisateur, d’une équipe, d’un groupe ou d’une société. La valeur par défaut est le propriétaire de l’objectif d’origine.
   * **Description**: informations supplémentaires sur l’objectif.

1. Vérifiez les **[!UICONTROL Copie de résultats]** si des résultats ont été ajoutés à l’objectif d’origine et que vous souhaitez les copier dans le nouvel objectif. Les résultats de l’objectif copié ont les mêmes propriétaire, noms et valeurs mesurées que les résultats de l’objectif d’origine.

1. Cliquez sur **[!UICONTROL Enregistrer]**. L’objectif copié est enregistré avec l’état Brouillon.

   ![Une image de la fonction [!UICONTROL Détails de l’objectif] dans [!DNL Workfront Goals] avec le [!UICONTROL Copier] option](assets/03-workfront-goals-copy-a-goal.png)

1. Cliquez sur **[!UICONTROL Activer]**, qui met à jour l’état de l’objectif sur Principal. L’objectif doit être associé à une activité ou à un résultat pour être &quot;activé&quot;.

1. Cliquez sur le bouton **X** dans le coin supérieur droit du [!UICONTROL Détails de l’objectif] pour le fermer.

Si vous avez copié un objectif qui n’a pas été terminé au cours d’une période précédente et que vous souhaitez continuer à travailler dessus au cours de la période suivante, procédez comme suit :

1. Accédez à l’objectif d’origine dans la **[!UICONTROL Liste des objectifs]**, **[!UICONTROL Archivage]** ou **[!UICONTROL Pulse]** .
1. Commentaire sur l’objectif pour indiquer qu’il a été copié et qu’un objectif plus récent a été créé.
1. Fermez l&#39;objectif d&#39;origine pour préserver les progrès réalisés pendant sa période d&#39;origine. Cliquez sur l’icône à 3 points dans la **[!UICONTROL Détails de l’objectif]** et sélectionnez **[!UICONTROL Fermer]** dans le menu.
1. Mettez à jour le [!UICONTROL Initial] valeur du nouveau résultat pour correspondre à la variable **[!UICONTROL Cible]** de la valeur du résultat précédent, de sorte que la progression de votre nouvel objectif commence à calculer à partir du point atteint au cours de la période précédente.
