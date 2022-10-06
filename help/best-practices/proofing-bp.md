---
title: Bonne pratique - Vérification
description: Découvrez les recommandations de bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation de la vérification dans Workfront.
feature: Workfront Proof
role: Admin, Leader, User
level: Beginner
kt: 10920
exl-id: 394485ee-bb8f-4248-86a9-4c86174dd37f
source-git-commit: 444f059d3cc26d8e3074a7145bc5419407c786cf
workflow-type: tm+mt
source-wordcount: '1179'
ht-degree: 0%

---

# Bonne pratique - Vérification

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives à la vérification dans Workfront

* Prenez le temps de créer des modèles de workflow de vérification.

* Désactivez le paramètre &quot;Envoyer des emails à partir de Workfront lorsqu’un commentaire est fait sur un BAT&quot; dans les configurations Workfront.

* Utilisez uniquement Lecture seule ou Réviseur pour le paramètre &quot;Rôles pour les non-destinataires qui ouvrent un BAT de document&quot; dans Workfront.

* Ajustez les paramètres du serveur principal BAT afin que les utilisateurs voient les échéances sous la forme d’une horloge de 12 heures.

* Définissez une date limite de BAT par défaut dans les paramètres du système.

* Masquez l’option de décision de BAT non pertinent .

* Ne réorganisez pas les options de décision du BAT dans les paramètres du BAT.

* Définissez les valeurs par défaut des utilisateurs pour les rôles de BAT et les alertes par email.

* Définissez le rôle de BAT du créateur du BAT sur Réviseur.

* Évitez d’utiliser le rôle d’approbateur de BAT.

* Évitez l’option d’alerte par email de toutes les activités BAT .

</br>
</br>

## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Prenez le temps de créer des modèles de workflow de vérification.

**Voici pourquoi**

Non seulement les modèles accélèrent et rationalisent le processus de création et d’affectation de BAT, mais ils assurent la cohérence entre les workflows de BAT pour des types de ressources similaires. Ils s’assurent également que chaque destinataire du BAT se voit attribuer le rôle de BAT approprié et une alerte par email, et qu’une date limite a été fixée.

</br>
</br>

**Bonne pratique**

Désactivez le paramètre &quot;Envoyer des emails à partir de Workfront lorsqu’un commentaire est fait sur un BAT&quot; dans les configurations Workfront.



**Voici pourquoi**

Lorsque ce paramètre est activé (par défaut), les utilisateurs peuvent recevoir plusieurs notifications par e-mail pour chaque commentaire sur un BAT, l’une provenant de la fonctionnalité de vérification et l’autre de Workfront lui-même. Ces notifications en double provoquent des perturbations et une confusion dans les notifications par e-mail, ainsi qu’une boîte de réception par e-mail complète, ce qui peut entraîner l’ignorance des notifications de BAT reçues par les utilisateurs. Ce qui, à son tour, pourrait signifier des échéances non respectées.



**Remarque**: Ce paramètre se trouve dans le menu principal de Workfront > Configuration > Email > Révision et approbation.

</br>
</br>

**Bonne pratique**

Utilisez uniquement Lecture seule ou Réviseur pour le paramètre &quot;Rôles pour les non-destinataires qui ouvrent un BAT de document&quot; dans Workfront.



**Voici pourquoi**

Les autres options de ce paramètre nécessitent qu’une décision de BAT soit prise, ce qui peut faire dérailler votre workflow de vérification. En règle générale, les personnes qui ne sont pas ajoutées au workflow de BAT doivent simplement afficher le BAT ou faire des commentaires, ne pas approuver réellement le BAT. Par conséquent, les options Lecture seule ou Réviseur sont votre meilleur choix.



**Remarque**: Ce paramètre se trouve dans le menu principal de Workfront > Configuration > Révision et approbation.

</br>
</br>

**Bonne pratique**

Ajustez les paramètres du serveur principal BAT afin que les utilisateurs voient les échéances sous la forme d’une horloge de 12 heures.



**Voici pourquoi**

Sélectionnez l’option F j, Y, gi:a dans les paramètres du BAT pour les utilisateurs qui souhaitent afficher les échéances/heures du BAT au format AM/PM. Pour les zones qui utilisent une horloge de 12 heures, cette option permet de clarifier les échéances.



**Remarque**: Pour accéder à ce paramètre, sélectionnez le menu principal Workfront > Vérification > Paramètres du compte > Utilisateurs > et modifiez le champ Format de date pour chaque utilisateur.

</br>
</br>

**Bonne pratique**

Définissez une date limite de BAT par défaut dans les paramètres du système.



**Voici pourquoi**

Lorsqu’un délai de BAT par défaut est défini (la date de téléchargement + x nombre de jours ouvrés), si le créateur du BAT oublie d’ajouter une date limite, Workfront applique automatiquement ce délai à chaque BAT transféré.



**Remarque**: Ce paramètre est accessible à partir du menu principal de Workfront > Vérification > Paramètres du compte > Paramètres > Valeurs par défaut du bon à tirer > Délai (+ jours ouvrables).

</br>
</br>


**Bonne pratique**

Masquez l’option de décision de BAT non pertinent .



**Voici pourquoi**

Cette option de décision crée souvent de la confusion parmi les approbateurs, car les organisations ne définissent pas quand l’option Non pertinent doit être utilisée. L&#39;option Non pertinent indique généralement que le BAT n&#39;est pas pertinent pour le destinataire du BAT et qu&#39;il n&#39;est pas nécessaire qu&#39;il prenne une décision approuvée ou rejetée. En sélectionnant Non pertinent, le workflow de BAT peut continuer.


L’option Non pertinent n’est pas nécessaire dans la plupart des workflows de BAT.

**Remarque**: Ce paramètre est accessible dans le menu principal de Workfront > Vérification > Paramètres du compte > Décisions.

</br>
</br>

**Bonne pratique**

Ne réorganisez pas les options de décision du BAT dans les paramètres du BAT.



**Voici pourquoi**

Chaque paramètre de décision de BAT contient une valeur/un poids spécifique qui, s’il est réorganisé, peut prêter à confusion dans vos configurations de BAT. L’ordre de décision et la valeur/le poids sont utilisés comme déclencheurs d’activation de l’étape du BAT et dans les rapports.



**Remarque**: Ce paramètre est accessible dans le menu principal de Workfront > Vérification > Paramètres du compte > Décisions.

</br>
</br>

**Bonne pratique**

Définissez les valeurs par défaut des utilisateurs pour les rôles de BAT et les alertes par email.



**Voici pourquoi**

Ces paramètres sont renseignés automatiquement lors de l’attribution d’un workflow de BAT, de l’accélération du processus et de la cohérence entre les workflows de BAT.



**Remarque**: Les paramètres par défaut de l’utilisateur sont disponibles dans le menu principal de Workfront > Vérification > Paramètres du compte > Utilisateurs > et sélectionnez l’utilisateur pour lequel définir les paramètres par défaut.

</br>
</br>

**Bonne pratique**

Définissez le rôle de BAT du créateur du BAT sur Réviseur.



**Voici pourquoi**

Le rôle du BAT du réviseur permet au créateur du BAT de faire des commentaires et d’accéder aux commentaires laissés par d’autres personnes. La plupart du temps, le créateur du BAT n’est pas tenu de prendre une décision sur un BAT qu’il a téléchargé. Les rôles de BAT Approbateur, Réviseur et approbateur, Auteur ou Modérateur requièrent tous une décision. Si le créateur du BAT se voit attribuer l’un de ces rôles de BAT, mais qu’il ne prend jamais de décision, cela peut nuire aux délais du BAT.

</br>
</br>

**Bonne pratique**

Évitez d’utiliser le rôle d’approbateur de BAT.



**Voici pourquoi**

Le rôle d’ approbateur de BAT ne permet pas à l’utilisateur de faire des commentaires sur ce BAT. Cela peut entraîner un refus du BAT de la part d&#39;un utilisateur, sans aucune explication, car il ne peut pas faire de commentaires. Utilisez plutôt le rôle de BAT Réviseur et approbateur afin que l’utilisateur puisse fournir des commentaires.

</br>
</br>

**Bonne pratique**

Évitez l’option d’alerte par email de toutes les activités BAT .

**Voici pourquoi**

Cette option envoie une notification par email de BAT chaque fois qu’un événement se produit avec un BAT : un commentaire est émis, une réponse est publiée, une décision est prise, etc. Le destinataire voit essentiellement l’activité du BAT au fur et à mesure.

Pour les propriétaires et les créateurs de BAT, l’alerte par e-mail Decisions fonctionne le mieux pour les workflows de BAT à plusieurs étapes et la décision finale fonctionne le mieux pour les workflows à une seule étape. En règle générale, tout le monde peut être défini sur Désactivé, sauf s’il souhaite être averti des commentaires ou décisions d’autres personnes (auquel cas, l’une des options de résumé du courrier électronique peut fonctionner le mieux).
