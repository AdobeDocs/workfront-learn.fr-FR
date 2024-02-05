---
title: Rapport sur les BAT
description: Découvrez comment utiliser les fonctionnalités de création de rapports pour gérer la progression des BAT.
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User, Admin
level: Intermediate
thumbnail: report-on-proofs.png
jira: KT-10233
exl-id: 9a1a9e16-61cc-4f95-977a-8870b7fd0dda
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: ht
source-wordcount: '445'
ht-degree: 100%

---

# Rapport sur les BAT

Les fonctions d’épreuvage numérique de [!DNL Workfront] vous permettent de gérer les projets et les workflows de révision connexes en un seul endroit, [!DNL Workfront]. Obtenez des informations précieuses sur le travail d’épreuvage effectué avec les types de rapports, les sources de champ et les noms de champ qui affichent les informations de révision et d’approbation.

Nous vous recommandons de travailler avec votre consultant ou consultante [!DNL Workfront] pour créer des rapports qui répondent aux besoins de votre organisation. Certains rapports requièrent une connaissance approfondie de la fonction de création de rapports en mode texte de [!DNL Workfront].

Commencez par ces rapports standard de base pour aider vos équipes à gérer les BAT lors d’un processus de révision et d’approbation dans [!DNL Workfront].

## [!UICONTROL Approbation d&#39;épreuve]

Ce type de rapport permet de suivre les approbations de BAT en cours afin de s’assurer que les délais sont respectés.

![Sélectionnez [!UICONTROL Approbation des BAT] dans le menu déroulant [!UICONTROL Nouveau rapport]](assets/proof-system-setups-proof-approval-report.png).

Les options d’affichage et de filtrage comprennent [!UICONTROL la date de décision], [!UICONTROL l’approbation des BAT], [!UICONTROL l’étape d’approbation], [!UICONTROL le modèle de workflow], et [!UICONTROL les informations sur le demandeur]. Avec la création de rapports en mode texte, vous pouvez créer un regroupement qui organise la liste par nom de document. Voir [Comprendre le mode de texte de base pour les regroupements](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/intermediate-reporting/basic-text-mode-for-groupings.html?lang=fr).

Lorsque vous rédigez des rapports d’approbation de BAT, assurez-vous d’obtenir des informations relatives à la version la plus récente des BAT. [!DNL Workfront] recommande d’inclure cette source de champ et ce nom de champ dans le filtre :

**[!UICONTROL Approbation des BAT]>>[!UICONTROL Est la version actuelle du document]**

![Onglet Filtres de Report Builder](assets/proof-system-setups-proof-approval-report-is-current-version.png)

Cela est utile lorsque vous établissez un rapport sur des BAT comportant plusieurs versions, de sorte que le rapport ne mentionne que la version actuelle de chaque BAT qui doit être approuvé. Cela filtre les versions antérieures sur lesquelles vous n’avez plus besoin de travailler.

## [!UICONTROL Version du document]

Ce type de rapport vous permet de gérer et de suivre les versions dans [!DNL Workfront].

![Sélectionnez [!UICONTROL Version du document] dans le menu déroulant [!UICONTROL Nouveau rapport]](assets/proof-system-setups-document-version-report.png).

Les options d’affichage incluent des informations provenant des champs [!UICONTROL version du document], [!UICONTROL document], [!UICONTROL saisi par], [!UICONTROL statut d’approbation des BAT], [!UICONTROL créateur de BAT], et [!UICONTROL fournisseur de documents].

Les regroupements peuvent être effectués en fonction des valeurs [!UICONTROL version du document], [!UICONTROL saisi par], [!UICONTROL statut d’approbation des BAT], ou des informations sur le ou la propriétaire des BAT.

Les filtres incluent : [!UICONTROL version du document], [!UICONTROL niveau d’accès], [!UICONTROL document], [!UICONTROL saisi par], [!UICONTROL statut d’approbation des BAT], [!UICONTROL créateur de BAT] et des informations sur la personne qui fournit les documents.

Vous pouvez afficher, dans une vue, le nom de la phase de BAT actuellement active pour chaque document du rapport, avec cette colonne :

**[!UICONTROL Versions de document] >> [!UICONTROL Étapes de BAT actives]**

![Onglet Filtres de Report Builder](assets/proof-system-setups-active-proof-stages.png)

Si aucune étape n’est actuellement active, la colonne est vide.

Cette combinaison source de champ >> nom de champ est également disponible en tant que filtre dans un rapport.

Utilisez la source de champ [!UICONTROL Créateur de BAT] pour rapporter des informations sur l’utilisateur ou l’utilisatrice qui a créé le BAT. Choisissez la source du champ [!UICONTROL Nom] pour afficher le nom du créateur de BAT dans une vue.

**[!UICONTROL Créateur de BAT] >> [!UICONTROL Nom]**

Cette combinaison source du champ >> nom du champ est également disponible sous forme de filtre.

![Onglet Filtres de Report Builder](assets/proof-system-setups-proof-creator-name.png)

<!--
Learn More Icon
Learn how to create reports in [!DNL Workfront] with the Report Creation class.
Access to proofing functionality
-->
