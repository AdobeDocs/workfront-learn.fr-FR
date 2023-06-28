---
title: Entrepôts de données
description: Découvrez comment synchroniser les noms d’entreprise entre deux systèmes. (Doit comporter entre 60 et 160 caractères, mais 59 caractères)
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11055
thumbnail: KT11055.png
exl-id: e4aa9a97-679a-4575-a2c6-b6ac304ce9c2
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '878'
ht-degree: 0%

---

# Entrepôts de données

Découvrez comment synchroniser les noms d’entreprise entre deux systèmes.

## Présentation de l’exercice

Il s’agit de la première partie d’une synchronisation unidirectionnelle des entreprises dans Workfront et d’un autre système. Pour l’instant, il ne se synchronise qu’entre un entrepôt de données Fusion et Workfront. Un tableau d’un entrepôt de données effectue le suivi du Workfront ID (WFID) et de l’ID d’entreprise dans le fichier CSV (CID) pour chaque entreprise. Cela permet une synchronisation bidirectionnelle à un moment ou à un autre.

![Images 1 des entrepôts de données](../12-exercises/assets/data-stores-walkthrough-1.png)

## Étapes à suivre

**Téléchargez le fichier depuis Workfront.**

1. Dans le dossier Workfront &quot;Fusion Exercise Files&quot;, sélectionnez &quot;_Entreprises.csv&quot; et cliquez sur Document Details.
1. Copiez le premier numéro d’identifiant de l’adresse URL.
1. Dans Fusion, créez un scénario appelé &quot;Utilisation des entrepôts de données pour synchroniser les données&quot;.
1. Pour le module de déclenchement, sélectionnez le module Document de téléchargement Workfront.
1. Configurez votre connexion Workfront et incluez l’ID de document copié à partir de l’URL Workfront.
1. Nommez ce module &quot;Get company file&quot; (Obtenir le fichier des entreprises).
1. Ajoutez maintenant un module CSV Parse.
1. Pour le champ Nombre de colonnes , saisissez 2.
1. Mapper les données du module Télécharger le document dans le champ CSV.
1. Nommez ce module &quot;Fichier d’analyse des entreprises&quot;.
1. Enregistrez votre scénario et cliquez sur Exécuter une fois.

   **Créez un entrepôt de données et une structure de données.**

1. Ajoutez un module d’enregistrements de recherche de l’entrepôt de données.
1. Créez un entrepôt de données appelé &quot;Synchronisation des entreprises&quot;.
1. Dans l’entrepôt de données, créez une structure de données nommée &quot;Synchronisation des entreprises (structure)&quot;.
1. Créez quatre champs.

   + CID : ID d’entreprise dans le fichier CSV
   + Nom de la société
   + WFID - ID de société Workfront
   + Date de création - Assurez-vous que le type de données est date

   ![Images 2 des entrepôts de données](../12-exercises/assets/data-stores-walkthrough-2.png)

1. Cliquez sur Enregistrer sur la structure de données, puis définissez la taille de stockage des données sur 1 et enregistrez l’entrepôt de données.
1. Continuez dans le module Data Store , configurez un filtre où l’ID de client est égal à l’ID de la société à partir du module CSV Parse (colonne 1).
1. Cliquez sur Afficher les paramètres avancés et sélectionnez l’option pour &quot;poursuivre l’exécution du scénario ou de l’itinéraire, même si ce module revient sans résultat&quot;.

   ![Images 3 des entrepôts de données](../12-exercises/assets/data-stores-walkthrough-3.png)

1. Renommez ce module &quot;Correspondance avec les entreprises&quot;.
1. Ajoutez un module d’enregistrements de recherche Workfront.
1. Choisissez Société comme type d’enregistrement.
1. Les critères de recherche correspondent au nom de la société dans Workfront, égal au nom de la société dans le fichier CSV.
1. Pour les sorties, sélectionnez le nom de l’entreprise et l’identifiant.

   ![Entrepôts de données Image 4](../12-exercises/assets/data-stores-walkthrough-4.png)

1. Cliquez sur OK et renommez ce module &quot;Sociétés correspondantes&quot;.

   **Créez des chemins d’accès différents selon que l’entreprise existe dans Workfront ou dans l’entrepôt de données.**

   **Chemin de routage 1 - Créez une société.**

1. Ajoutez un module de routeur à droite du module Enregistrements de recherche Workfront .
1. Ajoutez un module Workfront Create Record au chemin supérieur.
1. Définissez le type d’enregistrement sur Société.
1. Sélectionnez Nom dans Champs à mapper. Faites correspondre le champ du nom à la sortie du module Parse CSV (Colonne 2).
1. Renommez ce module &quot;Créer une société&quot;.

   ![Entrepôts de données Image 5](../12-exercises/assets/data-stores-walkthrough-5.png)

1. Ajoutez un filtre après le routeur pour créer une société uniquement si elle n&#39;est pas déjà dans Workfront. Nommez-le &quot;Not in Workfront&quot; (Pas dans).
1. Définissez la condition sur l’ID à partir du module de recherche Workfront et n’existe pas.

   ![Entrepôts de données Image 6](../12-exercises/assets/data-stores-walkthrough-6.png)

   **Préparez-vous à mettre à jour l’entrepôt de données dans le chemin suivant.**

1. Ajoutez un module Définir la variable à la fin du chemin d’accès supérieur.
1. Définissez le nom de la variable sur &quot;Workfront ID&quot;.
1. Définissez la valeur Variable sur l’identifiant à partir du module Créer une société .
1. Renommez ce module &quot;Set Workfront ID&quot; (Définition de l’ID).

   **Chemin de routage 2 - Mettez à jour l’entrepôt de données.**

1. Créez un filtre sur le chemin de routage 2. Nommez-le &quot;Not in data store&quot; (Pas dans l’entrepôt de données).

1. Définissez la condition sur la clé du module Data Store et n’existe pas.

   ![Entrepôts de données Image 7](../12-exercises/assets/data-stores-walkthrough-7.png)

1. Le premier module de ce chemin est le module Get variable.
1. Définissez le nom de la variable sur &quot;Workfront ID&quot;.
1. Renommez ce module &quot;Get Workfront ID&quot;.
1. Ajoutez un autre module de l’application Data Store, ajoutez/remplacez un enregistrement.
1. Dans le champ Entrepôt de données , sélectionnez Synchronisation de l’entreprise. Il s’agit de l’entrepôt de données que vous avez créé précédemment.
1. Laissez le champ Clé vide.
1. Mappez le champ CID de la colonne 1 dans le module CSV Parse.
1. Faites correspondre le champ du nom de l’entreprise de la colonne 2 dans le module Parse CSV.
1. Faites correspondre le champ WFID à partir du module Get Workfront ID.
1. Pour le champ Date de création , utilisez la fonction formatDate de l’onglet Date et heure afin de formater la date actuelle sous la forme MM/JJ/AAAA.

   ![Entrepôts de données Image 8](../12-exercises/assets/data-stores-walkthrough-8.png)

1. Cliquez sur OK et renommez ce module &quot;Créer une entrée d’entreprise&quot;.

   **Chemin de routage 3 - Synchroniser l’entrepôt de données entre les systèmes.**

1. Commencez par créer un filtre sur le chemin de routage 3. Nommez-le &quot;La société existe, pas dans l’entrepôt de données&quot;.
1. Définissez la condition sur la clé à partir du module d’enregistrements de recherche de l’entrepôt de données et n’existe pas.
1. Cliquez sur le bouton Ajouter la règle AND et indiquez que le nom de la société dans le fichier CSV (Colonne 2) est égal au nom de la société trouvée dans le module de recherche Workfront.

   ![Entrepôts de données Image 9](../12-exercises/assets/data-stores-walkthrough-9.png)

1. Ajoutez maintenant un autre module Ajouter/Remplacer un module d’enregistrement en clonant celui à la fin du chemin de routage 2.
1. Faites glisser le module cloné en place à la fin du chemin de routage 3. Supprimez le module vide qui s’y trouvait.
1. Cliquez sur le module cloné. Tous les champs doivent rester identiques, à l’exception du champ WFID . Mappez-le à partir du module Recherche des sociétés correspondantes.

   ![Image 10 des entrepôts de données](../12-exercises/assets/data-stores-walkthrough-10.png)

1. Cliquez sur OK et renommez ce module &quot;Créer une entrée d’entreprise&quot;.
