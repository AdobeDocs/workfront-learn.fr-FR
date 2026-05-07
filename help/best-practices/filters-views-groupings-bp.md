---
title: Bonnes pratiques - Filtres, vues et regroupements
description: Découvrez les bonnes pratiques recommandées par les spécialistes Adobe Workfront en matière de configuration, de gestion et d’utilisation des filtres, des vues et des regroupements Workfront.
feature: Reports and Dashboards
role: Admin, Leader, User
level: Beginner
jira: KT-10911
exl-id: 845aa0b4-3fe9-4bc1-9dde-2f22c537e758
TQID: https://experienceleague.adobe.com/hTZWn-fzcprOD-b7CU9k6JWfUh0VBCok2g8tG1c6fYE
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
  - id: f8a45b24-4be7-4f1b-909b-60d06b483a20
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: aa2f3246-cb95-4b30-8899-fdf7d73550cc
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: 36674ed53c8645f556862bb2d99f3bfd6c993c1e
workflow-type: tm+mt
source-wordcount: 846
ht-degree: 100%

---

# Bonnes pratiques - Filtres, vues et regroupements

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques relatives à ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La question « Pourquoi s’agit-il de bonnes pratiques » ? qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux filtres, aux vues et aux regroupements

* Réduisez le nombre de rapports personnalisés que vous créez en utilisant les filtres, les vues et les regroupements sur une liste d’objets pour obtenir les données dont vous avez besoin.

* Utilisez les contrôles de liste dans les modèles de mise en page pour masquer les filtres, les vues et les regroupements inutiles pour les objets couramment utilisés (projets, tâches, programmes, etc.).

* Partagez des filtres, des vues et des regroupements personnalisés correspondant aux workflows et aux processus de votre organisation grâce aux contrôles de listes des modèles de mise en page.

* Lors de la création de filtres pour le statut d’un projet, le statut d’une tâche ou le statut d’un problème, utiliser (objet)>>Statut Est égal à Source du champ/nom du champ avec le modificateur Égal, plutôt que Projet>>Statut Source du champ/Nom du champ.

</br>
</br>

## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Réduisez le nombre de rapports personnalisés que vous créez en utilisant les filtres, les vues et les regroupements sur une liste d’objets pour obtenir les données dont vous avez besoin.

**Voici pourquoi : **

La création de rapports d’utilisation uniques pour chaque segment de données que vous souhaitez afficher prend du temps et encombre le système Workfront.

Pour plus d’informations sur la création de rapports avec des invites, reportez-vous au chapitre intitulé « Configurer et utiliser les invites de rapports » dans la vidéo [Comprendre les paramètres des rapports](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/report-settings.html?lang=fr).

Pour plus d’informations sur la création de rapports avec des invites personnalisées, voir [Créer des invites personnalisées](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/intermediate-reporting/custom-prompts.html?lang=fr).

</br>
</br>

**Bonne pratique**

Utilisez les contrôles de liste dans les modèles de mise en page pour masquer les filtres, les vues et les regroupements inutiles pour les objets couramment utilisés (projets, tâches, programmes, etc.).

**Voici pourquoi : **

Simplicité rime avec efficacité. En masquant les options de filtrage, de vues et de regroupements qui ne sont pas pertinentes pour les workflows quotidiens de vos utilisateurs et utilisatrices, vous réduisez la taille des listes, ce qui permet aux utilisateurs et aux utilisatrices de trouver plus rapidement ce dont ils ont besoin.

Pour plus d’informations sur le masquage des filtres, des vues ou des groupes avec des modèles de mise en page, voir [Personnaliser les listes de rapports avec des modèles de mise en page](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/layout-templates/customize-reporting-lists-with-layout-templates.html?lang=fr).

</br>
</br>

**Bonnes pratiques**

Partagez des filtres, des vues et des regroupements personnalisés correspondant aux workflows et aux processus de votre organisation grâce aux contrôles de listes des modèles de mise en page.

**Voici pourquoi : **

Si vous avez créé des filtres, des vues et des regroupements qui affichent des informations spécifiques aux processus quotidiens des utilisateurs et des utilisatrices, il est facile de les partager grâce aux modèles de mise en page. Cela permet de s’assurer que toutes les personnes affectées à ce modèle de mise en page disposent des options de filtrage, de vues et de regroupements correspondant à leurs workflows.

La personnalisation des informations que vous souhaitez rendre visibles à vos utilisateurs et utilisatrices via les modèles de mise en page permet également aux administrateurs et administratrices système et de groupes de gagner du temps, car ceux-ci n’auront pas à partager individuellement chaque filtre, vue ou option de regroupement.

Pour plus d’informations sur le partage de filtres, de vues ou de groupes avec des modèles de mise en page, voir [Personnaliser les listes de rapports avec des modèles de mise en page](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/layout-templates/customize-reporting-lists-with-layout-templates.html?lang=fr).

</br>
</br>

**Bonne pratique**

Lors de la création de filtres pour le statut d’un projet, le statut d’une tâche ou le statut d’un problème, utiliser (objet)>>Statut Est égal à Source du champ/nom du champ avec le modificateur Égal, plutôt que Projet>>Statut Source du champ/Nom du champ.

**Voici pourquoi : **

En utilisant (objet)>>Est égal à, vous incluez tous les statuts personnalisés auxquels ce statut spécifique est affecté dans le champ Est égal à dans les configurations de statut. Tandis que la configuration du filtre telle que (objet)>>Statut > Égal nécessite que vous sélectionniez des statuts spécifiques pour le filtre. Cela pourrait poser un problème de maintenance si vous deviez tenir compte de ces nouveaux statuts dans d’autres filtres. Chaque filtre devrait alors être ouvert et mis à jour avec le nouveau statut.

Par exemple, si vous souhaitez voir tous les projets en cours, vous pouvez configurer votre filtre de la manière suivante : Projet>>Statut > Actuel. Cependant, si une personne ajoute un statut personnalisé nommé Actif et l’associe à Actuel, ce filtre ne trouvera pas de projets avec le statut Actif. Toutefois, si vous utilisez Projet>>Statut Est égal à > Égal > Actuel, le filtre peut alors trouver des objets ayant le statut Actuel ou Actif, car ils possèdent tous deux le statut Actif dans le champ Est égal à.
