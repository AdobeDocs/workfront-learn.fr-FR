---
title: Outil de développement
description: Améliorez vos capacités de dépannage d’un scénario et simplifiez les configurations complexes à l’aide de DevTool.
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
kt: 11057
thumbnail: KT11057.png
exl-id: 13080212-26cf-4e5f-8f0b-fc59a6f66eb1
source-git-commit: 58a545120b29a5f492344b89b77235e548e94241
workflow-type: tm+mt
source-wordcount: '616'
ht-degree: 0%

---

# Outil de développement

Améliorez vos capacités de dépannage d’un scénario et simplifiez les configurations complexes à l’aide de l’outil de développement.

## Présentation de l’exercice

Installez et utilisez les différentes zones de l’outil de développement Workfront pour approfondir l’analyse des requêtes/réponses effectuées et des astuces de conception de scénario avancées.

>[!NOTE]
>
>L’outil de développement de fusion Workfront n’est disponible que dans le navigateur Chrome lors de l’utilisation de la fonction [Outil de développement Chrome](https://developer.chrome.com/docs/devtools/).

![Image de Devtool 1](../12-exercises/assets/devtool-walkthrough-1.png)

## Étapes à suivre

**Installez l’outil de développement.**

1. Téléchargez le document &quot;workfront-fusion-devtool.zip&quot; qui se trouve dans le dossier Fusion Exercise Files du lecteur de test.
1. Extrayez les fichiers Zip dans un dossier.
1. Ouvrez un onglet dans Chrome et saisissez **chrome://extensions**.
1. Activez le mode Développeur à l’aide du commutateur en haut à droite, puis cliquez sur le bouton &quot;Charger les fichiers décompressés&quot; qui s’affiche en haut à gauche. Sélectionnez le dossier contenant l’outil de développement (c’est là que vous l’avez décompressé).

   ![Image du périphérique 2](../12-exercises/assets/devtool-walkthrough-2.png)

1. Une fois décompressé, l’outil de développement apparaît parmi vos autres extensions.

   ![Image de Devtool 3](../12-exercises/assets/devtool-walkthrough-3.png)

   **Utilisez le Live Stream.**

1. Commencez par ouvrir le scénario &quot;Utilisation des entrepôts de données pour synchroniser les données&quot;.
1. Ouvrez l’outil de développement en saisissant F12 ou la fonction F12. Vous pouvez également cliquer sur le menu à trois points dans la barre d’adresse de Chrome et accéder aux outils de développement.

   ![Image de Devtool 4](../12-exercises/assets/navigate-to-devtools.png)

1. Cliquez sur l’onglet Fusion Workfront , puis sélectionnez Diffusion en direct dans la liste de gauche.
1. Cliquez une fois sur Exécuter pour afficher les événements tels qu’ils se produisent.
1. Cliquez sur un événement pour afficher les onglets situés à droite des sections En-têtes de requête, Corps de requête, En-têtes de réponse et Corps de réponse.

   ![Image de Devtool 4](../12-exercises/assets/devtool-walkthrough-4.png)

   **Utilisation du débogueur de scénario**

1. Sélectionnez Débogueur de scénario et cliquez sur un module pour afficher des informations sur les opérations de ce module.

   ![Image Devtool 5](../12-exercises/assets/devtool-walkthrough-5.png)

1. Accédez à l’onglet Historique . Cliquez sur Détails sur une exécution pour examiner les détails de l’opération de module pour une exécution spécifique.

   ![Devtool Image 6](../12-exercises/assets/devtool-walkthrough-6.png)

   **Utilisation des outils**

1. Revenez au concepteur de scénarios et sélectionnez Outils dans l’outil de développement. Cette option affiche les outils disponibles.

   ![Devtool Image 7](../12-exercises/assets/devtool-walkthrough-7.png)

+ Mise au point d’un module : recherchez et ouvrez rapidement un module à l’aide de l’identifiant de module.
+ Rechercher un ou plusieurs modules par mappage : recherchez un scénario à l’aide d’un mot-clé pour trouver des valeurs et/ou des clés mappées dans les modules.
+ Obtenir les métadonnées de l’application : reportez-vous aux métadonnées de l’application sélectionnée dans un scénario.
+ Copier le mappage : copie le mappage d’un module à un autre. Vous pouvez également cloner le module dans le concepteur.
+ Copier le filtre : copie un filtre. Le filtre est toujours affecté au module à droite.
+ Permuter la connexion : l’outil récupère la connexion du module sélectionné et définit la même connexion à tous les modules de la même application dans le scénario. Cela s’avère utile si vous devez modifier la connexion tout au long d’un scénario terminé. Évitez de perdre tous les mappages et gagnez du temps en utilisant cet outil.
+ Variable de permutation : recherche toutes les occurrences de la variable donnée dans l’ensemble du scénario ou dans un module, et les remplace par le nouveau. Les caractères génériques ne sont pas pris en charge. Si vous avez mappé accidentellement une valeur sur l’ensemble du scénario, cela peut vous aider à permuter facilement la valeur correcte.
+ Permuter l’application : échange l’application donnée pour une autre.
+ Base 64 - Codez les données saisies dans Base64 ou décodez Base64. Utile lorsque vous souhaitez rechercher des données spécifiques dans la requête codée.
+ Copier le nom du module : copie le nom du module sélectionné dans le Presse-papiers.
+ Remap Source : modifiez la source de mappage d’un module à un autre. Vous devez d’abord ajouter le module à utiliser comme module source à l’itinéraire dans un scénario.
+ Migration du système d’exploitation : réalisé spécifiquement pour mettre à niveau les modules Google Sheets (hérités) vers la dernière version de Google Sheets. Il ajoute une nouvelle version du module juste après la version héritée du module dans l’itinéraire du scénario.
