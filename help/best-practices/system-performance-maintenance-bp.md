---
title: Bonne pratique - Performances du système et maintenance.
description: Découvrez les recommandations relatives aux bonnes pratiques des expertes et experts d’Adobe Workfront concernant les performances et la maintenance du système Workfront.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10927
exl-id: c3f32975-96f4-4e62-8c3a-5b985b45bbbf
TQID: https://experienceleague.adobe.com/2tq7aNHE96fep1EFCPrjcCo13t5lQ24A6c-ORDUmlpY
product_v2: id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2: id: d968a1bc-9a90-4926-a531-bcf272c32aad
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554id: c66ffd68-0f65-42bb-aa23-b4020f12e0bdid: f8a45b24-4be7-4f1b-909b-60d06b483a20
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2: id: aa2f3246-cb95-4b30-8899-fdf7d73550ccid: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: 36674ed53c8645f556862bb2d99f3bfd6c993c1e
workflow-type: tm+mt
source-wordcount: 638
ht-degree: 93%

---

# Bonne pratique - Performances du système et maintenance.

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques pour ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La zone « Pourquoi ces bonnes pratiques ? », qui se trouve après la liste de haut niveau, fournit plus de détails sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., que vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux performances et à la maintenance du système

* Consultez les notes de mise à jour du produit avant la date de publication.

* Créez différents types de rapports d’exceptions qui mettent en évidence des données et des paramètres manquants ou incorrects.

* Créez un processus de désactivation de l’utilisateur ou de l’utilisatrice qui inclut une révision des objets qui leur appartiennent ou qui leur sont affectés, de sorte que les utilisateurs ou les utilisatrices qui ne font plus partie de l’entreprise ne restent pas actifs dans le système et sèment la confusion chez les autres utilisateurs et utilisatrices.

* Veillez à ce que les configurations de workflow soient aussi simples que possible pour vous assurer qu’elles soient évolutives et qu’elles puissent être conservées en votre absence.

* Utilisez les filtres sur les rapports et les listes d’objets pour diminuer le nombre de lignes affichées simultanément et permettre à l’équipe de se concentrer sur les informations importantes.

* Videz régulièrement la mémoire cache et les cookies de votre navigateur afin d’améliorer les performances de Workfront.

* Commencez à nettoyer votre système dans les zones Adobe Workfront les plus encombrées, telles que les formulaires personnalisés, les modèles, les projets et les utilisateurs et utilisatrices.

* Identifiez le cluster sur lequel se trouve votre instance Workfront afin que vous puissiez surveiller les mises à jour, connaître les fenêtres de maintenance, etc.

* Faites en sorte que les projets soient courts.

* Dans la mesure du possible, faites en sorte que les rapports soient « légers » avec des filtres simples et peu nombreux pour améliorer les performances.

</br>
</br>

## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Consultez les notes de mise à jour du produit avant la date de publication.



**Voici pourquoi**

Les notes de mise à jour vous informent des nouvelles fonctionnalités et nouveaux outils qui seront ajoutés au système Workfront. En examinant ces notes et en analysant les nouvelles fonctionnalités de l’environnement de prévisualisation des sandbox, vous avez la possibilité d’en savoir plus sur les bugs relatifs aux nouvelles améliorations, de les découvrir et de les résoudre avant qu’ils ne soient publiés.

</br>
</br>

**Bonne pratique**

Créez différents types de rapports d’exceptions qui mettent en évidence des données et des paramètres manquants ou incorrects.



**Voici pourquoi**

Ces rapports vous indiquent quels sont les utilisateurs et les utilisatrices à désactiver, les projets qui affichent un pourcentage d’achèvement de 100 %, mais ne sont pas marqués comme terminés, les modèles qui n’ont jamais été utilisés, etc.



Placez ces rapports, ainsi que d’autres, sur un tableau de bord en donnant accès aux autres administrateurs et administratrices système et de groupe afin de maintenir un système propre et opportun. Par exemple, le tableau de bord Nettoyage de Workfront et le tableau de bord Utilisation de Workfront contiennent des exemples de rapports que vous pouvez créer.



Pour vous rappeler de vérifier ces rapports, au moins une fois par trimestre, créez un projet avec des tâches trimestrielles et affectez-les à vous-même ainsi qu’aux administrateurs et administratrices du système et des groupes. Assurez-vous que ces tâches comportent des heures planifiées afin que les personnes affectées à ces éléments de travail puissent allouer correctement leur temps.

</br>
</br>

**Bonne pratique**

Faites en sorte que les projets soient courts.



**Voici pourquoi**

Chaque fois que vous enregistrez un projet ou une tâche dans le projet, un calcul de chronologie est effectué pour mettre à jour toutes les dépendances. Selon le nombre de tâches de votre projet, l’exécution du nouveau calcul peut prendre un certain temps.
