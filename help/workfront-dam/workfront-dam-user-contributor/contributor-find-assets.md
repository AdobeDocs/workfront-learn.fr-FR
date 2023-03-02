---
title: Recherche et organisation de ressources dans [!UICONTROL Gestion des actifs numériques Workfront]
description: Découvrez comment rechercher des ressources, effectuer des recherches dans des dossiers, rationaliser les résultats de recherche, utiliser des métadonnées et des mots-clés comme filtres de recherche, etc. dans [!UICONTROL Gestion des actifs numériques Workfront].
activity: use
feature: Digital Content and Documents
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
kt: 8993
exl-id: 28b60118-a471-48bf-ae9b-3a2aed6a6130
doc-type: video
source-git-commit: d39754b619e526e1a869deedb38dd2f2b43aee57
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 0%

---

# Contributeur : recherche de ressources

Dans cette vidéo, vous apprendrez à :

* Recherche de ressources
* Recherche dans les dossiers
* Rationalisation des résultats de recherche
* Utilisation de métadonnées et de mots-clés comme filtres de recherche
* Afficher les détails du dossier
* Affichage et mise à jour des métadonnées et des mots-clés des ressources

>[!VIDEO](https://video.tv.adobe.com/v/335253/?quality=12)

## Critères de recherche de base

Une recherche de base porte sur les noms de fichier, les champs de métadonnées, les mots-clés et le contenu de la ressource (selon le type de ressource). Il n’inclut pas le nom du dossier.

La plupart des résultats de recherche correspondent exactement. Une exception à cette règle de &quot;correspondance exacte&quot; est lorsque la variable [!UICONTROL Gestion des actifs numériques Workfront] recherche le champ du nom de fichier. [!UICONTROL Gestion des actifs numériques Workfront] renvoie des correspondances de nom de fichier partielles, plutôt que des correspondances exactes.

## Opérateurs utilisateur lors de la recherche

Bien que les fonctions de recherche de base trouvent souvent les ressources dont vous avez besoin, vous devrez peut-être utiliser des paramètres de recherche supplémentaires de temps à autre.

### Correspondances partielles

Pour rechercher une correspondance partielle, ajoutez un astérisque au terme recherché. L’astérisque ne peut être utilisé qu’à la fin d’un mot.

### Opérateur ET

Pour rechercher des résultats contenant plusieurs termes de recherche, saisissez ET entre les mots. Les mots se trouvent dans n&#39;importe quel ordre. Lors de la recherche dans tous les champs, il se peut que les deux mots ne figurent pas dans le même champ. Par exemple, Paris ET la tour trouveront des ressources ayant ces deux mots dans l’un des champs.

### Opérateur OU

Utilisez l’opérateur OU pour rechercher les ressources qui contiennent l’un des termes de recherche. Par exemple, Paris OU Arc trouvera des ressources qui contiennent l’un des mots, mais pas nécessairement les deux.

### Expression

Pour trouver une expression exacte, utilisez des guillemets doubles. Tous les mots seront réunis et ordonnés. Par exemple, &quot;Tour Eiffel&quot; trouvera ces mots dans cet ordre exact.

### Opérateur négatif

Si vous souhaitez exclure un mot des résultats de la recherche, placez un signe moins (-) devant le mot. Assurez-vous qu’il n’y a pas d’espace entre le signe moins et le mot. Par exemple, pour exclure les ressources dont les métadonnées contiennent le mot &quot;tour&quot;, votre recherche peut être configurée en tant que tour Paris.

### Opérateur de champ vide

Pour rechercher des ressources qui ne contiennent pas d’informations dans un champ de métadonnées spécifique, saisissez le champ à rechercher dans ce format : ?[xxxxx]. Par exemple, si vous souhaitez rechercher des ressources pour lesquelles des mots-clés ne sont pas affectés, saisissez ?[keyword] dans le champ de recherche.
