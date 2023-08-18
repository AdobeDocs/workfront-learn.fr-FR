---
title: Utilisez la variable [!UICONTROL Portfolio Optimizer] prioriser et gérer le travail
description: Découvrez comment utiliser le [!UICONTROL Portfolio Optimizer] pour hiérarchiser et gérer les projets au sein d’un portfolio.
activity: use
team: Technical Marketing
feature: Strategic Planning
thumbnail: prioritize-and-manage-work-with-portfolios.png
type: Tutorial
last-substantial-update: 2023-08-18T00:00:00Z
jira: KT-13835
role: User
level: Intermediate
exl-id: b8b91ae8-f0e1-4cab-bf2c-6b8ca9746ea3
source-git-commit: 64789af613bd6b38e58bd2c15df622729b883b22
workflow-type: tm+mt
source-wordcount: '885'
ht-degree: 0%

---

# Utilisez la variable [!UICONTROL Portfolio Optimizer] prioriser et gérer le travail

Les informations saisies dans la variable [!UICONTROL Analyse de cas] pour chaque projet de votre portefeuille se cumule dans le portefeuille et dans l’en-tête de la variable [!UICONTROL Optimisation des Portfolios] .

![Une image de la [!UICONTROL Portfolio Optimizer] avec des informations de la fonction [!UICONTROL Analyse de cas]](assets/10-portfolio-management9.png)

Il est maintenant temps d&#39;utiliser ces informations pour analyser quels projets doivent être mis en production rapidement et lesquels peuvent rester en marge jusqu&#39;au prochain tour. La variable [!UICONTROL Optimisation des Portfolios] cet outil aidera énormément.

La variable [!UICONTROL Portfolio Optimizer] peut vous aider pleinement si :

* La variable [!UICONTROL Analyse de cas] a été terminé et soumis sur tous les projets.
* Cliquez sur le bouton [!UICONTROL Envoyer] dans le [!UICONTROL Analyse de cas] afin que Workfront calcule le score d’un projet.
* Vous fournissez un budget pour représenter le budget total des projets sélectionnés.

## Critères d’optimisation

La variable [!UICONTROL Portfolio Optimizer] utilise un ensemble standard de critères pour comparer et classer par priorité les projets.

Ces critères sont les suivants :

* Coût faible
* Alignement élevé
* Valeur élevée
* Un faible risque pour le bénéfice
* ROI élevé

Cliquez sur l’icône Optimiser pour ouvrir un ensemble de barres de curseur, chacune étant associée à l’un des critères. Vous pouvez définir les critères qui ont une priorité plus élevée en déplaçant le curseur vers la droite ou une priorité plus faible en le repoussant vers la gauche.

![Une image de la [!UICONTROL Portfolio Optimizer] avec des informations de la fonction [!UICONTROL Analyse de cas]](assets/11-portfolio-management10.png)

l&#39;utilisation de ces critères, [!DNL Workfront] génère un score de projet compris entre 1 et 100. Les projets dont le nombre est le plus élevé indiquent qu’ils s’alignent mieux sur la direction que vous souhaitez prendre pour le portefeuille.

![Une image de la [!UICONTROL Portfolio Optimizer] zone contenant des informations sur les scores du projet](assets/12-portfolio-management14.png)

>[!NOTE]
>
>La variable [!UICONTROL Portfolio Optimizer] ne marque pas le projet, même si toutes les sections de la variable [!UICONTROL Analyse de cas] sont remplis, sauf si la variable [!UICONTROL Analyse de cas] a été soumis au portefeuille par l’intermédiaire de [!DNL Workfront]. À la place d’un score, un symbole d’avertissement s’affiche dans la [!UICONTROL Score] de la colonne [!UICONTROL Portfolio Optimizer]. Passez la souris sur le symbole d’avertissement pour afficher plus d’informations sur la notation du projet.

![Image d’un symbole d’avertissement dans la variable [!UICONTROL Score] de la colonne [!UICONTROL Portfolio Optimizer].](assets/13-portfolio-management12.png)

## Hiérarchisation des projets

Maintenant que les projets ont été notés, vous pouvez rapidement et facilement réorganiser la liste.

En cliquant sur le bouton [!UICONTROL Score] en-tête de colonne, les projets sont triés à nouveau et sont répertoriés du plus haut au plus bas ou du plus bas au plus haut. Vous pouvez classer les projets manuellement en cliquant sur l’icône de barre située à gauche du nombre et en les déposant dans l’ordre de votre choix.

Il peut y avoir des projets dans votre liste que vous ne souhaitez pas comparer. Si vous ne souhaitez pas les voir dans la liste, désélectionnez-les d’abord, puis masquez-les en glissant le bouton à droite, afin que l’arrière-plan du bouton soit bleu. Si vous souhaitez inclure ces projets, faites glisser le bouton d’activation/désactivation vers la gauche pour afficher le gris.

![Une image d’un projet non sélectionné dans la fonction [!UICONTROL Portfolio Optimizer].](assets/14-portfolio-management13.png)

Vous pouvez ainsi visualiser les projets que vous souhaitez comparer les uns aux autres. Une fois les projets notés, filtrés et triés, vous pouvez désormais prendre une décision éclairée quant à la nécessité ou non de modifier les critères selon lesquels les projets sont prioritaires.

Souvenez-vous, [!DNL Workfront] a créé les portfolios et l’outil d’optimisation pour lisser le processus de hiérarchisation des projets. Cependant, vous n’avez pas à utiliser les critères suggérés. Si tout ce que l&#39;outil fait, c&#39;est de vous donner un bon départ ou une fondation à partir de laquelle travailler, c&#39;est bien.

Si, toutefois, les projets sont dans l’ordre de priorité et que vous êtes prêt à finaliser la priorité dans [!DNL Workfront], cliquez sur le **[!UICONTROL Définir la priorité]** en haut à gauche, et le système numérotera les projets à partir de 1 et utilisera ce nombre pour définir la variable [!UICONTROL Priorité du Portfolio] dans chaque projet.

Pour conserver ces nombres en place, veillez à cliquer sur le **[!UICONTROL Enregistrer]** en bas.

![Image d’utilisation de la fonction [!UICONTROL Définir la priorité] pour classer les projets par priorité dans le [!UICONTROL Portfolio Optimizer].](assets/15-portfolio-management15.png)

<!-- 
Pro-tips graphic
-->

* Vous pouvez afficher la priorité des projets telle qu’elle est définie au moyen du [!UICONTROL Portfolio Optimizer] dans le [!UICONTROL Resource Planner]. Cliquez sur le bouton **[!UICONTROL Paramètres]** et activez la fonction **[!UICONTROL Afficher les priorités de Portfolio]** . L’écran actualise et affiche les priorités du portfolio dans la colonne de gauche. Cliquez sur le bouton **[!UICONTROL Commande]** dans la partie supérieure de la colonne pour aligner le [!UICONTROL Resource Planner] priorités et priorités du portefeuille. Veillez à enregistrer lorsque vous avez terminé.

  ![Une image de la [!UICONTROL Priorités du Portfolio] dans la colonne [!UICONTROL Resource Planner].](assets/16-portfolio-management17.png)

## Gestion des modifications

Les Portfolios ne sont certainement pas un remède universel, mais ils peuvent soulager la douleur de changements de priorités. Ce qui autrefois prenait des jours pouvait maintenant prendre des heures, voire quelques minutes.

Lorsque de nouveaux projets sont ajoutés à un portefeuille, ils doivent encore être analysés et hiérarchisés. En utilisant la variable [!UICONTROL Analyse de cas] et le score d’optimisation vous permettent de comparer facilement de nouveaux projets avec les projets demandés, planifiés et en cours.

![Une image du projet [!UICONTROL État] dans la colonne [!UICONTROL Portfolio Optimizer].](assets/17-project-management16.png)

Si, au cours de la comparaison, vous constatez que les nouveaux projets doivent avoir une priorité plus élevée, vous pouvez soit trier à nouveau votre liste en fonction du score d’optimisation, soit les faire glisser et les déposer plus haut dans la liste. Une fois que vous avez terminé, cliquez simplement sur le **[!UICONTROL Définir la priorité]** , enregistrez et votre tâche est terminée.

<!-- Learn more graphic and documentation article links

* Portfolio Optimizer overview 
* Optimize projects in the Portfolio Optimizer 
* Overview of the Portfolio Optimizer score 
* Prioritizing projects in the Portfolio Optimizer

-->
