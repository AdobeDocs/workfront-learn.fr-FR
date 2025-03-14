---
title: Créer des tableaux de bord
description: La vidéo vise à aider les utilisateurs à créer, personnaliser et gérer efficacement des tableaux de bord dans Workfront pour surveiller et partager des données liées au projet.
activity: use
feature: Reports and Dashboards
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
thumbnail: 335157.png
jira: KT-8862
exl-id: 7adc2aeb-6618-4894-acc3-298e35175854
doc-type: video
source-git-commit: 06d6b06e2dfcd54a172d220fdb3996a7949348d1
workflow-type: tm+mt
source-wordcount: '645'
ht-degree: 61%

---

# Créer des tableaux de bord

La vidéo aborde les points clés suivants :

* **Présentation des tableaux de bord :** explique ce qu’est un tableau de bord dans Workfront et son objectif en tant que collection de rapports associés. &#x200B;
* **Création d’un tableau de bord :** explique comment créer un tableau de bord en accédant à la zone Tableaux de bord, en sélectionnant « Nouveau tableau de bord », en lui attribuant un nom et en choisissant une disposition. &#x200B;
* **Ajout de rapports :** montre comment ajouter différents rapports au tableau de bord, tels que des rapports de projet, des rapports de tâche et des rapports de problème, et les organiser selon la disposition choisie. &#x200B;
* **Personnalisation des vues :** indique comment personnaliser les colonnes affichées dans la vue Tableau de bord en modifiant le rapport et en sélectionnant des colonnes spécifiques à afficher. &#x200B;
* **Ajout d’éléments supplémentaires :** explique comment ajouter un calendrier personnalisé et une page externe (par exemple, un document en ligne) au tableau de bord. &#x200B;
* **Enregistrement et épinglage :** indique d’enregistrer le tableau de bord et de l’épingler pour un accès facile. &#x200B;
* **Affichage et modification :** fournit des conseils sur l’affichage et la modification du tableau de bord, y compris le réglage de la visibilité des colonnes pour un meilleur affichage. &#x200B;
* **Recherche et partage de tableaux de bord :** décrit comment trouver des tableaux de bord via le menu principal, les ajouter aux favoris et les partager avec d’autres utilisateurs. &#x200B;
* **Impression des tableaux de bord :** décrit le processus d’impression d’un tableau de bord. &#x200B;


>[!VIDEO](https://video.tv.adobe.com/v/335157/?quality=12&learn=on)


## Activités « Créer un tableau de bord »

### Activité 1 : créer un tableau de bord

Créez un [!UICONTROL tableau de bord] qui ne contient qu’un seul rapport : « Rechercher des notes dans ce projet ». Cela est utile pour trouver rapidement toute mise à jour effectuée sur un projet, même s&#39;il y a des milliers de mises à jour à rechercher. Cela permet d’effectuer des recherches dans les threads de mise à jour afin d’extraire rapidement les mises à jour répondant aux critères spécifiés dans les invites.

Créez ce rapport en effectuant une copie du rapport « Rechercher des notes » que vous avez créé dans l’activité « Créer un rapport de note » (ou utilisez un autre rapport si vous n’avez pas effectué cette activité).

* Supprimez le prompt Nom du projet de la copie et renommez le rapport « Rechercher des notes dans ce projet ».
* Attribuez au [!UICONTROL Tableau de bord] le nom « Rechercher des notes ».
* Accédez à une page de destination de projet et créez une section personnalisée pour un [!UICONTROL tableau de bord].
* Notez que lorsque vous recherchez des notes dans votre section personnalisée, seules s’affichent les notes contenues dans le projet dans lequel vous vous trouvez actuellement.

### Réponse 1

1. Exécutez le rapport que vous avez créé dans l&#39;activité « Créer un rapport de note ». Vous ne l&#39;avez pas encore créé ? Cliquez ici pour voir l’activité dans le tutoriel [Créer un rapport de tâche](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/create-a-task-report#activity-1-create-a-note-report-with-prompts).
1. Cliquez sur **[!UICONTROL Actions de rapport]** et sélectionnez **[!UICONTROL Copier]**. [!DNL Workfront] crée un rapport nommé « Recherche de notes (Copie) ».
1. Accédez à **[!UICONTROL Actions de rapport]** et sélectionnez **[!UICONTROL Modifier]**. Cliquez sur **[!UICONTROL Paramètres du rapport]** et remplacez le nom par « Rechercher des notes dans ce projet ».
1. Cliquez sur [!UICONTROL Invites de rapport] et supprimez l’invite [!UICONTROL Projet] > [!UICONTROL Nom] de la liste.

   ![Image de l’écran permettant de créer un tableau de bord](assets/edit-report-prompts.png)

1. Cochez la case **[!UICONTROL Afficher les invites dans le tableau de bord]**.
1. Cliquez sur **[!UICONTROL Terminé]**, puis sur **[!UICONTROL Enregistrer + Fermer]**. Vous voyez maintenant l’écran [!UICONTROL Invites] du rapport.

   Vous allez ensuite utiliser un raccourci pour créer un tableau de bord et y ajouter ce rapport.

1. Cliquez sur **[!UICONTROL Actions de rapport]** et sélectionnez **[!UICONTROL Ajouter au tableau de bord]** > **[!UICONTROL Nouveau tableau de bord]**.
1. Faites glisser le rapport « Rechercher des notes dans ce projet » vers le panneau **[!UICONTROL Disposition]**.
1. Remarquez que le nom du rapport devient le nom du tableau de bord. Modifiez le nom en « Rechercher des notes ».

   ![Image de l’écran permettant de créer un tableau de bord](assets/create-dashboard.png)

1. Cliquez sur **[!UICONTROL Enregistrer + Fermer]**.

   Ajoutez maintenant le tableau de bord à une page de projet.

   ![Image de l’écran permettant de créer un tableau de bord](assets/add-custom-section.png)

1. Accédez à n’importe quel projet. Dans le menu du panneau de gauche, cliquez sur l’icône **[!UICONTROL Ajouter une section personnalisée]**.
1. Dans le champ **[!UICONTROL Ajouter un tableau de bord]**, saisissez « Rechercher des notes » et sélectionnez le [!UICONTROL tableau de bord] dans la liste.
1. Dans le champ **[!UICONTROL Titre de la section personnalisée]**, saisissez « Rechercher des notes ».
1. Cliquez sur **[!UICONTROL Ajouter une nouvelle section]**.
1. Dans le menu du panneau de gauche, recherchez Rechercher des notes. Cliquez sur les points à gauche du nom de la section et faites-le glisser sous Mises à jour.
