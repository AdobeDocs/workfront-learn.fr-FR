---
title: Présentation des mesures de performances
description: 'Les mesures de performances sont les suivantes : [!UICONTROL Méthode d’index de performance] ([!UICONTROL PIM]) et la variable [!UICONTROL Estimation à la fin] ([!UICONTROL EAC]).'
feature: Work Management
thumbnail: understand-performance-metrics.png
type: Tutorial
role: User
level: Intermediate
kt: 10065
exl-id: 190c66f5-b412-48bd-8695-3bd7da088ccb
source-git-commit: d0c842ad8bf6f52161f003a62237fbcd35d23176
workflow-type: tm+mt
source-wordcount: '423'
ht-degree: 0%

---

# Présentation des mesures de performances

Deux mesures de performances utilisées par les chefs de projet incluent la variable [!UICONTROL Méthode d’index de performance] ([!UICONTROL PIM]) et la variable [!UICONTROL Estimation à la fin] ([!UICONTROL EAC]). Les valeurs par défaut à l’échelle du système peuvent être définies dans [!DNL Workfront] et s’appliquent aux projets nouvellement créés. [!UICONTROL PIM] peuvent ensuite être modifiés sur des projets individuels.

**[!UICONTROL MIP]**

Les paramètres de la variable [!UICONTROL PIM] contrôler comment [!DNL Workfront] calcule d’autres mesures de performances de projet, telles que la variable [!UICONTROL Indice de performance des coûts] ([!UICONTROL IPC]), [!UICONTROL Indice de performance de la planification des coûts] ([!UICONTROL CSI]), [!UICONTROL Planification de l’index de performance] ([!UICONTROL SPI]), et [!UICONTROL Estimation à la fin] ([!UICONTROL EAC]).

Options pour le [!UICONTROL PIM] sont basés sur les heures et les coûts.

* **Basé sur l’heure** — Workfront utilise les heures prévues pour calculer l’IPC et la CAE du projet. Le champ d’application du projet s’affiche sous la forme d’un nombre, en heures.
* **Basé sur les coûts** — Workfront utilise le coût du travail prévu pour calculer l&#39;IPC et la CAE du projet. La zone de contrôle d’accès apparaît comme valeur monétaire. Lorsque vous utilisez cette option, assurez-vous que les personnes désignées pour les tâches (utilisateurs et/ou rôles de tâche) sont associées aux taux de coût.

**[!UICONTROL CRE]**

[!UICONTROL EAC] représente le coût total prévu de la tâche ou du projet une fois qu’il s’est terminé. Les options sont calculées au niveau du projet et cumulées à partir des tâches/sous-tâches.

* **Calcul au niveau du projet** — [!UICONTROL EAC] pour la tâche parent et le projet sont déterminés à l’aide des heures réelles/coûts de main-d’oeuvre réels dans [!UICONTROL EAC] formules. Le calcul inclut les heures/coûts réels et les dépenses ajoutées directement à la tâche ou au projet parent.
* R **Cumuler à partir de tâches/sous-tâches** — [!UICONTROL EAC] pour la tâche parent et le projet sont déterminés en additionnant les éléments [!UICONTROL EAC] pour chaque tâche enfant. Ce calcul exclut les heures/coûts réels ajoutés directement à une tâche ou à un projet parent.

Le [!UICONTROL EAC] les calculs sont répertoriés dans la section &quot;Calcul de l’estimation à l’achèvement (EAC)&quot;. <!-- link to article -->article sur [!UICONTROL [!DNL Workfront] One].

**Mesures de performances : Paramètres**

Pour définir [!UICONTROL PIM] et [!UICONTROL EAC] valeurs par défaut du système :

1. Sélectionner **[!UICONTROL Configuration]** dans le menu principal.
1. Cliquez sur **[!UICONTROL Préférences du projet]** dans le menu du panneau de gauche, puis cliquez sur **[!UICONTROL Projets]**
1. Dans le [!UICONTROL État du projet] , rechercher [!UICONTROL Méthode d’index de performance]. Sélectionnez Basé sur les heures ou Basé sur les coûts.
1. Pour [!UICONTROL Estimation à la fin], sélectionnez Calculer au niveau du projet ou Cumuler à partir des tâches/sous-tâches.
1. Cliquez sur **[!UICONTROL Enregistrer]** au bas de la fenêtre.

![Une image de la fonction [!UICONTROL Préférences du projet] écran](assets/setting-up-finances-1.png)

**Définir [!UICONTROL PIM] sur des projets individuels**

1. Accédez à la landing page d&#39;un projet.
1. Cliquez sur **[!UICONTROL Détails du projet]** dans le panneau de gauche.
1. Ouvrez le **[!UICONTROL Finance]** .
1. Double-cliquez sur le texte ci-dessous. **[!UICONTROL Méthode d’index de performance]** pour la modifier.
1. Sélectionnez Basé sur les heures ou Basé sur les coûts.
1. Cliquez sur **[!UICONTROL Enregistrer]** Modifications à terminer.

![Une image de la fonction [!UICONTROL Détails du projet] écran](assets/setting-up-finances-2.png)

[!UICONTROL PIM] peut être défini sur un modèle de projet, dans la variable [!UICONTROL Finance] des détails du modèle.
