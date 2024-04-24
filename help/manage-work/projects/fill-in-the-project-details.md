---
title: Renseigner les détails du projet
description: Découvrez les 12 champs de détails du projet que  [!DNL  Workfront]  vous recommande de renseigner lors de la création d’un projet.
activity: use
team: Technical Marketing
feature: Work Management
thumbnail: fill-in-the-project-details.jpeg
type: Tutorial
role: User
level: Beginner
recommendations: noDisplay,noCatalog
jira: KT-10140
exl-id: a62b9421-627a-4f23-ab66-da1f29114225
source-git-commit: c2ba2ddfbbc642398a0136ecbf7c3613208080c4
workflow-type: ht
source-wordcount: '1252'
ht-degree: 100%

---

# Renseigner les détails du projet

Ne vous inquiétez pas... vous n’avez pas à remplir chaque champ et chaque case à cocher dans les détails du projet pour chaque projet que vous créez sur [!DNL  Workfront]. Utilisez les modèles pour préremplir les informations, puis portez votre attention sur les 12 champs les plus importants de détails du projet répertoriés ci-dessous.

1. **Nom**

   Un nom de projet descriptif permet à toute personne d’identifier l’objectif du projet. Veillez à respecter la convention de nommage de projet de votre entreprise, qui peut nécessiter l’inclusion de certaines informations dans le nom du projet (comme un numéro de référence, un nom de service ou un indicateur de catégorie).


1. **Description**

   Lorsque plusieurs personnes travaillent sur un projet, vous, en tant que personne responsable de la gestion du projet, devez vous assurer que tout le monde est au courant des objectifs et des attentes du projet.

   Pour ce faire, la description du projet doit fournir des informations de base, répondre aux questions et permettre à l’équipe de projet d’avancer dans son travail. Par exemple, « Campagne visant à augmenter de 50 % le travail générant des recettes » ou « Nouvelle mise à niveau du système pour améliorer l’efficacité dans l’ensemble du service ».

   Certaines personnes clientes de Workfront incluent un exemple de description d’un projet à l’apparence des modèles de projet.

1. **Statut**

   Le statut est utilisé dans Workfront pour indiquer où, ou à quel stade, se trouve un projet dans le workflow. Le statut est utilisé dans de nombreux rapports Workfront pour suivre l’avancement du travail.

   Workfront recommande que le statut soit défini sur Planification pendant que vous élaborez et finalisez le plan du projet. L’élément clé du statut Planification est que les notifications Workfront ne sont pas envoyées aux personnes désignées pour la tâche concernant le projet tant qu’il est dans ce statut.

   Une fois que le projet est prêt à être mis en œuvre, modifiez le statut en « Actif ». Cela permet à Workfront d’envoyer des notifications aux personnes au sujet des nouvelles tâches auxquelles elles sont affectées, mais il n’envoie pas de notifications aux utilisateurs et utilisatrices pour les tâches qui leur ont été affectées alors que le projet était au statut Planification.

   >[!TIP]
   >
   >  Lorsque vous apportez des modifications au projet (par exemple, en modifiant les dates d’échéance), vous pouvez restaurer le statut sur Planification ou désactiver la fonction d’enregistrement automatique pour empêcher les notifications d’être envoyées jusqu’à la fin des modifications.

   Le statut Planification peut être défini par l’administrateur ou l’administratrice système comme valeur par défaut globale de Workfront pour les nouveaux projets.

1. **Mode horaire**

   Les projets Workfront peuvent être planifiés à partir d’une date de début ou d’une date d’achèvement. Cette sélection importante détermine le mode de calcul des dates planifiées de chaque tâche.

   L’option Date de début prend en compte la date de début du projet (que vous avez saisie) ainsi que la durée de chaque tâche et les tâches précédentes pour calculer la date d’achèvement du projet. Workfront recommande d’utiliser cette option, car elle est la plus courante et facilite la planification des dates du projet.

   Toutefois, vous pouvez utiliser une date d’achèvement. Workfront prend en compte la date de fin (saisie par vos soins) et le travail à effectuer (sur la base des durées et des prédécesseurs), puis travaille en amont pour calculer la date de début du projet. Workfront recommande d’attendre d’utiliser la date d’achèvement après l’établissement d’un certain niveau de compétence dans Workfront.

   Quelle que soit l’option choisie, veillez à sélectionner une date dans le calendrier contextuel.

   L’option Mode de planification peut être définie dans le modèle.

1. **Groupe**

   Un groupe est une unité organisationnelle de Workfront qui s’aligne souvent sur un service. Ce champ peut être défini dans le modèle de projet. Si ce n’est pas le cas, le champ est automatiquement défini sur le groupe résidentiel de la personne qui a créé le projet. Vous pouvez modifier le groupe selon vos besoins.

   En général, la plupart des personnes travaillant sur le projet sont issues de ce groupe. Mais cela ne limite pas les personnes d’autres groupes qui se voient attribuer un travail dans le projet.

   Le groupe du projet détermine également les préférences de projet, de tâche et de problème que le projet utilisera. Ces préférences, telles qu’un statut personnalisé pour un groupe spécifique, sont définies par l’administrateur ou l’administratrice système ou un administrateur ou une administratrice de groupes.

   Le paramètre de groupe est un moyen pratique, grâce aux rapports, d’afficher tous les projets sur lesquels travaille un service.

1. **Propriétaire du projet**

   La personne propriétaire du projet est le terme utilisé par Workfront pour désigner la personne chargée de la gestion du projet. Il s’agit de la personne responsable de la planification et/ou de la gestion du projet.

   Pour que la personne propriétaire du projet dispose d’autorisations de gestion complètes pour le projet, elle doit disposer d’une licence Plan.

   Normalement, ce champ est laissé vide dans le modèle et se remplit automatiquement avec le nom de la personne qui crée le projet. Si un nom est saisi dans le modèle, il s’agit de la personne propriétaire par défaut du projet.

1. **Sponsor du projet**

   Le champ de personne sponsor du projet n’est pas obligatoire, mais lorsqu’il est utilisé, il s’agit généralement de la personne qui a demandé le projet. Il s’agit souvent d’une partie prenante interne, comme une personne responsable de la gestion ou cadre, qui doit rendre des comptes à propos du projet.

   La personne sponsor reçoit automatiquement des autorisations d’affichage pour le projet et doit être un utilisateur ou une utilisatrice sous licence Workfront.

   Le sponsor du projet peut être défini dans le modèle.

1. **Gestionnaire des ressources**

   Les utilisateurs et utilisatrices Workfront répertoriés dans ce champ peuvent utiliser les outils de planification et de gestion des ressources de Workfront pour le ou les projets spécifiques sur lesquels ils sont répertoriés. Vous pouvez répertorier jusqu’à 30 noms dans le champ Gestionnaire de ressources. Chacun d’eux doit disposer d’une licence de planification.

   Le champ Gestionnaire de ressources peut être défini dans le modèle.

1. **Formulaires personnalisés**

   Workfront fournit des champs natifs pour des éléments tels que le nom du projet et la date de début. Il existe toutefois d’autres informations dont vous avez besoin en tant que responsable de projet, ou dont l’équipe projet aura besoin. Vos données uniques sont tout aussi importantes et peuvent être stockées facilement dans ces formulaires. Des détails tels que les dates de publication, la taille des ressources imprimées, les canaux de diffusion, etc.

   Les formulaires personnalisés peuvent capturer ces informations et les inclure dans des listes et des rapports dans Workfront, ce qui facilite leur affichage et leur modification.

   Les formulaires personnalisés peuvent être joints à vos modèles à l’avance.

1. **Planning**

   Le travail se fait jour et nuit, car de nombreuses entreprises emploient des personnes dans le monde entier.

   Workfront vous permet d’appliquer un planning commun aux projets. Il est créé par votre administrateur ou administratrice système. Les plannings reflètent les jours et les heures de travail de vos équipes, ainsi que les jours pendant lesquels elles ne travailleront pas (comme les jours fériés).

   En tant que planificateur ou planificatrice, vous devez vous assurer que vous appliquez le bon planning au bon projet. Les paramètres de planification affectent les calculs de la chronologie, en tenant compte des congés et des fuseaux horaires.

   Le planning affecté au projet doit être celui qui s’applique à la majorité des personnes désignées pour les tâches. Si aucun planning n’est spécifié pour le projet, celui désigné par défaut sera utilisé.

   Le planning peut être défini dans le modèle.

1. **Pools de ressources**

   Les groupes de ressources sont des ensembles d’utilisateurs et d’utilisatrices Workfront qui doivent être disponibles au même moment pour réaliser des projets au sein de votre organisation. Un groupe de ressources peut être affecté à plusieurs projets, ce qui signifie que des projets sont en concurrence pour obtenir les ressources.

   L’affectation de groupes de ressources à un projet est une condition préalable à l’utilisation du planificateur de ressources et d’autres outils de gestion des ressources dans Workfront.

   Un groupe de ressources par défaut peut être défini dans le modèle.

1. **Accéder au projet pour les observateurs, observatrices, contributeurs et contributrices**

   Lorsqu’une personne obtient l’accès à un projet par le biais d’un partage, trois niveaux d’autorisations peuvent lui être accordés : Afficher, Contribuer et Gérer. Chaque niveau d’autorisation permet d’afficher et de réaliser certaines actions dans le projet.

   Par exemple, certaines personnes peuvent avoir accès au projet mais ne doivent pas pouvoir consulter les informations financières. Vous pouvez donc désactiver l’option Afficher le financement pour elles.

   Les paramètres d’accès peuvent être définis dans le modèle.

## Tutoriels recommandés sur cette rubrique

* [Comprendre les bases de la création de projets](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/projects/understand-basic-project-creation)
* [Parcourir la page du projet](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/projects/navigate-the-project-page)
* [Découvrir quatre façons de créer un projet](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/projects/understand-other-ways-to-create-projects)
* [Commencer avec la planification d’un projet](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/projects/getting-started-plan-a-project)
