---
title: Créer des instructions OR dans les filtres
description: La logique de filtre flexible de Workfront permet aux utilisateurs et utilisatrices d’affiner les vues de rapports à l’aide des règles « AND » par défaut, des conditions « OR » facultatives et des groupes de filtres organisés pour des critères complexes.
activity: use
team: Technical Marketing
feature: Reports and Dashboards
thumbnail: create-or-statements-in-filters.png
type: Tutorial
role: User
level: Intermediate
jira: KT-9987
exl-id: 1a56f2f6-12df-43a5-943c-986a85661efa
last-substantial-update: '2025-08-11T00:00:00.000Z'
doc-type: video
product_v2: id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2: id: c6dd2ac5-f5bd-4e59-9101-25b156918623
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: b5a62a22-46f7-4f0d-b151-3fc640bef588
autotag-review: '2026-05-06T02:11:54.379Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 318
ht-degree: 65%

---

# Créer des instructions OR dans les filtres

La vidéo explique comment créer et utiliser des filtres avec plusieurs règles dans Workfront. &#x200B; Par défaut, Workfront utilise « AND » entre les règles de filtrage, ce qui signifie que toutes les conditions doivent être vraies pour qu’un élément apparaisse dans la liste.
Vous pouvez également remplacer la logique de filtre par « OU », qui affiche les éléments qui répondent à l’une des conditions.
La vidéo illustre également la création de filtres pour les tâches à l’aide de groupes de filtres. &#x200B; Par exemple, vous pouvez créer deux groupes : un pour les tâches incomplètes affectées en retard à l’équipe créative et un autre pour les tâches incomplètes affectées à l’équipe créative qui ne sont pas affectées. &#x200B; Au sein de chaque groupe, la logique « AND » s’applique, ce qui signifie que toutes les conditions du groupe doivent être remplies. &#x200B; La logique « OR » entre les groupes garantit l’affichage des tâches répondant aux conditions de l’un ou l’autre groupe.

>[!VIDEO](https://video.tv.adobe.com/v/3470692/?quality=12&learn=on&enablevpops=0)

## Activité du filtre OR

Vous voulez trouver les tâches incomplètes qui vous sont attribuées ou qui ne sont attribuées à personne. Vous configurez un filtre qui ressemble à celui présenté ci-dessous. Ce filtre vous donnera-t-il les résultats que vous souhaitez ? Pourquoi ou pourquoi pas ?

![Image d’une instruction OR créée de manière incorrecte dans [!DNL Workfront]](assets/or-statement-your-turn-1.png)

### Réponses

Non, ce filtre ne fournira pas les résultats que vous espérez (les tâches non terminées qui vous sont affectées ou qui ne sont affectées à personne) parce que la règle de filtrage pour l’achèvement de la tâche ne concerne qu’un seul aspect de l’instruction OR.

Au lieu de cela, ce filtre génère une liste qui indique ce qui suit :

* Les tâches qui vous sont affectées et qui ne sont pas terminées.
* **PLUS (OR)**
* Toutes les tâches non assignées, quel que soit leur statut.

Le filtre doit ressembler à l’illustration ci-dessous. Remarquez que ce filtre comporte la règle de filtrage de l’achèvement de la tâche des deux aspects de l’instruction OR.

![Image d’une instruction OR correctement créée dans [!DNL Workfront]](assets/or-statement-your-turn-2.png)
