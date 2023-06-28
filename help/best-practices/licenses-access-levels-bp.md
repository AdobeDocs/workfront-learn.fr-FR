---
title: Bonne pratique - Licences et niveaux d’accès
description: Découvrez les recommandations de bonnes pratiques des experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation des licences et des niveaux d’accès Workfront.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10914
exl-id: 6be3fab9-16a1-4ab9-89ce-8c53f8358e62
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '1253'
ht-degree: 0%

---

# Bonne pratique - Licences et niveaux d’accès

## Qu’est-ce qu’une &quot;bonne pratique&quot; Adobe Workfront ?

Les meilleures pratiques sont des lignes directrices qui représentent un plan d&#39;action efficace et efficace; sont facilement adoptés par vous et les utilisateurs de votre entreprise ; et peut être répliqué avec succès dans l’ensemble de votre organisation.

Lorsque vous passez en revue ces recommandations, gardez à l’esprit que certaines bonnes pratiques Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à guider vos configurations et votre utilisation du système Workfront.

## Navigation dans cette page

Lorsque vous parcourez cette page, vous trouverez d’abord une liste de haut niveau de toutes les bonnes pratiques relatives à la rubrique. Cela vous permet de consulter les recommandations sans entrer dans les détails du &quot;pourquoi&quot;.

&quot;Pourquoi ces bonnes pratiques ?&quot; , qui se trouve après la liste de haut niveau, fournit des détails plus détaillés sur certaines des bonnes pratiques et pourquoi elles sont considérées comme un processus, un outil, etc., vous devez envisager d’implémenter avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux licences et aux niveaux d’accès

* Commencez par un accès moindre pour les utilisateurs lors de la configuration des niveaux d’accès.

* Lors de l’attribution de licences de révision et de demande, la fonction Réviser est généralement activée par défaut, car elle accorde à l’utilisateur davantage d’autorisations dans Adobe Workfront.

* Décochez la case &quot;Partager à l’échelle du système&quot; sur chaque objet à tous les niveaux d’accès, sauf si vous souhaitez que ces utilisateurs puissent le faire spécifiquement.

* Envisagez d’activer le paramètre &quot;Ne jamais autoriser les utilisateurs à supprimer les commentaires&quot; sous Définir des restrictions supplémentaires dans un niveau d’accès.

* Limitez le nombre d’administrateurs système en faveur des administrateurs de groupe.

* Copiez un niveau d’accès existant et apportez des modifications, plutôt que de créer un nouveau niveau d’accès à partir de zéro.

* Documentez ce que chaque niveau d’accès peut faire dans la zone Description.

* Limitez-vous uniquement aux niveaux d’accès nécessaires pour atteindre vos objectifs de travail, idéalement quatre ou cinq qui répondent aux besoins de la plupart des utilisateurs du système.

* Attribuez au moins deux utilisateurs au niveau d’accès administrateur du système global.

* Limitez ce que les utilisateurs peuvent faire des éléments Workfront par le partage, plutôt que de supprimer une fonctionnalité d’un niveau d’accès.

</br>
</br>


## Pourquoi ces bonnes pratiques ?

**Bonne pratique**

Commencez par un accès moindre pour les utilisateurs lors de la configuration des niveaux d’accès.



**Voici pourquoi**

Démarrez les utilisateurs avec l’accès minimal dont ils auront besoin pour effectuer leur travail. S’ils ne peuvent pas effectuer leurs tâches en raison de droits d’accès insuffisants, ils demanderont généralement un accès supplémentaire. L’octroi immédiat d’un trop grand accès aux utilisateurs peut entraîner des problèmes de sécurité. De plus, il est toujours préférable de donner aux utilisateurs plus d’accès que de supprimer l’accès.

</br>
</br>



**Bonne pratique**

Lors de l’attribution de licences de révision et de demande, la fonction Réviser est généralement activée par défaut, car elle accorde à l’utilisateur davantage d’autorisations dans Adobe Workfront.



**Voici pourquoi**

Bien que les licences de révision et de demande puissent être attribuées à un nombre illimité d’utilisateurs dans Workfront, les licences de demande se limitent à effectuer et mettre à jour des demandes. Une licence Révision offre plus d’accès aux projets et aux tâches qu’une licence Demander, ainsi que la possibilité d’afficher des portefeuilles et des programmes, de modifier des documents et d’accéder aux outils de gestion des ressources.

</br>
</br>

**Bonne pratique**

Décochez la case &quot;Partager à l’échelle du système&quot; sur chaque objet à tous les niveaux d’accès, sauf s’il existe une raison spécifique pour laquelle les utilisateurs doivent pouvoir partager à l’échelle du système.



**Voici pourquoi**

Le partage d’un objet à l’échelle du système est souvent utilisé comme une béquille pour permettre à certains utilisateurs de voir des éléments dans Workfront. Cela se produit lorsque la structure de groupe Workfront est manquante ou lorsque les autorisations de partage ne sont pas entièrement comprises. Lorsque des éléments sont partagés à l’échelle du système, cela signifie que tout le monde peut voir l’élément partagé. Selon le type d’informations conservées dans le système, cela peut entraîner des problèmes de confidentialité.



Par exemple, vous pouvez collaborer avec plusieurs fournisseurs dans Workfront pour vérifier l’avancement, fournir les approbations, etc. Si la case à cocher &quot;Partager à l’échelle du système&quot; est une option, elle peut être sélectionnée ou définie comme valeur par défaut, ce qui rend les informations disponibles pour tous les fournisseurs.



En décochant complètement l’option, vous faites en sorte qu’un utilisateur, avec l’autorisation de partager, détermine la ou les personnes spécifiques — par l’intermédiaire d’une société, d’un groupe ou d’une équipe — avec lesquelles il souhaite partager l’objet.

</br>
</br>

**Bonne pratique**

Envisagez d’activer le paramètre &quot;Ne jamais autoriser les utilisateurs à supprimer les commentaires&quot; sous Définir des restrictions supplémentaires dans un niveau d’accès.



**Voici pourquoi**

L’activation de cette option garantit que les communications antérieures ne sont pas supprimées de Workfront. Certaines organisations exigent que l’historique complet des commentaires soit conservé à des fins de contrôle.

</br>
</br>

**Bonne pratique**

Limitez le nombre d’administrateurs système en faveur des administrateurs de groupe.



**Voici pourquoi**

Les administrateurs système ont accès à tous les éléments de Workfront, y compris les paramètres système globaux. Les administrateurs de groupe de paramètres peuvent accéder à sont contrôlés par l’administrateur système et s’appliquent uniquement à ce groupe spécifique.



Le fait d’avoir des administrateurs de groupe permet aux administrateurs système de déléguer de nombreuses responsabilités, ce qui leur permet de se concentrer sur des éléments d’image plus importants, plutôt que sur la maintenance quotidienne de Workfront. Les administrateurs de groupe peuvent plus facilement rester en contact avec les besoins de leurs groupes, ce qui offre un meilleur service aux utilisateurs.

</br>
</br>


**Bonne pratique**

Copiez un niveau d’accès existant et apportez des modifications, plutôt que de créer un nouveau niveau d’accès à partir de zéro.



**Voici pourquoi**

La copie d’un niveau d’accès existant fournit une base cohérente pour les nouveaux niveaux d’accès, en s’assurant que les paramètres initiaux sont identiques. Cela permet également d’économiser du temps, car les administrateurs système n’auront pas à configurer entièrement un niveau d’accès à partir de zéro.

</br>
</br>

**Bonne pratique**

Documentez ce que chaque niveau d’accès peut faire dans la zone Description.



**Voici pourquoi**

Soyez détaillé avec la description, en indiquant les paramètres de chaque type d’objet. Cela permet aux administrateurs système, actuels et futurs, de savoir exactement ce que fait chaque niveau d’accès sans avoir à passer au niveau d’accès lui-même pour vérifier les paramètres.



Cela peut également faciliter la comparaison des niveaux d’accès lors de leur consultation dans un rapport. Le champ de description peut être rapidement ajouté à la vue pour voir rapidement en quoi ils diffèrent et, éventuellement, pourquoi un niveau d’accès différent a été créé.

</br>
</br>

**Bonne pratique**

Limitez-vous uniquement aux niveaux d’accès nécessaires pour atteindre vos objectifs de travail, idéalement quatre ou cinq qui répondent aux besoins de la plupart des utilisateurs du système.


**Voici pourquoi**

Le niveau d’accès garantit que lorsqu’un objet Workfront est partagé avec un utilisateur, celui-ci dispose des droits dont il a besoin pour le modifier, le supprimer, etc. Vous pouvez rendre les niveaux d’accès plus généraux, car le partage sur des éléments individuels peut être configuré pour être plus spécifique.


En outre, le fait d’avoir moins de niveaux d’accès peut faciliter la maintenance d’un système plus encombrant et la mise en oeuvre d’une stratégie, ce qui peut également accélérer l’intégration lorsque des personnes rejoignent l’entreprise ou changent de département.

</br>
</br>

**Bonne pratique**

Attribuez au moins deux utilisateurs au niveau d’accès administrateur du système global.

**Voici pourquoi**

Plus d’une personne doit comprendre pourquoi Workfront a été configuré comme il l’était, comment le gérer/le gérer et comment prendre en charge les utilisateurs. Si une personne est absente du bureau, quitte l’organisation, est occupée, etc., cela garantit qu’une autre personne dispose des informations et des connaissances pour gérer le système avec succès.

</br>
</br>

**Bonne pratique**

Limitez ce que les utilisateurs peuvent faire des éléments Workfront par le partage, plutôt que de supprimer une fonctionnalité d’un niveau d’accès.


**Voici pourquoi**

Les niveaux d’accès contrôlent ce que les utilisateurs peuvent faire avec des éléments spécifiques à un niveau global. Les autorisations de partage sur chaque projet, tâche, portfolio, document, etc., contrôlent ce qu’un utilisateur peut faire de cet élément spécifique. Plutôt que de supprimer une fonctionnalité pour toutes les personnes disposant d’un niveau d’accès spécifique, affinez les autorisations de partage sur des éléments spécifiques afin que les utilisateurs disposent de contrôles limités.
