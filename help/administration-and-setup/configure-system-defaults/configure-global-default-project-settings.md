---
title: Configuration des paramètres par défaut globaux du projet
description: Découvrez comment modifier un état personnalisé, définir les préférences globales du projet et créer des plannings qui sont des paramètres par défaut globaux.
feature: System Setup and Administration
role: Admin
level: Intermediate
activity: deploy
type: Tutorial
team: Technical Marketing
thumbnail: 335065.png
kt: 8753
exl-id: b961ba8c-9597-4ed4-a6d7-79689c8e290d
doc-type: video
source-git-commit: 650e4d346e1792863930dcebafacab4c88f2a8bc
workflow-type: tm+mt
source-wordcount: '379'
ht-degree: 0%

---

# Configuration des paramètres globaux par défaut du projet

<!---
21.4 updates have been made
--->

Dans cette vidéo, vous apprendrez à :

* Modifier un état personnalisé
* Définition des préférences globales de projet
* Création et utilisation des plannings

>[!VIDEO](https://video.tv.adobe.com/v/335065/?quality=12&learn=on)

## Paramètres globaux et de projet, de tâche et de problème de groupe

Lorsque vous ouvrez le [!UICONTROL Projets] paramètres dans [!DNL Workfront], vous remarquerez qu’il indique &quot;[!UICONTROL Préférences du projet système]&quot; dans la barre de recherche située en haut de la fenêtre. Cela vous permet de savoir si ces paramètres affectent toutes les personnes de votre [!DNL Workfront] système — c&#39;est une configuration globale.

![[!UICONTROL Préférences du projet] page [!UICONTROL Configuration]](assets/admin-fund-system-project-preferences-1.png)

Vous verrez quelque chose de similaire lorsque vous ouvrez la [!UICONTROL Tâches et problèmes] paramètres.

![[!UICONTROL Tâche et préférences de problème] in [!UICONTROL Configuration]](assets/admin-fund-task-issue-preferences-2.png)

Cependant, il est possible que tous les groupes de [!DNL Workfront] nécessite le même projet, la même tâche et les mêmes préférences de publication. Par exemple, le groupe marketing souhaite que l’état d’un nouveau projet soit Planification tandis que le groupe de gestionnaires de projet préfère l’état Requête .

[!DNL Workfront] permet aux administrateurs de groupe d’ajuster certaines préférences de projet, de tâche et d’émission pour leurs groupes. Les préférences qui peuvent être ajustées sont déterminées par la variable [!DNL Workfront] administrateur système à l’aide des bascules de verrouillage/déverrouillage.

Commencez par accéder au [!UICONTROL Configuration] area :

1. Sélectionner **[!UICONTROL Configuration]** dans le **[!UICONTROL Menu Principal]**.
1. Développer **[!UICONTROL Préférences du projet]** dans le menu de gauche.
1. Sélectionner **[!UICONTROL Projets]** ou **[!UICONTROL Tâches et problèmes]**, selon les paramètres que vous souhaitez modifier.

Verrouillez une préférence pour empêcher les administrateurs de groupe d’ajuster ce paramètre pour leur groupe.

![Message de préférence verrouillé](assets/admin-fund-preferences-locked-3.png)

Déverrouillez la préférence pour la rendre disponible pour que les administrateurs de groupe puissent la personnaliser.

![Message de préférence déverrouillé](assets/admin-fund-preferences-unlocked-4.png)

Certains paramètres ne peuvent pas être déverrouillés et restent des paramètres système globaux.

![Message de préférence verrouillé](assets/admin-fund-preferences-always-locked-5.png)

### Définition des préférences de groupe et de sous-groupe

Pour tous les paramètres déverrouillés par l’administrateur système, les administrateurs du groupe peuvent apporter des modifications au(x) groupe(s) qu’ils gèrent et aux sous-groupes imbriqués dans ces groupes. En outre, les administrateurs de groupe peuvent contrôler les paramètres que leurs administrateurs de sous-groupe peuvent modifier.

1. Sélectionner **[!UICONTROL Configuration]** dans le **[!UICONTROL Menu Principal]**.
1. Cliquez sur **[!DNL Groups]** dans le menu de gauche.
1. Cliquez sur le nom du groupe ou du sous-groupe pour l’ouvrir.
1. Sélectionner **[!UICONTROL Préférences du projet]** ou **[!UICONTROL Tâches et préférences relatives aux problèmes]** dans le menu de gauche.
1. Apportez les modifications nécessaires pour chacune des préférences déverrouillées.
1. Sélectionner **[!UICONTROL Enregistrer]**.

![[!UICONTROL État du projet] section sur [!UICONTROL Groupe] page](assets/admin-fund-group-preferences.png)

Si votre entreprise n’utilise pas d’administrateurs de groupe, l’administrateur système peut gérer les paramètres des préférences pour les différents groupes.

<!---
learn more URLs and guides
Create or edit a group status 
Group administrators 
Configure system-wide project preferences 
Configure project preferences for a group 
Configure task and issue preferences for a group 
Create and modify a group’s schedule 
--->
