---
title: Comprendre les taux de facturation multiples
description: Découvrez comment remplacer les taux de facturation système dans un projet.
activity: use
team: Technical Marketing
feature: Work Management
thumbnail: understand-multiple-billing-rates.png
type: Tutorial
role: User
level: Intermediate
jira: KT-10048
exl-id: bda562b9-f8da-49c9-bea7-0440fdc4c24c
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '438'
ht-degree: 100%

---

# Comprendre les taux de facturation multiples

Dans [!DNL Workfront], un ou une chef de projet a la possibilité de modifier les taux de facturation du système dans le cadre d’un projet spécifique. Auparavant, lorsque le nouveau taux de facturation était appliqué au projet, il affectait non seulement les heures futures, mais également les heures déjà enregistrées du projet.

Grâce à la nouvelle fonctionnalité de taux de facturation multiple de [!DNL Workfront], le ou la chef de projet peut décider de la période pendant laquelle un taux de facturation doit être appliqué. Ainsi, si un taux a été négocié ou modifié, le ou la chef de projet peut déterminer quand ce taux doit prendre effet.

## Modifier le taux de facturation

1. Accédez à la page de destination du projet. Sélectionnez **[!UICONTROL Taux de facturation]** dans le panneau de gauche.

   ![Image de sélection du [!UICONTROL Taux de facturation] dans [!DNL Workfront]](assets/project-finances-1.png)

1. Dans l’onglet **[!UICONTROL Taux de facturation]**, cliquez sur le bouton **[!UICONTROL Ajouter un taux de facturation]**. Sélectionnez **[!UICONTROL Nouveau taux de facturation]** dans la liste déroulante.

   ![Image de sélection du [!UICONTROL Nouveau taux de facturation] dans [!DNL Workfront]](assets/project-finances-2.png).

1. La boîte de dialogue [!UICONTROL Nouveau taux de facturation] apparaît. Dans la liste déroulante **[!UICONTROL Fonction]**, sélectionnez la fonction pour laquelle le nouveau taux de facturation sera appliqué.

   ![Image de sélection des fonctions avec un nouveau taux de facturation dans [!DNL Workfront]](assets/project-finances-3.png)

1. Une fois la fonction sélectionnée, le champ [!UICONTROL Taux de facturation par défaut] et [!UICONTROL Taux de facturation 1] apparaît. Saisissez le nouveau taux de facturation dans le champ [!UICONTROL Taux de facturation 1]. Si ce taux de facturation s’applique à l’ensemble du projet (heures passées, présentes et futures enregistrées), cliquez sur le bouton **[!UICONTROL Enregistrer]**.

   ![Image d’enregistrement d’un nouveau taux de facturation applicable à l’ensemble du projet dans [!DNL Workfront]](assets/project-finances-5.png)

1. Si le nouveau taux de facturation ne s’applique que pendant une certaine période, cliquez sur le bouton **[!UICONTROL Ajouter taux]**. Les champs [!UICONTROL Date de fin du taux de facturation 1] et [!UICONTROL Taux de facturation 2] apparaissent. Saisissez la date de fin pour le [!UICONTROL Taux de facturation 1]. Vous ne pouvez pas saisir de date de début pour le [!UICONTROL Taux de facturation 1], car le système suppose qu’il a démarré au début du projet.

   ![Image de création d’un nouveau taux de facturation s’appliquant à une certaine période, à partir du début du projet dans [!DNL Workfront]](assets/project-finances-6.png).

1. Si ce n’est pas le cas :

   * Saisissez le taux de facturation par défaut pour le [!UICONTROL Taux de facturation 1].
   * Sélectionnez la Date de fin pour le [!UICONTROL Taux de facturation 1] ([!UICONTROL Taux de facturation par défaut]).
   * La date de début pour le [!UICONTROL Taux de facturation 2] est automatiquement définie sur le jour suivant la fin du [!UICONTROL Taux de facturation 1].
   * Saisissez le taux de facturation souhaité dans la section [!UICONTROL Taux de facturation 2].
   * Continuez à ajouter des taux de facturation si nécessaire, en cliquant sur le bouton **[!UICONTROL Ajouter taux]**.
   * Lorsque vous avez terminé, cliquez sur **[!UICONTROL Enregistrer]**.
   * Tous les taux de facturation s’affichent dans l’onglet [!UICONTROL Taux de facturation] du projet.

   ![Image de création de nouveaux taux de facturation qui s’appliquent aux différentes périodes dans [!DNL Workfront]](assets/project-finances-7.png).
