---
title: Comprendre les mesures de performances
description: 'Découvrez comment utiliser les mesures de performances : [!UICONTROL Méthode d’index de performance] ([!UICONTROL PIM]) et [!UICONTROL Estimation à l’achèvement] ([!UICONTROL EAC]).'
activity: use
team: Technical Marketing
feature: Work Management
thumbnail: understand-performance-metrics.png
type: Tutorial
role: User
level: Intermediate
jira: KT-10065
exl-id: 190c66f5-b412-48bd-8695-3bd7da088ccb
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: ht
source-wordcount: '433'
ht-degree: 100%

---

# Comprendre les mesures de performances

Deux mesures de performances utilisées par les personnes chargées de la gestion de projet sont la [!UICONTROL Méthode d’index de performance] ([!UICONTROL PIM]) et l’[!UICONTROL Estimation à l’achèvement] ([!UICONTROL EAC]). Les valeurs par défaut du système peuvent être définies dans [!DNL Workfront] et s’appliquent aux projets nouvellement créés. La mesure [!UICONTROL PIM] peut ensuite être modifiée sur des projets individuels.

**[!UICONTROL MIP]**

Les paramètres de la mesure [!UICONTROL PIM] contrôlent comment [!DNL Workfront] calcule d’autres mesures de performances de projet, telles que les mesures [!UICONTROL Indice de performance des coûts] ([!UICONTROL CPI]), [!UICONTROL Indice de performance de la planification des coûts] ([!UICONTROL CSI]), [!UICONTROL Planification de l’index de performance] ([!UICONTROL SPI]), et [!UICONTROL Estimation à l’achèvement] ([!UICONTROL EAC]).

Les options pour la mesure [!UICONTROL PIM] sont Basé sur les heures et Basé sur les coûts.

* **Basé sur les heures** : Workfront utilise le nombre d’heures prévues pour calculer le CPI et l’EAC du projet. L’EAC du projet s’affiche sous la forme d’un nombre, en heures.
* **Basé sur les coûts** : Workfront utilise le coût prévu de la main-d’œuvre pour calculer le CPI et l’EAC du projet. L’EAC apparaît comme une valeur monétaire. Lorsque vous utilisez cette option, assurez-vous que les personnes désignées pour les tâches (utilisateurs et utilisatrices et/ou fonctions) sont associées aux taux de coût.

**[!UICONTROL CRE]**

L’[!UICONTROL EAC] représente le coût total prévu de votre tâche ou de votre projet lorsqu’il sera achevé. Les options sont calculées au niveau du projet et cumulées à partir des tâches/sous-tâches.

* **Calculer au niveau du projet** : l’[!UICONTROL EAC] pour la tâche parent et le projet est déterminé à l’aide des heures réelles/du coût réel de la main-d’œuvre dans les formules de l’[!UICONTROL EAC]. Le calcul inclut les heures effectives/les coûts et les dépenses ajoutées directement à la tâche ou au projet parent.
* **Cumuler à partir des tâches/sous-tâches** : l’[!UICONTROL EAC] pour la tâche parent et le projet est déterminé en additionnant l’[!UICONTROL EAC] pour chaque tâche enfant. Ce calcul exclut les heures effectives/les coûts ajoutés directement à une tâche ou à un projet parent.

Les calculs de l’[!UICONTROL EAC] sont répertoriés dans la section [Calculer l’estimation à l’achèvement (EAC)](https://experienceleague.adobe.com/docs/workfront/using/manage-work/projects/project-finances/calculate-eac.html?lang=fr).

**Mesures de performances : paramètres**

Pour définir les valeurs par défaut du système de la [!UICONTROL PIM] et de l’[!UICONTROL EAC] :

1. Sélectionnez **[!UICONTROL Configuration]** dans le menu principal.
1. Cliquez sur **[!UICONTROL Préférences du projet]** dans le menu du panneau de gauche, puis cliquez sur **[!UICONTROL Projets]**.
1. Dans la section [!UICONTROL Statut du projet], recherchez [!UICONTROL Méthode d’index de performance]. Sélectionnez Basé sur les heures ou Basé sur les coûts.
1. Pour [!UICONTROL Estimation à l’achèvement], sélectionnez Calculer au niveau du projet ou Cumuler à partir des tâches/sous-tâches.
1. Cliquez sur **[!UICONTROL Enregistrer]** au bas de la fenêtre.

![Image de l’écran [!UICONTROL Préférences du projet]](assets/setting-up-finances-1.png)

**Définir la [!UICONTROL PIM] sur des projets individuels**

1. Accédez à la page de destination d’un projet.
1. Cliquez sur **[!UICONTROL Détails du projet]** dans le panneau de gauche.
1. Ouvrez la section **[!UICONTROL Finance]**.
1. Double-cliquez sur le texte sous **[!UICONTROL Méthode d’index de performance]** pour le modifier.
1. Sélectionnez Basé sur les heures ou Basé sur les coûts.
1. Cliquez sur **[!UICONTROL Enregistrer]** les modifications pour terminer.

![Image de l’écran [!UICONTROL Détails du projet]](assets/setting-up-finances-2.png)

La [!UICONTROL PIM] peut être définie sur un modèle de projet, dans la section [!UICONTROL Finance] des détails du modèle.
