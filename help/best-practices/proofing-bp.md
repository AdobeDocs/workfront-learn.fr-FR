---
title: Bonne pratique - Relecture
description: Découvrez les bonnes pratiques recommandées par les spécialistes d’Adobe Workfront en matière de configuration, de gestion et d’utilisation de la relecture dans Workfront.
feature: Workfront Proof
role: Admin, Leader, User
level: Beginner
jira: KT-10920
exl-id: 394485ee-bb8f-4248-86a9-4c86174dd37f
source-git-commit: af71439e222061cf468b78dfe1807f0b4893c52a
workflow-type: tm+mt
source-wordcount: '1182'
ht-degree: 91%

---

# Bonne pratique - Relecture

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques relatives à ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La question « Pourquoi s’agit-il de bonnes pratiques » ? qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques en matière de relecture dans Workfront

* Prenez le temps de créer des modèles de workflow de relecture.

* Désactivez le paramètre &quot;Envoyer des emails à partir de Workfront lorsqu’un commentaire est fait sur un BAT&quot; dans les configurations Workfront.

* Utilisez uniquement les rôles Lecture seule ou Réviseur ou réviseuse pour le paramètre « Rôles pour les personnes non destinataires qui ouvrent un BAT de document » dans Workfront.

* Ajustez les paramètres back-end de l’épreuve pour que les utilisateurs et les utilisatrices voient les échéances au format 12 heures.

* Fixez une date d’échéance par défaut pour la relecture dans les paramètres système.

* Masquez l’option non pertinente de statut de décision de l’épreuve.

* Ne réorganisez pas les options de statut de décision de l’épreuve les paramètres de l’épreuve.

* Définissez les valeurs par défaut des utilisateurs et des utilisatrices pour les rôles d’épreuve et les alertes par e-mail.

* Définissez le rôle de BAT de la personne qui a créé le BAT sur Réviseur ou réviseuse.

* Évitez d’utiliser le rôle d’épreuve Approbateur.

* Évitez l’option d’alerte par e-mail d’épreuve Toutes les activités.

</br>
</br>

## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Prenez le temps de créer des modèles de workflow de relecture.

**Voici pourquoi : **

Non seulement les modèles accélèrent et rationalisent le processus de création et d’attribution des épreuves, mais ils assurent la cohérence des workflows d’épreuve pour des types de ressources similaires. Ils s’assurent également que chaque personne destinataire d’épreuve se voit attribuer le rôle d’épreuve et l’alerte e-mail appropriés, et qu’une échéance a été fixée.

</br>
</br>

**Bonne pratique**

Désactivez le paramètre &quot;Envoyer des emails à partir de Workfront lorsqu’un commentaire est fait sur un BAT&quot; dans les configurations Workfront.



**Voici pourquoi : **

Lorsque ce paramètre est activé (ce qui est le cas par défaut), les utilisateurs et les utilisatrices ont la possibilité de recevoir plusieurs notifications par e-mail pour chaque commentaire sur une épreuve : une de la fonctionnalité de relecture et une autre de Workfront. Ces notifications en double entraînent une perturbation et une confusion dans les notifications par e-mail, ainsi qu’une boîte de réception pleine, ce qui peut amener les utilisateurs et les utilisatrices à ignorer les notifications d’épreuve qu’ils reçoivent. Ce qui, à son tour, pourrait signifier des échéances non respectées.



**Note** : ce paramètre se trouve dans le menu principal de Workfront > Configuration > E-mail > Révision et approbation.

</br>
</br>

**Bonne pratique**

Utilisez uniquement les rôles Lecture seule ou Réviseur ou réviseuse pour le paramètre « Rôles pour les personnes non destinataires qui ouvrent un BAT de document » dans Workfront.



**Voici pourquoi : **

Les autres options de ce paramètre requièrent toutes un statut de décision de l’épreuve, ce qui peut faire dérailler votre workflow de relecture. En règle générale, les personnes qui n’ont pas été ajoutées au workflow d’épreuve ont juste besoin de consulter l’épreuve ou de faire des commentaires, et non de l’approuver, de sorte que les options « Lecture seule » ou « Réviseur » sont les mieux adaptées.



**Remarque** : ce paramètre se trouve dans le menu principal de Workfront > Configuration > Révision et approbation.

</br>
</br>

**Bonne pratique**

Ajustez les paramètres back-end de l’épreuve pour que les utilisateurs et les utilisatrices voient les échéances au format 12 heures.



**Voici pourquoi : **

La valeur par défaut est un format d’horloge de 24 heures, ce qui peut dérouter ceux qui ne le connaissent pas. Pour modifier le format, accédez au menu principal de Workfront > Vérification > Paramètres du compte > Utilisateurs. Double-cliquez sur un utilisateur pour en sélectionner un, puis modifiez le champ Format de date dans la section Paramètres personnels . Vous devez sélectionner chaque utilisateur un par un pour le modifier.

</br>
</br>

**Bonne pratique**

Fixez une date d’échéance par défaut pour la relecture dans les paramètres système.



**Voici pourquoi : **

Lorsqu’une date d’échéance pour la relecture est définie par défaut (date de chargement + x nombre de jours ouvrables), si la personne ayant créé l’épreuve oublie d’ajouter une échéance, Workfront applique automatiquement cette échéance à chaque épreuve chargée.



**Remarque** : ce paramètre se trouve dans le menu principal Workfront > Relecture > Paramètres du compte > Paramètres > Valeurs par défaut des épreuves > champ Échéance (+ jours ouvrables).

</br>
</br>


**Bonne pratique**

Masquez l’option non pertinente de statut de décision de l’épreuve.



**Voici pourquoi : **

Cette option de décision est souvent source de confusion pour les personnes chargées de l’approbation, car les organisations ne définissent pas toujours quand l’option Non pertinent doit être utilisée. L’option Non pertinent indique généralement que l’épreuve n’est pas pertinente pour la personne destinataire de l’épreuve et qu’elle n’a pas besoin de prendre une décision d’approbation ou de rejet. En sélectionnant Non pertinent, le workflow d’épreuve peut continuer.


L’option Non pertinent n’est pas nécessaire dans la plupart des workflows d’épreuve.

**Remarque** : ce paramètre se trouve dans le menu principal de Workfront > Relecture > Paramètres du compte > Décisions.

</br>
</br>

**Bonne pratique**

Ne réorganisez pas les options de statut de décision de l’épreuve les paramètres de l’épreuve.



**Voici pourquoi : **

Chaque paramètre de statut de décision de l’épreuve contient une valeur/un poids spécifique qui, s’ils sont réorganisés, peuvent semer la confusion dans vos configurations d’épreuve. L’ordre de décision et la valeur/le poids sont utilisés comme déclencheurs d’activation de l’étape d’épreuve et dans les rapports.



**Remarque** : ce paramètre se trouve dans le menu principal de Workfront > Relecture > Paramètres du compte > Décisions.

</br>
</br>

**Bonne pratique**

Définissez les valeurs par défaut des utilisateurs et des utilisatrices pour les rôles d’épreuve et les alertes par e-mail.



**Voici pourquoi : **

Ces paramètres sont automatiquement renseignés lors de l’affectation d’un workflow d’épreuve, ce qui accélère le processus et contribue à la cohérence des workflows d’épreuve.



**Remarque** : les paramètres d’utilisateur par défaut se trouvent dans le menu principal de Workfront, en choisissant Relecture > Paramètres du compte > Utilisateurs et utilisatrices, et en sélectionnant l’utilisateur ou l’utilisatrice pour lequel les paramètres par défaut doivent être définis.

</br>
</br>

**Bonne pratique**

Définissez le rôle de BAT de la personne qui a créé le BAT sur Réviseur ou réviseuse.



**Voici pourquoi : **

Le rôle d’épreuve Réviseur garantit que la personne ayant créé l’épreuve peut faire des commentaires et accéder à ceux laissés par d’autres. La plupart du temps, la personne ayant créé un BAT n’est pas tenue de prendre une décision sur un BAT qu’elle a chargé. Les rôles d’approbation, de révision et d’approbation, de création ou de modération des épreuves exigent tous qu’une décision soit prise. Si la personne ayant créé l’épreuve se voit affecter l’un de ces rôles mais ne prend jamais de décision, cela peut avoir des conséquences négatives sur les échéances.

</br>
</br>

**Bonne pratique**

Évitez d’utiliser le rôle d’épreuve Approbateur.



**Voici pourquoi : **

Le rôle d’approbation ne permet pas à l’utilisateur ou à l’utilisatrice d’apporter des commentaires sur cette épreuve. Cela pourrait amener un utilisateur ou une utilisatrice à refuser l’épreuve, sans aucune explication, parce qu’il lui a été impossible de faire des commentaires. Utilisez plutôt le rôle Réviseur et approbateur d’épreuve pour que l’utilisateur ou l’utilisatrice puisse faire des commentaires.

</br>
</br>

**Bonne pratique**

Évitez l’option d’alerte par e-mail d’épreuve Toutes les activités.

**Voici pourquoi : **

Cette option permet d’envoyer une notification par e-mail à chaque fois qu’il se passe quelque chose avec une épreuve : un commentaire est fait, une réponse est publiée, une décision est prise, etc. Le ou la destinataire voit l’activité du BAT au fur et à mesure qu’elle se produit.

Pour les propriétaires et créateurs et créatrices de BAT, l’alerte par e-mail Décisions est la plus adaptée aux workflows de BAT en plusieurs étapes et la Décision finale est la plus adaptée aux workflows en une seule étape. En règle générale, tous les autres peuvent être désactivés, à moins qu’ils ne souhaitent être informés des commentaires ou décisions des autres personnes (dans ce cas, l’une des options d’envoi d’un résumé par e-mail peut se révéler plus efficace).
