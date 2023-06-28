---
title: Utilisation de JSON
description: Découvrez comment créer et analyser JSON dans un scénario pour prendre en charge vos besoins en matière de conception.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-11056
thumbnail: KT11056.png
exl-id: 72d5159e-72e5-4202-90de-753b3d7626de
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '485'
ht-degree: 0%

---

# Utilisation de JSON

Découvrez comment créer et analyser JSON dans un scénario pour prendre en charge vos besoins en matière de conception.

## Présentation de l’exercice

L’objectif de cet exercice est d’expliquer comment utiliser les informations envoyées dans un scénario au format JSON, en les analysant dans des champs et des éléments que vous pouvez mapper tout au long de votre scénario. Vous pouvez ensuite extraire des informations de ces tableaux mappés ou les regrouper dans JSON pour les envoyer ensuite à un autre système qui attend JSON comme entrée de réception.

![Utilisation de json Image 1](../12-exercises/assets/working-with-json-walkthrough-1.png)

## Étapes à suivre

**Créez une structure de données et analysez JSON.**

1. Créez un scénario et nommez-le &quot;Utilisation des données JSON en anneau&quot;.
1. Pour le module déclencheur, utilisez le module Définir la variable .
1. Pour le nom de la variable, saisissez &quot;Données en anneau&quot;.
1. Pour la valeur Variable , copiez et collez le contenu du document &quot;_Donut Data - Sample JSON.rtf&quot; figurant dans le dossier Fusion Exercise Files de votre lecteur de test.

   ![Utilisation de json Image 2](../12-exercises/assets/working-with-json-walkthrough-2.png)

1. Renommez ce module &quot;JSON à partir d’un autre connecteur&quot;.
1. Ajoutez un module JSON d’analyse.
1. Cliquez sur Ajouter pour le champ Structure de données .
1. Sélectionnez le générateur et collez les données Anneau - Exemple de données JSON copiées dans le champ Exemple de données .

   ![Utilisation de json Image 3](../12-exercises/assets/working-with-json-walkthrough-3.png)

1. Cliquez sur Enregistrer, en nommant la structure de données &quot;Données en anneau&quot;. Cliquez ensuite sur Enregistrer.
1. Faites correspondre les données Anneau du module Définir la variable au champ de chaîne JSON.

   ![Utilisation de json Image 4](../12-exercises/assets/working-with-json-walkthrough-4.png)

1. Enregistrez votre scénario, puis cliquez sur Exécuter une fois pour afficher la sortie.

   **La sortie du module JSON d’analyse doit se présenter comme suit :**

   ![Utilisation de json Image 5](../12-exercises/assets/working-with-json-walkthrough-5.png)

   **Associer à des variables de tableau spécifiques.**

1. Ajoutez un routeur après le module JSON d’analyse.
1. Dans le chemin supérieur, ajoutez un module Définir la variable .
1. Pour le nom de la variable, saisissez &quot;Types de lot par beignet&quot;.
1. Pour la valeur Variable , utilisez la fonction map pour obtenir les types de lots du tableau batters .

   ![Utilisation de json Image 6](../12-exercises/assets/working-with-json-walkthrough-6.png)

1. Cliquez sur OK, puis Exécuter une fois.
1. Ouvrez l’Inspecteur d’exécution pour afficher le lot de sortie pour chacune des trois opérations, en indiquant les types de batteur pour chacune d’elles.

   ![Utilisation de json Image 7](../12-exercises/assets/working-with-json-walkthrough-7.png)

   **Agrégez les données de scénario avec JSON.**

1. Sur le chemin de routage inférieur, ajoutez un agrégat au module JSON.
1. Pour le module source, sélectionnez l’itérateur : module Parse JSON.
1. Pour la structure de données, créez ou sélectionnez une structure de données. Pour cet exemple, utilisez Données en anneau .
1. Faites une mise en correspondance directe des champs pour cet exemple, comme illustré ci-dessous.
1. Lorsque vous accédez au traitement par lot et au recadrage, notez qu’il s’agit de tableaux. Vous devez donc cliquer sur Ajouter un élément pour les mapper.

   ![Utilisation de json Image 8](../12-exercises/assets/working-with-json-walkthrough-8.png)

1. Enregistrez le scénario et cliquez sur Exécuter une fois.

Examinez l’Inspecteur d’exécution pour le module Agrégat vers JSON et observez comment vous avez pu regrouper trois lots en une seule chaîne JSON. Vous pouvez ensuite envoyer cette chaîne à d’autres systèmes qui attendent JSON.

![Utilisation de json Image 9](../12-exercises/assets/working-with-json-walkthrough-9.png)
