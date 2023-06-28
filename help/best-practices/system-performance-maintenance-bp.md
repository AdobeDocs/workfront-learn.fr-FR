---
title: Bonne pratique - Performances du système et maintenance
description: Examinez les recommandations relatives aux bonnes pratiques des experts d’Adobe Workfront concernant les performances et la maintenance du système Workfront.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10927
exl-id: c3f32975-96f4-4e62-8c3a-5b985b45bbbf
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '635'
ht-degree: 0%

---

# Bonne pratique - Performances du système et maintenance

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques de maintenance et de performance du système

* Consultez les notes de mise à jour du produit avant la date de publication.

* Créez différents types de rapports d’exceptions qui mettent en évidence des données et des paramètres manquants ou incorrects.

* Créez un processus de désactivation de l’utilisateur qui inclut une révision des objets qui lui appartiennent ou qui lui sont affectés, de sorte que les utilisateurs qui ne font plus partie de l’entreprise ne restent pas principaux dans le système et créent la confusion pour d’autres utilisateurs.

* Veillez à ce que les configurations de workflow soient aussi simples que possible pour vous assurer qu’elles sont évolutives et qu’elles peuvent être conservées en votre absence.

* Utilisez les filtres sur les rapports et les listes d’objets pour diminuer le nombre de lignes affichées simultanément et concentrer l’équipe sur des informations importantes.

* Effacez régulièrement le cache et les cookies de votre navigateur afin d’améliorer les performances de Workfront.

* Commencez à nettoyer votre système dans les zones Adobe Workfront les plus encombrées, telles que les formulaires personnalisés, les modèles, les projets et les utilisateurs.

* Connaissez la grappe sur laquelle se trouve votre instance Workfront afin que vous puissiez surveiller les mises à jour, connaître les fenêtres de maintenance, etc.

* Gardez les projets courts.

* Dans la mesure du possible, laissez les rapports &quot;légers&quot; avec très peu de filtres simples pour améliorer les performances.

</br>
</br>

## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Consultez les notes de mise à jour du produit avant la date de publication.



**Voici pourquoi**

Les notes de mise à jour vous indiquent les nouvelles fonctionnalités et les nouveaux outils du système Workfront. En examinant ces notes et en analysant les nouvelles fonctionnalités de l’environnement de prévisualisation des environnements de test, vous avez la possibilité d’en savoir plus, de vous entraîner et de résoudre les bogues avec de nouvelles améliorations avant qu’ils ne soient publiés en production.

</br>
</br>

**Bonne pratique**

Créez différents types de rapports d’exceptions qui mettent en évidence des données et des paramètres manquants ou incorrects.



**Voici pourquoi**

Ces rapports contiennent des rapports qui indiquent les utilisateurs à désactiver, les projets qui affichent un pourcentage d’achèvement de 100 % mais ne sont pas marqués comme terminés, les modèles qui n’ont jamais été utilisés, etc.



Placez ces rapports, entre autres, sur un tableau de bord et autorisez les autres administrateurs système et groupe à accéder à ce tableau de bord afin de maintenir un système propre en temps voulu. Par exemple, le tableau de bord Nettoyage de Workfront et le tableau de bord de l’utilisation de Workfront contiennent des exemples de rapports que vous pouvez créer.



Pour vous aider à garder à l’esprit la vérification de ces rapports, au moins une fois par trimestre, créez un projet avec des tâches trimestrielles et attribuez-les à vous-même, ainsi qu’aux administrateurs système et groupe. Assurez-vous que ces tâches ont planifié les heures associées afin que les personnes désignées de ces tâches puissent allouer correctement leur temps.

</br>
</br>

**Bonne pratique**

Gardez les projets courts.



**Voici pourquoi**

Chaque fois que vous enregistrez un projet, ou une tâche à l’intérieur du projet, un calcul de chronologie est exécuté pour mettre à jour toutes les dépendances. Selon le nombre de tâches de votre projet, l’exécution du nouveau calcul peut prendre un certain temps.
