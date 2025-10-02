---
title: Comprendre la recherche de ressources en tant que contributeur ou contributrice
description: Découvrez comment rechercher des ressources, effectuer des recherches dans des dossiers, optimiser les résultats de recherche, utiliser des métadonnées et des mots-clés comme filtres de recherche dans [!UICONTROL Workfront DAM].
activity: use
feature: Digital Content and Documents
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
jira: KT-8993
exl-id: 28b60118-a471-48bf-ae9b-3a2aed6a6130
doc-type: video
source-git-commit: bbdf99c6bc1be714077fd94fc3f8325394de36b3
workflow-type: tm+mt
source-wordcount: '407'
ht-degree: 100%

---

# Comprendre la recherche de ressources en tant que contributeur ou contributrice

Dans cette vidéo, vous apprendrez à :

* Rechercher des ressources
* Effectuer des recherches dans des dossiers
* Optimiser les résultats de recherche
* Utiliser les métadonnées et les mots-clés comme filtres de recherche
* Visualiser les détails d’un dossier
* Visualiser et mettre à jour les métadonnées et les mots-clés des ressources

>[!VIDEO](https://video.tv.adobe.com/v/3453921/?quality=12&learn=on&enablevpops=1&captions=fre_fr)

## Critères de recherche de base

Une recherche de base porte sur les noms de fichiers, les champs de métadonnées, les mots-clés et le contenu de la ressource (en fonction du type de ressource). Elle n’inclut pas le nom du dossier.

La plupart des résultats de recherche sont des correspondances exactes. Il existe une exception à cette règle de « correspondance exacte » lorsque [!UICONTROL Workfront DAM] effectue une recherche portant sur le champ du nom de fichier. [!UICONTROL Workfront DAM] renvoie des correspondances partielles de noms de fichiers, plutôt que des correspondances exactes.

## Opérateurs d’utilisateur ou d’utilisatrice lors d’une recherche

Bien que les fonctions de recherche de base permettent souvent de trouver les ressources dont vous avez besoin, vous devrez peut-être utiliser des paramètres de recherche supplémentaires de temps à autre.

### Correspondances partielles

Pour trouver une correspondance partielle, ajoutez un astérisque au terme de recherche. L’astérisque ne peut être utilisé qu’à la fin d’un mot.

### Opérateur AND

Pour obtenir des résultats contenant plusieurs termes de recherche, saisissez AND entre les mots. Les mots peuvent être trouvés dans n’importe quel ordre. Lors d’une recherche dans tous les champs, les deux mots peuvent ne pas être présents dans le même champ. Par exemple, « Paris AND tour » permet de trouver des ressources contenant ces deux mots dans l’un ou l’autre des champs.

### Opérateur OR

Utilisez l’opérateur OR pour trouver les ressources qui contiennent l’un des termes de recherche. Par exemple, « Paris OR Arc » donnera des ressources contenant l’un ou l’autre de ces mots, mais pas nécessairement les deux.

### Expression

Pour trouver une expression exacte, utilisez des guillemets doubles autour des mots. Tous les mots seront trouvés ensemble et dans l’ordre. Par exemple, « Tour Eiffel » donnera ces mots dans l’ordre exact.

### Opérateur négatif

Si vous souhaitez exclure un mot des résultats de la recherche, placez le signe moins (-) devant le mot à exclure. Veillez à ce qu’il n’y ait pas d&#39;espace entre le signe moins et le mot. Par exemple, pour exclure les ressources dont les métadonnées contiennent le mot « tour », votre recherche peut être définie comme « Paris -tour ».

### Opérateur de champ vide

Pour trouver des ressources qui ne contiennent aucune information dans un champ de métadonnées spécifique, saisissez le champ à rechercher dans ce format : ?[xxxxx]. Par exemple, si vous souhaitez rechercher des ressources auxquelles aucun mot-clé n’a été attribué, saisissez ?[mot-clé] dans le champ de recherche.
