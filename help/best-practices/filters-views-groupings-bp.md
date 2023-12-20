---
title: Bonne pratique - Filtres, vues et groupes
description: Découvrez les recommandations de bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation des filtres, vues et regroupements Workfront.
feature: Reports and Dashboards
role: Admin, Leader, User
level: Beginner
jira: KT-10911
exl-id: 845aa0b4-3fe9-4bc1-9dde-2f22c537e758
source-git-commit: 0ff5accae867f07cc31ac2be7b0c12981412346e
workflow-type: tm+mt
source-wordcount: '785'
ht-degree: 0%

---

# Bonne pratique - Filtres, vues et groupes

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les bonnes pratiques sont des consignes qui représentent un plan d’action efficace. Elles sont facilement adoptées par vous et les utilisateurs de votre entreprise et peuvent être répliquées avec succès dans l’ensemble de votre entreprise.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux filtres, aux vues et aux regroupements

* Réduisez le nombre de rapports personnalisés que vous créez en utilisant les filtres, vues et regroupements sur une liste d’objets pour obtenir les données dont vous avez besoin.

* Les commandes de liste des modèles de mise en page permettent de masquer les filtres, les vues et les regroupements inutiles pour les objets fréquemment utilisés (projets, tâches, programmes, etc.).

* Partagez des filtres, des vues et des regroupements personnalisés pertinents pour les processus et les workflows de votre entreprise grâce aux commandes de liste des modèles de mise en page.

* Lors de la création de filtres pour l’état du projet, l’état de la tâche ou l’état du problème, utilisez (objet)&quot;État = Est égal à avec la source/le nom du champ avec le modificateur Egal, plutôt que le nom Projet&quot;Source/nom du champ État.

</br>
</br>

## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Réduisez le nombre de rapports personnalisés que vous créez en utilisant les filtres, vues et regroupements sur une liste d’objets pour obtenir les données dont vous avez besoin.

**Voici pourquoi :**

La création de rapports d’utilisation uniques pour chaque segment de données que vous souhaitez afficher prend du temps et encombre le système Workfront.

Pour plus d’informations sur la création de rapports avec des invites, reportez-vous au chapitre intitulé &quot;Comment configurer et utiliser les invites de rapports&quot; dans la section [Présentation des paramètres des rapports](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/basic-reporting/report-settings.html) vidéo.

Pour plus d’informations sur la création de rapports avec des invites personnalisées, voir [Création d’invites personnalisées](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/reporting/intermediate-reporting/custom-prompts.html).

</br>
</br>

**Bonne pratique**

Les commandes de liste des modèles de mise en page permettent de masquer les filtres, les vues et les regroupements inutiles pour les objets fréquemment utilisés (projets, tâches, programmes, etc.).

**Voici pourquoi :**

Moins c&#39;est plus. Le masquage des options de filtrage, d’affichage et de liste de regroupement qui ne sont pas pertinentes pour les workflows quotidiens de vos utilisateurs réduit les listes, ce qui facilite la recherche plus rapide des besoins des utilisateurs.

Pour plus d’informations sur le masquage des filtres, des vues ou des groupes avec des modèles de mise en page, voir [Personnalisation des listes de rapports avec des modèles de mise en page](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/layout-templates/customize-reporting-lists-with-layout-templates.html).

</br>
</br>

**Bonne pratique**

Partagez des filtres, des vues et des regroupements personnalisés pertinents pour les processus et les workflows de votre entreprise grâce aux commandes de liste des modèles de mise en page.

**Voici pourquoi :**

Si vous avez créé des filtres, des vues et des regroupements qui affichent des informations spécifiques aux processus quotidiens des utilisateurs, il est facile de les partager par le biais des modèles de mise en page. Ainsi, chaque personne affectée au modèle de mise en page dispose d’options de filtrage, d’affichage et de regroupement pertinentes pour ses workflows.

La personnalisation des informations que vous souhaitez afficher pour vos utilisateurs à l’aide des modèles de mise en page est également un gain de temps pour les administrateurs système et groupe, car ils n’auront pas à partager individuellement chaque option de filtrage, d’affichage ou de regroupement.

Pour plus d’informations sur le partage de filtres, de vues ou de groupes avec des modèles de mise en page, voir [Personnalisation des listes de rapports avec des modèles de mise en page](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/layout-templates/customize-reporting-lists-with-layout-templates.html).

</br>
</br>

**Bonne pratique**

Lors de la création de filtres pour l’état du projet, l’état de la tâche ou l’état du problème, utilisez (objet)&quot;État = Est égal à avec la source/le nom du champ avec le modificateur Egal, plutôt que le nom Projet&quot;Source/nom du champ État.

**Voici pourquoi :**

En utilisant (objet)&quot;Égal à, vous incluez tous les statuts personnalisés auxquels ce statut spécifique est affecté dans le champ Égal à dans les configurations d’état. En revanche, si vous définissez le filtre sur (objet)&quot;Statut > Égal , vous devez sélectionner des statuts spécifiques pour le filtre. Cela peut poser un problème de maintenance si vous devez tenir compte de ces nouveaux statuts dans divers filtres. Chaque filtre doit être ouvert et mis à jour avec le nouvel état .

Par exemple, si vous souhaitez afficher tous les projets en cours, vous pouvez configurer votre filtre pour qu’il lise Projet > État > Égal > Actuel. Cependant, si quelqu’un ajoute un état personnalisé nommé Actif et l’associe à Actif, ce filtre ne trouvera pas de projets avec l’état Actif. Cependant, si vous utilisez l’option Projet > État égal à > Égal à > Actuel, le filtre trouve les objets ayant l’état Actuel ou Actif, car ils ont tous deux l’état Actuel dans le champ Égal à avec .
