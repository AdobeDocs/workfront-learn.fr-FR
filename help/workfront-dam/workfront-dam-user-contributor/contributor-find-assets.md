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
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
autotag-review: '2026-05-05T20:25:54.114Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 407
ht-degree: 89%

---

# Comprendre la recherche de ressources en tant que contributeur ou contributrice

Dans cette vidéo, vous apprendrez à :

* Rechercher des ressources
* Effectuer des recherches dans des dossiers
* Optimiser les résultats de recherche
* Utiliser les métadonnées et les mots-clés comme filtres de recherche
* Visualiser les détails d’un dossier
* Visualiser et mettre à jour les métadonnées et les mots-clés des ressources

>[!VIDEO](https://video.tv.adobe.com/v/335253/?quality=12&learn=on&enablevpops=1)

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

Pour rechercher des ressources qui ne contiennent aucune information dans un champ de métadonnées spécifique, saisissez le champ à rechercher au format suivant : ?[xxxxx]. Par exemple, si vous souhaitez rechercher des ressources auxquelles aucun mot-clé n’est affecté, saisissez ?[mot-clé] dans le champ de recherche.
