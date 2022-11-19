---
title: Comprendre plusieurs taux de facturation
description: Découvrez comment remplacer les taux de facturation système dans un projet.
activity: use
team: Technical Marketing
feature: Work Management
thumbnail: understand-multiple-billing-rates.png
type: Tutorial
role: User
level: Intermediate
kt: 10048
exl-id: bda562b9-f8da-49c9-bea7-0440fdc4c24c
source-git-commit: 58a545120b29a5f492344b89b77235e548e94241
workflow-type: tm+mt
source-wordcount: '427'
ht-degree: 0%

---

# Comprendre plusieurs taux de facturation

Within [!DNL Workfront], un chef de projet peut remplacer les taux de facturation système au sein d’un projet spécifique. Auparavant, lorsque le nouveau taux de facturation était appliqué au projet, il affectait non seulement les heures futures, mais également les heures déjà connectées au projet.

Avec [!DNL Workfront]Grâce à sa nouvelle fonctionnalité de taux de facturation multiple, le chef de projet peut décider de la période pendant laquelle un taux de facturation doit être appliqué. Ainsi, si un taux a été négocié ou modifié, le chef de projet peut déterminer quand ce taux doit prendre effet.

## Modifier le taux de facturation

1. Accédez à la landing page du projet. Sélectionner **[!UICONTROL Taux de facturation]** dans le panneau de gauche.

   ![Image de sélection [!UICONTROL Taux de facturation] in [!DNL Workfront]](assets/project-finances-1.png)

1. Dans la **[!UICONTROL Taux de facturation]** , cliquez sur l’onglet **[!UICONTROL Ajouter le taux de facturation]** bouton . Sélectionner **[!UICONTROL Nouveau taux de facturation]** dans la liste déroulante.

   ![Image de sélection [!UICONTROL Nouveau taux de facturation] in [!DNL Workfront]](assets/project-finances-2.png)

1. Le [!UICONTROL Nouveau taux de facturation] s’affiche. Dans la **[!UICONTROL Rôle de tâche]** dans la liste déroulante, sélectionnez le rôle de tâche auquel le nouveau taux de facturation sera appliqué.

   ![Image de sélection des rôles de tâche dans un nouveau taux de facturation dans [!DNL Workfront]](assets/project-finances-3.png)

1. Une fois le rôle de tâche sélectionné, la fonction [!UICONTROL Taux de facturation par défaut] et le [!UICONTROL Taux de facturation 1] s’affiche. Saisissez le nouveau taux de facturation dans la variable [!UICONTROL Taux de facturation 1] champ . Si ce taux de facturation s’applique à l’ensemble du projet (heures passées, présentes et futures consignées), cliquez sur le bouton **[!UICONTROL Enregistrer]** bouton .

   ![Image d’enregistrement d’un nouveau taux de facturation applicable à l’ensemble du projet dans [!DNL Workfront]](assets/project-finances-5.png)

1. Si le nouveau taux de facturation ne s&#39;applique que pour une certaine période, cliquez sur le bouton **[!UICONTROL Taux d’ajout]** bouton . Le [!UICONTROL Taux de facturation 1 Date de fin] et le [!UICONTROL Taux de facturation 2] s’affichent. Saisissez la date de fin pour [!UICONTROL Taux de facturation 1]. Vous ne pouvez pas saisir de date de début pour [!UICONTROL Taux de facturation 1] car le système suppose qu’il a commencé au début du projet.

   ![Image de création d’un nouveau taux de facturation s’appliquant à une certaine période, à partir du début du projet dans [!DNL Workfront]](assets/project-finances-6.png)

1. Si ce n’est pas le cas :

   * Saisissez le taux de facturation par défaut pour [!UICONTROL Taux de facturation 1].
   * Sélectionnez la Date de fin pour [!UICONTROL Taux de facturation 1] ([!UICONTROL Taux de facturation par défaut]).
   * Date de début pour [!UICONTROL Taux de facturation 2] est automatiquement défini sur le jour suivant [!UICONTROL Taux de facturation 1] se termine.
   * Saisissez le taux de facturation souhaité dans la variable [!UICONTROL Taux de facturation 2] .
   * Continuez à ajouter des taux de facturation, si nécessaire, en cliquant sur le bouton **[!UICONTROL Taux d’ajout]** bouton .
   * Lorsque vous avez terminé, cliquez sur **[!UICONTROL Enregistrer]**.
   * Tous les taux de facturation s’affichent dans la variable [!UICONTROL Taux de facturation] sur le projet.
   ![Image de création de nouveaux taux de facturation qui s’appliquent aux différentes périodes dans [!DNL Workfront]](assets/project-finances-7.png)
