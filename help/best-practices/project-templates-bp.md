---
title: Bonne pratique - Modèles de projet
description: Examinez les recommandations relatives aux bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation des modèles de projet Workfront.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10919
exl-id: 17cd2e49-ee16-4b80-a8b2-ccc254fa8014
source-git-commit: d39151288d8b749940c5183063392ee471769445
workflow-type: tm+mt
source-wordcount: '1743'
ht-degree: 0%

---

# Bonne pratique - Modèles de projet

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les bonnes pratiques sont des consignes qui représentent un plan d’action efficace. Elles sont facilement adoptées par vous et les utilisateurs de votre entreprise et peuvent être répliquées avec succès dans l’ensemble de votre entreprise.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux modèles de projet

* Utilisez des modèles lors de la création de projets.

* Définissez une convention d’affectation des noms pour les modèles de projet.

* Créez un groupe sélectionné d’utilisateurs pouvant créer et mettre à jour des modèles de projet.

* Utilisez le partage de projet sur un modèle de projet pour accorder automatiquement l’accès aux projets créés à l’aide de ce modèle.

* Affectez des rôles ou des équipes de travail à des tâches, et non à des individus.

* Évitez d’être trop granulaire lors de la création de tâches dans un modèle de projet. Limitez le nombre de tâches d’un modèle de projet à celles nécessaires pour terminer le travail.

* Utilisez la description de la tâche pour capturer les petites étapes de la tâche, plutôt que de la ventiler en plusieurs tâches.

* Assurez-vous que les tâches de modèle incluent les durées de tâche, les heures planifiées et les prédécesseurs.

* Préconfigurer les détails du projet et joindre des formulaires personnalisés au modèle.

* Examinez et mettez régulièrement à jour les modèles de projet.

* Vérifiez les modèles pour vous assurer qu’ils contiennent toutes les informations nécessaires avant de les partager et que d’autres commencent à les utiliser.

* Lorsque vous ajustez l’option Planifier à partir d’un modèle, passez en revue et mettez à jour les contraintes de tâche.

* Vérifiez l’équipe du projet sur le modèle et supprimez les utilisateurs qui ne seront pas associés au projet.

</br>
</br>

## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Utilisez des modèles lors de la création de projets.

**Voici pourquoi :**

Les modèles de projet enlèvent aux chefs de projet (et aux autres personnes créant des projets) les conjectures sur les tâches d’un projet, sur la structure de la chronologie, etc. Les modèles constituent le moyen le plus efficace d’accélérer la création de projet.

Il est important de noter que les modèles fournissent une cohérence entre les projets de types similaires, de sorte que les personnes, les processus et les points de données soient détaillés de la même manière à chaque fois. Même les projets avec des rebonds rapides (un ou deux jours) et des tâches minimales peuvent bénéficier de la création avec des modèles de projet.

Grâce à cette cohérence entre les projets, les données sont plus précises, ce qui est essentiel pour prendre des décisions au sein de votre équipe, de votre service et de l’organisation.

</br>
</br>

**Bonne pratique**

Définissez une convention d’affectation des noms pour les modèles de projet.

**Voici pourquoi :**

L’affectation de nom cohérente facilite la recherche de modèles. Il permet également aux chefs de projet et aux autres créateurs de projets de sélectionner le modèle approprié lorsqu’il existe des modèles portant le même nom au sein de plusieurs équipes ou services.

</br>
</br>

**Bonne pratique**

Créez un groupe sélectionné d’utilisateurs pouvant créer et mettre à jour des modèles de projet.

**Voici pourquoi :**

Disposer de modèles de projet bien conçus et cohérents est essentiel pour une bonne gestion du travail et un reporting précis. Limitez le nombre d’utilisateurs pouvant modifier des modèles pour éviter des modifications accidentelles ou non approuvées.

</br>
</br>

**Bonne pratique**

Utilisez le partage de projet sur un modèle de projet pour accorder automatiquement l’accès aux projets créés à l’aide de ce modèle.

**Voici pourquoi :**

L’accès à des projets spécifiques est accordé par le biais du projet lui-même. Si le même groupe de personnes doit toujours accéder aux projets créés avec un modèle spécifique, ajoutez-les sous l’option Partage de projets du modèle. Non seulement vous pouvez contrôler l’accès aux projets dès leur création, mais cela simplifie les efforts d’évolutivité si les autorisations doivent changer à l’avenir.

Pour plus d’informations sur le partage de projets créés à l’aide d’un modèle, reportez-vous au chapitre intitulé &quot;Comment partager des projets créés à l’aide d’un modèle&quot; dans [Partage d’un modèle de projet](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-work/create-and-manage-project-templates/share-a-project-template.html).

**Remarque**: le partage de modèles accorde l’accès au modèle lui-même. Un utilisateur doit disposer d’au moins les autorisations Afficher pour réaliser des projets avec le modèle.

</br>
</br>

**Bonne pratique**

Affectez des rôles ou des équipes de travail à des tâches, et non à des individus.

**Voici pourquoi :**

Lorsqu’un utilisateur individuel change de poste ou quitte l’entreprise, vous devrez mettre à jour manuellement les modèles de projet qui incluent cette personne. Cela prend du temps pour une partie du système ou des groupes administrateurs ou chefs de projet.

Si vous utilisez des rôles de tâche ou des équipes sur les modèles, les modifications de personnel n’auront pas d’effet direct sur vos modèles de projet, car toute personne à qui ce rôle de tâche ou cette équipe pourrait se voir attribuer le travail. Cela permet de s&#39;assurer que le travail ne passe pas à travers les fissures. Les affectations de rôle de tâche facilitent également l’affectation de travail à des utilisateurs individuels, car Workfront peut vous afficher une liste des personnes auxquelles ce rôle de tâche a été affecté.

En outre, les rôles de tâche sont utilisés par les outils de planification des ressources de Workfront pour vous aider à calculer les ressources et à planifier les tâches futures.

</br>
</br>

**Bonne pratique**

Évitez d’être trop granulaire lors de la création de tâches dans un modèle de projet. Limitez le nombre de tâches d’un modèle de projet à celles nécessaires pour terminer le travail.

**Voici pourquoi :**

Les modèles de projet trop complexes génèrent une mauvaise expérience pour les utilisateurs : chefs de projet, gestionnaires de ressources, membres de l’équipe, etc. Trop de tâches rend la chronologie du projet difficile à gérer, avec des échéances de tâche se chevauchant et plusieurs tâches affectées aux mêmes rôles de travail ou aux mêmes personnes.


</br>
</br>

**Bonne pratique**

Utilisez la description de la tâche pour capturer les petites étapes de la tâche, plutôt que de la ventiler en plusieurs tâches.

**Voici pourquoi :**

Si plusieurs tâches d’une ligne sont affectées au même rôle/au même individu de tâche, cela indique que ces tâches peuvent être combinées. Trop de tâches affectées à un utilisateur peuvent leur donner l’impression qu’il reste encore du travail à accomplir, ce qui peut avoir une incidence sur l’adoption de Workfront.

</br>
</br>

**Bonne pratique**

Assurez-vous que les tâches de modèle incluent les durées de tâche, les heures planifiées et les prédécesseurs.

**Voici pourquoi :**

Ces trois éléments (durée, heures planifiées et prédécesseurs) sont les éléments constitutifs de la chronologie du projet. Elles sont essentielles pour savoir combien de temps le travail prendra et quand il faudra le faire. Les outils de gestion des ressources Workfront utilisent des durées et des heures planifiées, ainsi que des affectations de rôles de tâche, pour calculer la capacité, la disponibilité des ressources, etc.

Si vous ne savez pas comment estimer les durées ou les heures planifiées pour la première fois, travaillez avec l’équipe du projet pour définir des estimations initiales. Une fois que vous avez utilisé le modèle, rencontrez l’équipe du projet pour déterminer les modifications qui pourraient être apportées afin de le rendre plus précis. Si les utilisateurs ouvrent une session dans Workfront, vous pouvez comparer les heures planifiées d’un projet avec les heures réelles pour déterminer où des ajustements sont nécessaires.


</br>
</br>

**Bonne pratique**

Préconfigurer les détails du projet et joindre des formulaires personnalisés au modèle.

**Voici pourquoi :**

Assurez-vous que les informations standard pour tous les projets sont renseignées sur le modèle de projet. Cela permet non seulement d’accélérer la création du projet, mais aussi de s’assurer que les informations nécessaires sont disponibles et qu’elles sont cohérentes entre les projets.

Joignez des formulaires personnalisés de projet qui correspondent à des formulaires personnalisés de demande pour extraire les informations envoyées lors de la conversion de la demande en projet à l’aide du modèle.

Pour plus d’informations sur la manière de joindre un formulaire personnalisé à un objet tel qu’un modèle de projet, voir [Joindre un formulaire personnalisé à un objet](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/custom-data/custom-forms/custom-forms-using-a-custom-form.html).

</br>
</br>

**Bonne pratique**

Examinez et mettez régulièrement à jour les modèles de projet.

**Voici pourquoi :**

À mesure que les processus et les équipes changent, les modèles de projet doivent être mis à jour. Créez une cadence régulière, par exemple trimestrielle, pour vérifier et voir les modèles qui ne sont pas activement utilisés. Vous pouvez les désactiver afin qu’ils soient toujours dans Workfront, mais qu’ils n’apparaissent pas dans les listes de sélection de modèles.

Pour plus d’informations sur la désactivation d’un modèle de projet, voir [Désactivation d’un modèle de projet](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-work/create-and-manage-project-templates/deactivate-a-project-template.html).

</br>
</br>

**Bonne pratique**

Vérifiez les modèles pour vous assurer qu’ils contiennent toutes les informations nécessaires avant de les partager et que d’autres commencent à les utiliser.


**Voici pourquoi :**

Comme les modèles seront utilisés à plusieurs reprises pour créer des projets, vous devrez vous assurer que tout est configuré correctement et complètement. Cela entraîne la cohérence de tous les projets et des données précises pour la création de rapports.

Outre les paramètres de tâche tels que la durée et les heures planifiées, voici quelques éléments à vérifier avant de partager les modèles :

* Paramètre Planifier de
* Contraintes de tâche
* Propriétaire, sponsor, groupe et société du projet
* Portfolio et programme
* Chemin et étapes Milestone
* Processus d&#39;approbation
* Assurez-vous que les utilisateurs affectés aux tâches sur les projets ont un accès Contribution au projet
* Pools de ressources
* Notifications de rappel
* Planning
* Paramètre de devise (le cas échéant)
* Joindre des documents standard
* Joindre les formulaires douaniers nécessaires
* Vérifiez l’équipe du projet pour vous assurer qu’aucune autre personne n’est affectée.

</br>
</br>

**Bonne pratique**

Lorsque vous ajustez l’option Mode de planification sur un modèle, passez en revue et mettez à jour les contraintes de tâche.

**Voici pourquoi :**

Le mélange de différentes contraintes de tâche sur un projet peut entraîner des calculs de date planifiés inattendus et déroutants. Par exemple, lorsque Date de début est sélectionnée pour l’option Mode de planification , toutes les tâches créées dans ce projet se voient attribuer par défaut la contrainte de tâche Dès que possible . Si vous basculez par la suite l’option Mode de planification sur Date d’achèvement, toutes les tâches créées ont par défaut une contrainte de tâche Aussi tardive que possible . Le fait de combiner involontairement des tâches avec chacune de ces contraintes peut entraîner une confusion des dates planifiées dans la chronologie de votre projet.

Pour mieux comprendre les contraintes de tâche et leur utilisation, voir [Comprendre et gérer les types de durée et les contraintes de tâche](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-work/intermediate-projects/understand-and-manage-duration-types-and-task-constraints.html).

</br>
</br>

**Bonne pratique**

Vérifiez l’équipe du projet sur le modèle et supprimez les utilisateurs qui ne travailleront pas avec le projet.

**Voici pourquoi :**

Lorsque vous créez un modèle à partir d’un projet existant, à moins que vous ne choisissiez l’option Effacer les affectations lors de la création, Workfront met en relation les personnes auxquelles des tâches/problèmes ont été affectés sur le projet dans la section Personnes. Et lorsque vous travaillez avec votre modèle, vous pouvez supprimer ces personnes qui ont déjà été désignées ou modifier une affectation que vous avez effectuée vous-même sur le modèle.

Tous ces utilisateurs seront répertoriés dans l’équipe du projet, dans les sections Personnes et Planification du projet. Par conséquent, ils seront propagés à tous les projets créés à partir de ce modèle. Cela peut prêter à confusion pour l’utilisateur, car l’équipe du projet reçoit des notifications sur l’activité du projet, voit le projet dans la liste Projets actifs et obtient des autorisations sur le projet et ses tâches, problèmes et documents.

Pour plus d’informations sur la modification de l’équipe de projet dans un modèle de projet, voir [Modification de l’équipe de projet dans un modèle de projet](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-work/create-and-manage-project-templates/edit-the-project-team-in-a-project-template.html).
