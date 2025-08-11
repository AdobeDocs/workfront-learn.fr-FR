---
title: Créer des instructions OR dans les filtres
description: La logique de filtre flexible de Workfront permet aux utilisateurs d’affiner les vues de rapports à l’aide des règles « AND » par défaut, des conditions « OR » facultatives et des groupes de filtres organisés pour des critères complexes.
activity: use
team: Technical Marketing
feature: Reports and Dashboards
thumbnail: create-or-statements-in-filters.png
type: Tutorial
role: User
level: Intermediate
jira: KT-9987
exl-id: 1a56f2f6-12df-43a5-943c-986a85661efa
last-substantial-update: 2025-08-11T00:00:00Z
doc-type: video
source-git-commit: b3cff8f86ceeb6e79e2b88ab335b2671aa25600a
workflow-type: tm+mt
source-wordcount: '320'
ht-degree: 31%

---

# Créer des instructions OR dans les filtres

La vidéo explique comment créer et utiliser des filtres avec plusieurs règles dans Workfront. &#x200B; Par défaut, Workfront utilise « AND » entre les règles de filtrage, ce qui signifie que toutes les conditions doivent être vraies pour qu’un élément apparaisse dans la liste.
Vous pouvez également remplacer la logique de filtre par « OU », qui affiche les éléments qui répondent à l’une des conditions.
La vidéo illustre également la création de filtres pour les tâches à l’aide de groupes de filtres. &#x200B; Par exemple, vous pouvez créer deux groupes : un pour les tâches incomplètes affectées à l’équipe créative en retard et un autre pour les tâches incomplètes affectées à l’équipe créative qui ne sont pas affectées. &#x200B; Au sein de chaque groupe, la logique « AND » s’applique, ce qui signifie que toutes les conditions du groupe doivent être remplies. &#x200B; La logique « OR » entre les groupes garantit que les tâches répondant aux conditions de l’un ou l’autre groupe sont affichées.

>[!VIDEO](https://video.tv.adobe.com/v/3470695/?quality=12&learn=on&captions=fre_fr)

## Activité du filtre OR

Vous voulez trouver les tâches incomplètes qui vous sont attribuées ou qui ne sont attribuées à personne. Vous configurez un filtre qui ressemble à celui présenté ci-dessous. Ce filtre vous donnera-t-il les résultats que vous souhaitez ? Pourquoi ou pourquoi pas ?

![Image d’une instruction OR créée de manière incorrecte dans [!DNL Workfront]](assets/or-statement-your-turn-1.png)

### Réponses

Non, ce filtre ne donnera pas les résultats que vous espérez (des tâches qui ne sont pas terminées et qui vous sont affectées ou qui ne sont affectées à personne), car la règle de filtrage pour l’exhaustivité de la tâche n’est que d’un côté de l’opérateur OR.

Au lieu de cela, ce filtre génère une liste qui indique :

* Tâches qui vous sont affectées et qui ne sont pas terminées
* **PLUS (OR)**
* Toutes les tâches non assignées, quel que soit leur statut.

Le filtre doit ressembler à l’illustration ci-dessous. Notez que ce filtre contient la règle de filtrage pour l’exhaustivité de la tâche des deux côtés de la zone D’enregistrement.

![Image d’une instruction OR correctement créée dans [!DNL Workfront]](assets/or-statement-your-turn-2.png)
