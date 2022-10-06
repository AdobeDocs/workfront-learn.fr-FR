---
title: Bonne pratique - Création de rapports en mode texte
description: Examinez les recommandations relatives aux bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation de la création de rapports en mode texte Workfront.
feature: Reports and Dashboards
role: Admin, Leader, User
level: Beginner
kt: 10928
exl-id: c624545c-ba42-4cc3-aafe-8be15baadb75
source-git-commit: 444f059d3cc26d8e3074a7145bc5419407c786cf
workflow-type: tm+mt
source-wordcount: '414'
ht-degree: 0%

---

# Bonne pratique - Création de rapports en mode texte

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux rapports sur le mode texte

* Lorsque cela est possible, utilisez des expressions de valeur du mode texte au lieu de champs personnalisés calculés dans les colonnes du rapport de liste.

* Placez les calculs utilisés dans un calcul en mode texte dans la description du rapport.

</br>
</br>

## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Lorsque cela est possible, utilisez des expressions de valeur du mode texte au lieu de champs personnalisés calculés dans les colonnes du rapport de liste.



**Voici pourquoi**

Les expressions de valeur du mode texte sont calculées au moment de l’exécution du rapport et sont recalculées chaque fois que le rapport est actualisé. Cela signifie que vous disposez toujours de données à jour et de rapports précis.



Les champs personnalisés calculés (utilisés dans les formulaires personnalisés) ne sont pas mis à jour automatiquement lorsque les données sont affichées dans Workfront. Ils affichent plutôt les résultats du calcul le plus récent stocké dans Workfront. Cela signifie que ces valeurs peuvent être &quot;obsolètes&quot; ou obsolètes à un moment donné. Les champs personnalisés calculés doivent être actualisés manuellement, soit en recalculant l&#39;expression, soit en modifiant et en enregistrant l&#39;objet qui contient le champ calculé. Cela peut prendre du temps et être facile à oublier.


</br>
</br>

**Bonne pratique**

Placez les calculs utilisés dans un calcul en mode texte dans la description du rapport.



**Voici pourquoi**

L’inclusion de tout calcul de mode texte dans la description du rapport permet à d’autres personnes de comprendre comment le calcul a été créé et quel type d’informations il doit afficher. Il rappelle également aux administrateurs système comment le rapport a été créé, au cas où des mises à jour seraient nécessaires à l’avenir.
