---
title: Bonnes pratiques - Filtres, vues et regroupements
description: Découvrez les bonnes pratiques recommandées par les spécialistes Adobe Workfront en matière de configuration, de gestion et d’utilisation des filtres, des vues et des regroupements Workfront.
feature: Reports and Dashboards
role: Admin, Leader, User
level: Beginner
jira: KT-10911
exl-id: 845aa0b4-3fe9-4bc1-9dde-2f22c537e758
source-git-commit: 0ff5accae867f07cc31ac2be7b0c12981412346e
workflow-type: tm+mt
source-wordcount: '785'
ht-degree: 70%

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

* Utilisez les contrôles de liste dans les modèles de disposition pour masquer les filtres, les vues et les regroupements inutiles pour les objets couramment utilisés (projets, tâches, programmes, etc.).

* Partagez des filtres, des vues et des regroupements personnalisés pertinents pour les processus et les workflows de votre entreprise grâce aux commandes de liste des modèles de mise en page.

* Lors de la création de filtres pour le statut d’un projet, le statut d’une tâche ou le statut d’un problème, utiliser (objet)>>Statut Est égal à Source du champ/nom du champ avec le modificateur Égal, plutôt que Projet>>Statut Source du champ/Nom du champ.

</br>
</br>

## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Réduisez le nombre de rapports personnalisés que vous créez en utilisant les filtres, les vues et les regroupements sur une liste d’objets pour obtenir les données dont vous avez besoin.

**Voici pourquoi : **

La création de rapports d’utilisation uniques pour chaque segment de données que vous souhaitez afficher prend du temps et encombre le système Workfront.

Pour plus d’informations sur la création de rapports avec des invites, reportez-vous au chapitre intitulé &quot;Comment configurer et utiliser les invites de rapports&quot; dans la section [Présentation des paramètres des rapports](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/report-settings.html) vidéo.

Pour plus d’informations sur la création de rapports avec des invites personnalisées, voir [Création d’invites personnalisées](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/intermediate-reporting/custom-prompts.html).

</br>
</br>

**Bonne pratique**

Utilisez les contrôles de liste dans les modèles de disposition pour masquer les filtres, les vues et les regroupements inutiles pour les objets couramment utilisés (projets, tâches, programmes, etc.).

**Voici pourquoi : **

Simplicité rime avec efficacité. Le masquage des options de filtrage, d’affichage et de liste de regroupement qui ne sont pas pertinentes pour les workflows quotidiens de vos utilisateurs réduit les listes, ce qui facilite la recherche plus rapide des besoins des utilisateurs.

Pour plus d’informations sur le masquage des filtres, des vues ou des groupes avec des modèles de mise en page, voir [Personnalisation des listes de rapports avec des modèles de mise en page](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/layout-templates/customize-reporting-lists-with-layout-templates.html).

</br>
</br>

**Bonnes pratiques**

Partagez des filtres, des vues et des regroupements personnalisés pertinents pour les processus et les workflows de votre entreprise grâce aux commandes de liste des modèles de mise en page.

**Voici pourquoi : **

Si vous avez créé des filtres, des vues et des regroupements qui affichent des informations spécifiques aux processus quotidiens des utilisateurs, il est facile de les partager par le biais des modèles de mise en page. Cela permet de s’assurer que toutes les personnes affectées à ce modèle de disposition disposent des options de filtrage, de vues et de regroupements correspondant à leurs workflows.

La personnalisation des informations que vous souhaitez rendre visibles à vos utilisateurs et utilisatrices via les modèles de disposition permet également aux administrateurs et administratrices système et de groupes de gagner du temps, car ceux-ci n’auront pas à partager individuellement chaque filtre, vue ou option de regroupement.

Pour plus d’informations sur le partage de filtres, de vues ou de groupes avec des modèles de mise en page, voir [Personnalisation des listes de rapports avec des modèles de mise en page](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/layout-templates/customize-reporting-lists-with-layout-templates.html).

</br>
</br>

**Bonne pratique**

Lors de la création de filtres pour le statut d’un projet, le statut d’une tâche ou le statut d’un problème, utiliser (objet)>>Statut Est égal à Source du champ/nom du champ avec le modificateur Égal, plutôt que Projet>>Statut Source du champ/Nom du champ.

**Voici pourquoi : **

En utilisant (objet)&quot;Égal à, vous incluez tous les statuts personnalisés auxquels ce statut spécifique est affecté dans le champ Égal à dans les configurations d’état. Tandis que la configuration du filtre telle que (objet)>>Statut > Égal nécessite que vous sélectionniez des statuts spécifiques pour le filtre. Cela pourrait poser un problème de maintenance si vous deviez tenir compte de ces nouveaux statuts dans d’autres filtres. Chaque filtre devrait alors être ouvert et mis à jour avec le nouveau statut.

Par exemple, si vous souhaitez voir tous les projets en cours, vous pouvez configurer votre filtre de la manière suivante : Projet>>Statut > Actuel. Cependant, si quelqu’un ajoute un état personnalisé nommé Actif et l’associe à Actif, ce filtre ne trouvera pas de projets avec l’état Actif. Toutefois, si vous utilisez Projet>>Statut Est égal à > Égal > Actuel, le filtre peut alors trouver des objets ayant le statut Actuel ou Actif, car ils possèdent tous deux le statut Actif dans le champ Est égal à.
