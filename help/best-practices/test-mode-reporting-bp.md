---
title: Bonne pratique - Création de rapports en mode texte
description: Découvrez les recommandations relatives aux bonnes pratiques des spécialistes Adobe Workfront en matière de configuration, de gestion et d’utilisation du système de création de rapports Workfront en mode texte.
feature: Reports and Dashboards
role: Admin, Leader, User
level: Beginner
jira: KT-10928
exl-id: c624545c-ba42-4cc3-aafe-8be15baadb75
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '414'
ht-degree: 100%

---

# Bonne pratique - Création de rapports en mode texte

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques pour ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La zone « Pourquoi s’agit-il de bonnes pratiques ? » qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques en matière de création de rapports en mode texte

* Lorsque cela est possible, utilisez des expressions de valeur en mode texte au lieu de champs personnalisés calculés dans les colonnes de rapports de liste.

* Placez les calculs utilisés dans un calcul en mode texte dans la description du rapport.

</br>
</br>

## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Lorsque cela est possible, utilisez des expressions de valeur en mode texte au lieu de champs personnalisés calculés dans les colonnes de rapports de liste.



**Voici pourquoi**

Les expressions de valeur en mode texte sont calculées au moment de l’exécution du rapport et sont recalculées chaque fois que le rapport est actualisé. Cela signifie que vous disposez toujours de données à jour et de rapports précis.



Les champs personnalisés calculés (utilisés dans les formulaires personnalisés) ne sont pas mis à jour automatiquement lorsque les données sont affichées dans Workfront. Au lieu de cela, ceux-ci affichent les résultats du calcul le plus récent stocké dans Workfront. Cela signifie que ces valeurs peuvent être anciennes ou obsolètes à tout moment. Les champs personnalisés calculés doivent être actualisés manuellement, soit en recalculant l’expression, soit en modifiant et en enregistrant l’objet qui contient le champ calculé. Cela peut prendre du temps et être facile à oublier.


</br>
</br>

**Bonne pratique**

Placez les calculs utilisés dans un calcul en mode texte dans la description du rapport.



**Voici pourquoi**

L’inclusion des calculs en mode texte dans la description du rapport aide les autres personnes à comprendre comment le calcul a été élaboré et quel type d’informations celui-ci doit afficher. Cela rappelle également aux administrateurs et administratrices système comment le rapport a été élaboré, au cas où des mises à jour seraient nécessaires à l’avenir.
