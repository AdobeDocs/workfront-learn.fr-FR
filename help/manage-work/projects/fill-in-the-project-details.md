---
title: Renseignement des détails du projet
description: Découvrez les 12 champs de détails du projet [!DNL  Workfront] vous recommande de renseigner la variable lors de la création d’un projet.
activity: use
team: Technical Marketing
feature: Work Management
thumbnail: fill-in-the-project-details.jpeg
type: Tutorial
role: User
level: Intermediate
kt: 10140
exl-id: a62b9421-627a-4f23-ab66-da1f29114225
source-git-commit: 58a545120b29a5f492344b89b77235e548e94241
workflow-type: tm+mt
source-wordcount: '1226'
ht-degree: 1%

---

# Renseignement des détails du projet

Ne vous inquiétez pas ... vous n’avez pas à remplir tous les champs et cases à cocher des détails du projet avec chaque projet que vous créez dans [!DNL  Workfront]. Utilisez les modèles pour préremplir les informations, puis ciblez votre attention sur les 12 champs les plus importants de détails du projet répertoriés ci-dessous.

1. **Nom**

   Un nom de projet descriptif permet à chacun d’identifier l’objectif du projet. Veillez à respecter la convention d’affectation des noms de projet de votre entreprise, qui peut nécessiter l’inclusion de certaines informations dans le nom du projet (comme un numéro de référence, un nom de département ou un indicateur de catégorie).

1. **Description**

   Lorsque plusieurs personnes travaillent sur un projet, vous devez, en tant que chef de projet, vous assurer que tout le monde est au courant des objectifs et des attentes du projet.

   Pour ce faire, utilisez une description du projet qui fournit des informations de base, répond à des questions et permet à l’équipe du projet de poursuivre son travail. Par exemple, &quot;Campagne visant à augmenter de 50 % le travail générant des recettes&quot; ou &quot;Nouvelle mise à niveau du système pour améliorer l’efficacité dans l’ensemble du service&quot;.

   Certains clients Workfront incluent un exemple de description d’un projet à l’apparence des modèles de projet.

1. **Statut**

   L’état est utilisé dans Workfront pour indiquer où se trouve, ou à quelle étape, un projet dans le workflow. L’état est utilisé dans de nombreux rapports Workfront pour suivre l’avancement du travail.

   Workfront recommande que l’état soit défini sur Planification pendant que vous effectuez l’analyse et la finalisation du plan du projet. L’élément clé de l’état Planification est que les notifications Workfront ne sont pas envoyées aux personnes désignées pour la tâche concernant le projet tant qu’il est dans cet état.

   Ensuite, une fois que le projet est prêt à être mis en ligne, définissez l’état sur Actuel. C’est alors que Workfront envoie des notifications aux personnes appropriées concernant les tâches auxquelles elles ont été affectées.

   >[!TIP]
   >
   >  Lorsque vous apportez des modifications au projet (par exemple, en modifiant les dates d’échéance), vous pouvez restaurer l’état dans Planification ou désactiver la fonction d’enregistrement automatique pour empêcher les notifications d’être envoyées jusqu’à la fin des modifications.

   L’état Planification peut être défini comme valeur par défaut de Workfront globale par votre administrateur système.

1. **Mode horaire**

   Les projets Workfront peuvent être planifiés à partir d’une date de début ou d’achèvement. Cette sélection importante détermine le mode de calcul des dates planifiées de chaque tâche.

   L’option Date de début prend la date de début du projet (que vous avez saisie) et la durée et les prédécesseurs de chaque tâche à calculer quand le projet se terminera. Workfront recommande d’utiliser cette option, car elle est la plus courante et facilite la planification des dates des projets.

   Vous pouvez toutefois utiliser une date de fin. Workfront examine la date de fin (saisie par vous) et le travail à faire (en fonction des durées et des prédécesseurs), puis fait marche arrière pour calculer la date de début du projet. Workfront recommande d’attendre d’utiliser la date d’achèvement après l’établissement d’un certain niveau de compétence dans Workfront.

   Quelle que soit l’option choisie, veillez à sélectionner une date dans le calendrier contextuel.

   L’option Mode de planification peut être définie dans le modèle.

1. **Groupe**

   Un groupe est une entité organisationnelle Workfront qui s’aligne souvent sur un service. Ce champ peut être défini sur le modèle de projet. Si ce n’est pas le cas, le champ est automatiquement défini sur le Groupe d’accueil de la personne qui crée le projet. Vous pouvez modifier le groupe selon vos besoins.

   En général, la plupart des personnes qui travaillent sur le projet viennent de ce groupe. Mais cela ne limite pas les personnes d&#39;autres groupes qui se voient attribuer un travail dans le projet.

   Le groupe sur le projet détermine également le projet, la tâche et les préférences d’émission que le projet utilisera. Ces préférences, telles qu’un état personnalisé pour un groupe spécifique, sont définies par l’administrateur système ou un administrateur de groupe.

   Le paramètre de groupe est un moyen pratique, grâce aux rapports, d’afficher tous les projets sur lesquels travaille un service.

1. **Propriétaire du projet**

   Le propriétaire du projet est le terme utilisé par Workfront pour désigner le chef de projet. Il s’agit de la personne responsable de la planification et/ou de la gestion du projet.

   Le propriétaire du projet dispose d’autorisations de gestion complètes pour le projet. Il doit donc disposer d’une licence Plan .

   Normalement, ce champ n’est pas renseigné dans le modèle et il est automatiquement renseigné avec le nom de la personne qui crée le projet. Si un nom est saisi dans le modèle, il s’agit du propriétaire par défaut du projet.

1. **Sponsor du projet**

   Le parrain du projet est généralement la personne qui a demandé le projet. Il s’agit souvent d’une partie prenante à l’interne, comme un responsable ou un cadre exécutif, qui doit rendre des comptes au projet.

   Le sponsor reçoit automatiquement des autorisations d’affichage pour le projet et doit être un utilisateur sous licence Workfront.

   Le parrain du projet peut être défini dans le modèle.

1. **Gestionnaire des ressources**

   Les utilisateurs de Workfront répertoriés dans ce champ peuvent utiliser les outils de planification et de gestion des ressources de Workfront pour les projets spécifiques sur lesquels ils sont répertoriés. Vous pouvez répertorier jusqu’à 30 noms dans le champ Gestionnaire de ressources . Chacun d’eux doit disposer d’une licence Plan .

   Le champ Gestionnaire de ressources peut être défini dans le modèle.

1. **Formulaires personnalisés**

   Workfront fournit des champs natifs pour des éléments tels que le nom du projet et la date de début. Il existe toutefois des informations supplémentaires dont vous avez besoin en tant que chef de projet ou dont l’équipe aura besoin. Vos données uniques sont tout aussi importantes et peuvent facilement être stockées sous ces formes. Détails tels que les dates de publication, la taille des ressources imprimées, les canaux de diffusion, etc.

   Les formulaires personnalisés peuvent capturer ces informations et les inclure dans des listes et des rapports dans Workfront, ce qui facilite l’affichage et la modification des informations.

   Des formulaires personnalisés peuvent être joints à vos modèles à l’avance.

1. **Planification**

   Le travail se fait jour et nuit, car de nombreuses entreprises ont des employés dans le monde entier.

   Workfront vous permet d’appliquer un planning commun aux projets. Ils sont créés par votre administrateur système. Les plannings reflètent les jours de travail et les heures de travail de votre équipe, ainsi que les jours pendant lesquels les employés ne travailleront pas (comme les jours fériés).

   En tant que planificateur, assurez-vous d’appliquer le bon planning au bon projet. Les paramètres de planification affectent les calculs de la chronologie, en prenant en compte les décalages horaires et les fuseaux horaires.

   Le planning affecté au projet doit être celui qui s’applique à la majorité des personnes désignées pour la tâche. Si aucune planification n’est spécifiée pour le projet, la planification marquée comme Par défaut sera utilisée.

   Le planning peut être défini dans le modèle.

1. **Pools de ressources**

   Les pools de ressources sont des groupes d’utilisateurs Workfront qui sont nécessaires simultanément pour terminer des projets au sein de votre organisation. Un pool de ressources peut être affecté à plusieurs projets, ce qui signifie que des projets sont en compétition pour les ressources.

   L’affectation de pools de ressources à un projet est une condition préalable à l’utilisation du planificateur de ressources et d’autres outils de gestion des ressources dans Workfront.

   Un pool de ressources par défaut peut être défini dans le modèle.

1. **Accès au projet pour les visionneuses et les contributeurs**

   Lorsqu’une personne a accès à un projet, trois niveaux d’autorisations peuvent initialement être accordés lorsqu’un projet est mis en ligne : Affichage, Contribution et Gestion. Chaque niveau d’autorisation permet à l’utilisateur d’afficher et de réaliser certaines actions avec le projet.

   Par exemple, certaines personnes peuvent avoir accès au projet, mais ne devraient pas voir les informations financières. Vous pouvez donc désactiver l’option Afficher le financement pour les observateurs et les contributeurs.

   Vous pouvez affiner à tout moment ces paramètres d’autorisation sur des projets individuels. Cependant, une fois qu’un projet est passé de l’état Planification à l’état actuel, les ajustements basés sur les autorisations doivent être effectués par le biais du partage du projet.

   Les paramètres d’accès peuvent être définis dans le modèle.
