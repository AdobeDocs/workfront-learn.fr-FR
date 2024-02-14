---
title: Exercice Entrepôts de données
description: Découvrez comment synchroniser des noms d’entreprise entre deux systèmes. (Doit comporter entre 60 et 160 caractères, mais comporte 59 caractères)
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11055
thumbnail: KT11055.png
recommendations: noDisplay,noCatalog
exl-id: e4aa9a97-679a-4575-a2c6-b6ac304ce9c2
source-git-commit: a4e61514567ac8c2b4ad5c9ecacb87bd83947731
workflow-type: tm+mt
source-wordcount: '904'
ht-degree: 99%

---

# Exercice Entrepôts de données

Découvrez comment synchroniser des noms d’entreprise entre deux systèmes.

## Vue d’ensemble de l’exercice

Il s’agit de la première partie d’une synchronisation unidirectionnelle d’entreprises dans Workfront avec un autre système. Pour l’instant, la synchronisation ne se fait qu’entre un magasin de données Fusion et Workfront. Une table dans un magasin de données conserve l&#39;identifiant Workfront (WFID) et l’identifiant d’entreprise dans le fichier CSV (CID) pour chaque entreprise. Cela permet une éventuelle synchronisation bidirectionnelle ultérieure.

![Image 1 - Magasins de données](../12-exercises/assets/data-stores-walkthrough-1.png)

## Étapes à suivre

**Téléchargez le fichier à partir de Workfront.**

1. Dans le dossier Workfront « Fusion Exercise Files », sélectionnez « _Entreprises.csv » et cliquez sur Détails du document.
1. Copiez le premier numéro d’identifiant de l’adresse URL.
1. Dans Fusion, créez un scénario nommé « Utilisation des magasins de données pour synchroniser les données ».
1. Pour le module de déclenchement, sélectionnez le module de téléchargement de document Workfront.
1. Configurez votre connexion Workfront et incluez l’ID de document copié à partir de l’URL Workfront.
1. Nommez ce module « Obtenir le fichier des entreprises ».
1. Ajoutez un module d’analyse CSV.
1. Dans le champ Nombre de colonnes, saisissez 2.
1. Mappez les données du module de téléchargement de document dans le champ CSV.
1. Nommez ce module « Analyse du fichier des entreprises ».
1. Enregistrez votre scénario et cliquez sur Exécuter une fois.

   **Créez un magasin de données et une structure de données.**

1. Ajoutez un module d’enregistrement des recherches d’un magasin de données.
1. Créez un magasin de données nommé « Synchronisation de l’entreprise ».
1. Dans le magasin de données, créez une structure de données nommée « Synchronisation de l’entreprise (structure) ».
1. Créez quatre champs.

   + CID : ID d’entreprise dans le fichier CSV
   + Nom de l’entreprise
   + WFID : Identifiant Workfront de l’entreprise
   + Date de création : assurez-vous que le type de données est « date »

   ![Image 2 - Magasins de données](../12-exercises/assets/data-stores-walkthrough-2.png)

1. Cliquez sur Enregistrer sur la structure de données, puis définissez la taille de stockage des données sur 1 et enregistrez le magasin de données.
1. Toujours dans le module Magasin de données, configurez un filtre dans lequel le CID est égal à l’ID de l’entreprise à partir du module Analyse CSV (colonne 1).
1. Cliquez sur Afficher les paramètres avancés et sélectionnez l’option « Poursuivre l’exécution du scénario ou de l’itinéraire, même si ce module ne renvoie aucun résultat ».

   ![Image 3 - Magasins de données](../12-exercises/assets/data-stores-walkthrough-3.png)

1. Renommez ce module « Entreprises correspondantes ».
1. Ajoutez un module d’enregistrements des recherches Workfront.
1. Choisissez Entreprise comme type d’enregistrement.
1. Les critères de recherche correspondent au nom de l’entreprise dans Workfront, qui est égal au nom de l’entreprise dans le fichier CSV.
1. Pour les sorties, sélectionnez le nom de l’entreprise et l’identifiant.

   ![Image 4 - Magasins de données](../12-exercises/assets/data-stores-walkthrough-4.png)

1. Cliquez sur OK et renommez ce module « Entreprises correspondantes ».

   **Créez des chemins différents selon que l’entreprise existe dans Workfront ou dans le magasin de données.**

   **Chemin de routage 1 - Créer une entreprise.**

1. Ajoutez un module de routeur à droite du module d’enregistrements des recherches Workfront.
1. Ajoutez un module de création d’enregistrement Workfront au chemin supérieur.
1. Définissez le type d’enregistrement sur Entreprise.
1. Sélectionnez Nom dans Champs à mapper. Mappez le champ du nom à la sortie du module d’analyse CSV (colonne 2).
1. Renommez ce module « Créer une entreprise ».

   ![Image 5 - Magasins de données](../12-exercises/assets/data-stores-walkthrough-5.png)

1. Ajoutez un filtre après le routeur pour ne créer une entreprise que si elle n’est pas déjà présente dans Workfront. Nommez-le « Pas dans Workfront ».
1. Définissez la condition sur l’ID issu du module de recherche Workfront, et sur « n’existe pas ».

   ![Magasins de données - Image 6](../12-exercises/assets/data-stores-walkthrough-6.png)

   **Préparez-vous à mettre à jour le magasin de données dans le chemin suivant.**

1. Ajoutez un module Définir la variable à la fin du chemin d’accès supérieur.
1. Définissez le nom de la variable sur « Workfront ID ».
1. Définissez la valeur de la variable sur l’ID issu du module Créer une entreprise.
1. Renommez ce module « Définir le Workfront ID ».

   **Chemin de routage 2 - Mise à jour du magasin de données.**

1. Créez un filtre sur le chemin de routage 2. Nommez-le « Pas dans le magasin de données ».

1. Définissez la Condition sur la Clé du module Magasin de données, et sur « n’existe pas ».

   ![Magasins de données - Image 7](../12-exercises/assets/data-stores-walkthrough-7.png)

1. Le premier module de ce chemin est le module Obtenir une variable.
1. Définissez le nom de la variable sur « Workfront ID ».
1. Renommez ce module « Obtenir le Workfront ID ».
1. Ajoutez un autre module issu de l’application du Magasin de données : Ajouter/remplacer un enregistrement.
1. Dans le champ Magasin de données, sélectionnez Synchronisation de l’entreprise. Il s’agit du magasin de données que vous avez créé précédemment.
1. Laissez le champ Clé vide.
1. Mappez le champ CID de la colonne 1 sur le module Analyse CSV.
1. Mappez le champ du nom de l’entreprise de la colonne 2 sur le module Analyse CSV.
1. Mappez le champ WFID du module Obtenir le Workfront ID.
1. Pour le champ Date de création, utilisez la fonction formatDate de l’onglet Date et heure afin de définir le format de la date actuelle sur MM/JJ/AAAA.

   ![Magasins de données - Image 8](../12-exercises/assets/data-stores-walkthrough-8.png)

1. Cliquez sur OK et renommez ce module « Créer une entrée d’entreprise ».

   **Chemin de routage 3 - Synchronisation du magasin de données entre les systèmes.**

1. Commencez par créer un filtre sur le chemin de routage 3. Nommez-le « entreprise existante, pas présente dans le magasin de données ».
1. Définissez la condition sur la clé issue du module de recherche d’enregistrements du magasin de données, et sur « n’existe pas ».
1. Cliquez sur le bouton Ajouter une règle AND et indiquez que le nom de l’entreprise issu du fichier CSV (Colonne 2) est égal au nom de l’entreprise présent dans le module de recherche Workfront.

   ![Magasins de données - Image 9](../12-exercises/assets/data-stores-walkthrough-9.png)

1. Ajoutez maintenant un autre module Ajouter/Remplacer un enregistrement, en clonant celui se trouvant à la fin du chemin de routage 2.
1. Faites glisser le module cloné jusqu’à la fin du chemin de routage 3. Supprimez le module vide qui s’y trouvait.
1. Cliquez sur le module cloné. Tous les champs doivent rester inchangés, à l’exception du champ WFID. Mappez-le à partir du module Recherche des entreprises correspondantes.

   ![Magasins de données - Image 10](../12-exercises/assets/data-stores-walkthrough-10.png)

1. Cliquez sur OK et renommez ce module « Créer une entrée d’entreprise ».
