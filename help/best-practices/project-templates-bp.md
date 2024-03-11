---
title: Bonne pratique - Modèles de projet
description: Découvrez les bonnes pratiques recommandées par les expertes et les experts Adobe Workfront en matière de configuration, de gestion et d’utilisation des modèles de projet Workfront.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10919
exl-id: 17cd2e49-ee16-4b80-a8b2-ccc254fa8014
source-git-commit: d39151288d8b749940c5183063392ee471769445
workflow-type: ht
source-wordcount: '1743'
ht-degree: 100%

---

# Bonne pratique - Modèles de projet

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques relatives à ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La question « Pourquoi s’agit-il de bonnes pratiques » ? qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux modèles de projet

* Utilisez des modèles lors de la création de projets.

* Définissez une convention de nommage pour les modèles de projet.

* Créez un groupe d’utilisateurs et d’utilisatrices sélectionnés qui peuvent créer et mettre à jour des modèles de projet.

* Utilisez le partage de projet sur un modèle de projet pour accorder automatiquement l’accès aux projets créés à l’aide de ce modèle.

* Attribuez des fonctions ou des équipes à des tâches, et non à des personnes individuelles.

* Évitez d’être trop granulaire lorsque vous créez des tâches dans un modèle de projet. Limitez le nombre de tâches d’un modèle de projet à celles qui sont nécessaires pour achever le travail.

* Utilisez la description de la tâche pour capturer les petites étapes de la tâche, plutôt que de la ventiler en plusieurs tâches.

* Assurez-vous que les tâches de modèle incluent les durées de tâche, les heures planifiées et les personnes ayant travaillé dessus par le passé.

* Préconfigurez les détails du projet et joignez des formulaires personnalisés au modèle.

* Examinez et mettez régulièrement à jour les modèles de projet.

* Vérifiez les modèles pour vous assurer qu’ils contiennent toutes les informations nécessaires avant de les partager et de les faire utiliser par d’autres.

* Lorsque vous ajustez l’option Planifier à partir de sur un modèle, passez en revue et mettez à jour les contraintes de tâche.

* Examinez l’équipe de projet sur le modèle et supprimez les utilisateurs et utilisatrices qui ne seront pas associés au projet.

</br>
</br>

## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Utilisez des modèles lors de la création de projets.

**Voici pourquoi : **

Les modèles de projet permettent aux personnes chargées de la gestion de projet (et aux autres personnes qui créent des projets) de ne plus avoir à se poser de questions sur les tâches que doit contenir un projet, sur la manière de structurer le calendrier, etc. Les modèles constituent le moyen le plus efficace d’accélérer la création de projet.

Il est important de noter que les modèles assurent la cohérence entre les projets de même type, de sorte que les personnes, les processus et les points de données sont détaillés de la même manière à chaque fois. Même les projets dont les délais d’exécution sont rapides (un ou deux jours) et les tâches minimes peuvent être créés à l’aide de modèles de projet.

Grâce à cette cohérence entre les projets, les données sont plus précises, ce qui est essentiel pour prendre des décisions au sein de votre équipe, de votre service et de l’organisation.

</br>
</br>

**Bonne pratique**

Définissez une convention de nommage pour les modèles de projet.

**Voici pourquoi : **

Une dénomination cohérente facilite la recherche des modèles. Cela aide également les personnes chargées de la gestion de projet et les autres personnes qui créent des projets à sélectionner le bon modèle lorsqu’il existe des modèles portant le même nom au sein de plusieurs équipes ou services.

</br>
</br>

**Bonne pratique**

Créez un groupe d’utilisateurs et d’utilisatrices sélectionnés qui peuvent créer et mettre à jour des modèles de projet.

**Voici pourquoi : **

Disposer de modèles de projet bien conçus et cohérents est essentiel pour une bonne gestion du travail et l’établissement de rapports précis. Limitez le nombre de personnes pouvant modifier les modèles afin d’éviter les modifications accidentelles ou non approuvées.

</br>
</br>

**Bonne pratique**

Utilisez le partage de projet sur un modèle de projet pour accorder automatiquement l’accès aux projets créés à l’aide de ce modèle.

**Voici pourquoi : **

L’accès à des projets spécifiques est accordé par le biais du projet lui-même. Si le même groupe de personnes doit toujours avoir accès aux projets créés avec un modèle spécifique, ajoutez-les sous l’option Partage de projet du modèle. Vous pouvez contrôler l’accès aux projets dès leur création pour optimiser les efforts d’évolutivité si les autorisations doivent être modifiées à l’avenir.

Pour obtenir des instructions sur le partage de projets créés à l’aide d’un modèle, reportez-vous au chapitre intitulé « Partager des projets créés à l’aide d’un modèle » dans [Partager un modèle de projet](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-work/create-and-manage-project-templates/share-a-project-template.html?lang=fr).

**Note** : le partage de modèle donne accès au modèle lui-même. Une personne doit avoir au moins les autorisations d’affichage pour créer des projets avec le modèle.

</br>
</br>

**Bonne pratique**

Attribuez des fonctions ou des équipes à des tâches, et non à des personnes individuelles.

**Voici pourquoi : **

Lorsqu’une personne change de poste ou quitte l’organisation, vous devez mettre à jour manuellement les modèles de projet qui incluent cette personne. Cela demande du temps de la part des administrateurs ou administratrices du système ou du groupe ou des personnes chargées de la gestion du projet.

Si vous utilisez des fonctions ou des équipes dans les modèles, les changements de personnel n’auront pas d’effet direct sur vos modèles de projet, car toute personne assignée à cette fonction ou appartenant à cette équipe pourrait se voir confier le travail. Cela permet de s’assurer que le travail ne passe pas entre les mailles du filet. L’attribution de fonctions facilite également l’attribution de tâches à des personnes individuelles, car Workfront peut vous montrer une liste de personnes auxquelles cette fonction a été attribuée.

En outre, les fonctions sont utilisées par les outils de planification des ressources de Workfront pour vous aider à calculer les ressources nécessaires et à planifier le travail futur.

</br>
</br>

**Bonne pratique**

Évitez d’être trop granulaire lorsque vous créez des tâches dans un modèle de projet. Limitez le nombre de tâches d’un modèle de projet à celles qui sont nécessaires pour achever le travail.

**Voici pourquoi : **

Des modèles de projet trop compliqués sont une mauvaise expérience pour les utilisateurs et les utilisatrices (personnes chargées de la gestion de projet et de la gestion de ressources, personnes membres de l’équipe, etc). Un trop grand nombre de tâches rend le calendrier du projet difficile à gérer, avec des échéances qui se chevauchent et des tâches multiples attribuées aux mêmes fonctions ou aux mêmes personnes.


</br>
</br>

**Bonne pratique**

Utilisez la description de la tâche pour capturer les petites étapes de la tâche, plutôt que de la ventiler en plusieurs tâches.

**Voici pourquoi : **

Si plusieurs tâches d’une même ligne sont attribuées à la même fonction/personne, cela indique que ces tâches pourraient être combinées. Un trop grand nombre de tâches assignées à une personne peut lui donner l’impression d’avoir plus de travail à accomplir, ce qui peut affecter l’adoption de Workfront.

</br>
</br>

**Bonne pratique**

Assurez-vous que les tâches de modèle incluent les durées de tâche, les heures planifiées et les personnes ayant travaillé dessus par le passé.

**Voici pourquoi : **

Ces trois éléments (les durées, le nombre d’heures prévues et les personnes ayant travaillé sur la tâche par le passé) sont les éléments constitutifs du calendrier du projet. Ces éléments sont essentiels pour savoir combien de temps durera le travail et quand il devra être effectué. Les outils de gestion des ressources de Workfront utilisent les durées et le nombre d’heures prévues, ainsi que les attributions de fonctions, afin de calculer la capacité des ressources, leur disponibilité et bien plus encore.

Si vous ne savez pas comment estimer les durées ou le nombre d’heures prévues pour la première fois, travaillez avec l’équipe du projet pour définir des estimations initiales. Une fois le modèle utilisé, rencontrez à nouveau l’équipe de projet pour déterminer les modifications à apporter afin de rendre le modèle plus précis. Si les personnes enregistrent leur temps dans Workfront, vous pouvez comparer le nombre d’heures prévues d’un projet avec les heures effectives pour voir où des ajustements sont nécessaires.


</br>
</br>

**Bonne pratique**

Préconfigurez les détails du projet et joignez des formulaires personnalisés au modèle.

**Voici pourquoi : **

Veillez à ce que les informations standard pour tous les projets soient remplies sur le modèle de projet. Cela permet non seulement d’accélérer la création du projet, mais aussi de s’assurer que les informations nécessaires sont disponibles et qu’elles sont cohérentes entre les projets.

Attachez des formulaires personnalisés de projet qui correspondent aux formulaires personnalisés de la demande afin d’extraire les informations soumises lors de la conversion de la demande en projet à l’aide du modèle.

Pour obtenir des instructions sur la manière de joindre un formulaire personnalisé à un objet tel qu’un modèle de projet, voir [Joindre un formulaire personnalisé à un objet](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/custom-data/custom-forms/custom-forms-using-a-custom-form.html?lang=fr).

</br>
</br>

**Bonne pratique**

Examinez et mettez régulièrement à jour les modèles de projet.

**Voici pourquoi : **

Au fur et à mesure que les processus et les équipes évoluent, les modèles de projet doivent être mis à jour. Établissez un rythme régulier, par exemple trimestriel, pour vérifier quels sont les modèles qui ne sont pas activement utilisés. Vous pouvez les désactiver afin qu’ils soient toujours dans Workfront, mais qu’ils n’apparaissent pas dans les listes de sélection de modèles.

Pour obtenir des instructions sur la désactivation d’un modèle de projet, voir [Désactiver un modèle de projet](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-work/create-and-manage-project-templates/deactivate-a-project-template.html?lang=fr).

</br>
</br>

**Bonne pratique**

Vérifiez les modèles pour vous assurer qu’ils contiennent toutes les informations nécessaires avant de les partager et de les faire utiliser par d’autres.


**Voici pourquoi : **

Étant donné que les modèles seront utilisés à plusieurs reprises pour réaliser des projets, vous devez vous assurer que tout est configuré correctement et complètement. Cela permet d’assurer la cohérence de tous les projets et d’obtenir des données précises pour l’établissement des rapports.

Outre les paramètres de la tâche tels que la durée et les heures planifiées, voici quelques éléments à vérifier avant de partager des modèles :

* Paramètre Planifier à partir
* Contraintes de tâche
* Personne propriétaire de projet, sponsor, groupe et société du projet
* Portfolio et programme
* Chemin jalonné et étapes
* Processus d&#39;approbation
* Assurez-vous que les personnes affectées aux tâches sur les projets ont un accès de contribution au projet.
* Pools de ressources
* Notifications de rappel
* Planning
* Paramètre de devise (le cas échéant)
* Joindre des documents standard
* Joindre les formulaires personnalisés nécessaires
* Vérifiez l’équipe du projet pour vous assurer qu’aucune autre personne n’est affectée.

</br>
</br>

**Bonnes pratiques**

Lorsque vous ajustez l’option Mode planning sur un modèle, passez en revue et mettez à jour les contraintes de tâche.

**Voici pourquoi : **

Le mélange de différentes contraintes de tâches sur un projet peut entraîner des calculs de dates planifiées inattendus et déroutants. Par exemple, lorsque la date de début est sélectionnée pour l’option Mode planning, toutes les tâches créées dans ce projet se voient attribuer par défaut la contrainte de tâche Dès que possible. Si vous remplacez ensuite l’option Mode planning par Date d’achèvement, toutes les tâches créées sont assorties par défaut d’une contrainte de tâche Le plus tard possible. Le mélange involontaire de tâches soumises à chacune de ces contraintes peut entraîner une confusion au niveau des dates prévues dans le calendrier du projet.

Pour mieux comprendre les contraintes de tâche et leur utilisation, voir [Comprendre et gérer les types de durée et les contraintes de tâche](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-work/intermediate-projects/understand-and-manage-duration-types-and-task-constraints.html?lang=fr).

</br>
</br>

**Bonnes pratiques**

Vérifiez l’équipe du projet sur le modèle et supprimez les utilisateurs et utilisatrices qui ne travailleront pas sur le projet.

**Voici pourquoi : **

Lorsque vous créez un modèle à partir d’un projet existant, à moins que vous ne choisissiez l’option Effacer les affectations lors de la création, Workfront met en relation les personnes auxquelles des tâches/problèmes ont été affectés sur le projet dans la section Personnes. Et lorsque vous travaillez avec votre modèle, vous pouvez supprimer les personnes auxquelles vous aviez auparavant affecté un travail ou modifier une affectation que vous avez effectuée vous-même sur le modèle.

Toutes ces personnes seront répertoriées comme faisant partie de l’équipe du projet, dans les sections Personnes et Planification du projet. Par conséquent, elles seront propagées à tous les projets créés à partir de ce modèle. Cela peut être source de confusion pour la personne, car, en tant que personne membre de l’équipe de projet, elle reçoit des notifications sur l’activité du projet, voit le projet dans la liste Projets auxquels je participe et obtient des autorisations sur le projet, ses tâches, ses problèmes et ses documents.

Pour obtenir des instructions sur la modification de l’équipe de projet dans un modèle de projet, voir [Modifier l’équipe de projet dans un modèle de projet](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-work/create-and-manage-project-templates/edit-the-project-team-in-a-project-template.html?lang=fr).
