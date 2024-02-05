---
title: Bonne pratique - Licences et niveaux d’accès
description: Découvrez les recommandations de bonnes pratiques des expertes et experts d’Adobe Workfront concernant la configuration, la gestion et l’utilisation des licences et des niveaux d’accès Workfront.
feature: System Setup and Administration
role: Admin, Leader, User
level: Beginner
jira: KT-10914
exl-id: 6be3fab9-16a1-4ab9-89ce-8c53f8358e62
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: ht
source-wordcount: '1253'
ht-degree: 100%

---

# Bonne pratique - Licences et niveaux d’accès

## En quoi consiste une « bonne pratique » Adobe Workfront ?

Les bonnes pratiques sont des directives qui présentent une ligne de conduite efficace. Vous pouvez facilement les adopter, ainsi que les utilisateurs et utilisatrices de votre entreprise, et elles peuvent être reproduites avec succès dans toute votre organisation.

En examinant ces recommandations, gardez à l’esprit que certaines des bonnes pratiques de Workfront sont universelles, tandis que d’autres peuvent être plus spécifiques au sujet. Utilisez ces bonnes pratiques comme cadre pour vous aider à configurer et à utiliser le système Workfront.

## Naviguer sur cette page

En parcourant cette page, vous trouverez d’abord une liste détaillée de toutes les bonnes pratiques pour ce sujet. Cela vous permet d’examiner les recommandations sans entrer dans les détails du « pourquoi ».

La zone « Pourquoi s’agit-il de bonnes pratiques ? » qui se trouve après la liste détaillée, fournit plus de détails sur certaines des bonnes pratiques et sur les raisons pour lesquelles elles sont considérées comme un processus, un outil, etc. que vous devriez envisager de mettre en place avec votre instance Workfront.

</br>
</br>

## Bonnes pratiques relatives aux licences et aux niveaux d’accès

* Commencez par un accès moindre pour les utilisateurs et utilisatrices lors de la configuration des niveaux d’accès.

* Lors de l’affectation de licences de révision et de demande, la fonction Réviser est généralement activée par défaut, car elle accorde à l’utilisateur ou l’utilisatrice davantage d’autorisations dans Adobe Workfront.

* Décochez la case « Partager à l’échelle du système » sur chaque objet à tous les niveaux d’accès, sauf si vous souhaitez précisément que ces utilisateurs et utilisatrices puissent le faire.

* Envisagez d’activer le paramètre « Ne jamais autoriser les utilisateurs et utilisatrices à supprimer les commentaires » sous Définir des restrictions supplémentaires dans un niveau d’accès.

* Limitez le nombre d’administrateurs et administratrices système en faveur des administrateurs et administratrices de groupe.

* Copiez un niveau d’accès existant et apportez des modifications, plutôt que de créer un nouveau niveau d’accès à partir de zéro.

* Décrivez ce que chaque niveau d’accès peut faire dans la zone Description.

* Limitez-vous aux niveaux d’accès nécessaires pour atteindre vos objectifs de travail, idéalement quatre ou cinq, qui répondent aux besoins de la plupart des utilisateurs et utilisatrices du système.

* Affectez au moins deux utilisateurs ou utilisatrices au niveau d’accès d’administration globale du système.

* Limitez ce que les utilisateurs et utilisatrices peuvent faire des éléments Workfront en réalisant un partage, plutôt qu’en supprimant une fonctionnalité d’un niveau d’accès.

</br>
</br>


## Pourquoi s’agit-il des bonnes pratiques ?

**Bonnes pratiques**

Commencez par un accès moindre pour les utilisateurs et utilisatrices lors de la configuration des niveaux d’accès.



**Voici pourquoi**

Commencez par donner aux utilisateurs et utilisatrices l’accès minimum dont ils auront besoin pour faire leur travail. S’ils ne peuvent pas faire leur travail en raison de droits d’accès insuffisants, ils demanderont généralement un accès supplémentaire. L’octroi immédiat d’un accès trop important aux utilisateurs et utilisatrices peut entraîner des problèmes de sécurité. De plus, il est toujours préférable d’élargir l’accès pour les utilisateurs et utilisatrices plutôt que d’en supprimer.

</br>
</br>



**Bonne pratique**

Lors de l’affectation de licences de révision et de demande, la fonction Réviser est généralement activée par défaut, car elle accorde à l’utilisateur ou l’utilisatrice davantage d’autorisations dans Adobe Workfront.



**Voici pourquoi**

Bien que les licences Révision et Demande puissent être affectées à un nombre illimité de personnes dans Workfront, les licences Demande se limitent globalement à l’élaboration et à la mise à jour de demandes. Une licence Révision offre un accès plus large aux projets et aux tâches qu’une licence Demande, ainsi que la possibilité d’afficher des portfolios et des programmes, de modifier des documents et d’accéder aux outils de gestion des ressources.

</br>
</br>

**Bonne pratique**

Décochez la case « Partager à l’échelle du système » sur chaque objet à tous les niveaux d’accès, sauf s’il existe une raison spécifique pour laquelle les utilisateurs et utilisatrices doivent pouvoir effectuer des partages à l’échelle du système.



**Voici pourquoi**

Le partage d’un objet à l’échelle du système est souvent utilisé comme un contournement pour permettre à certaines personnes de voir des éléments dans Workfront. Cela se produit lorsque la structure du groupe Workfront est insuffisante ou lorsque les autorisations de partage ne sont pas bien comprises. Lorsque des éléments sont partagés à l’échelle du système, cela signifie que tout le monde peut voir l’élément partagé. Selon le type d’informations conservées dans le système, cela peut entraîner des problèmes de confidentialité.



Par exemple, vous pourriez travailler avec plusieurs fournisseurs et fournisseuses au sein de Workfront pour vérifier l’état d’avancement, fournir des approbations, etc. Si la case à cocher « Partager à l’échelle du système » est une option, elle peut être sélectionnée ou définie comme valeur par défaut, ce qui rend les informations disponibles pour tous les fournisseurs et fournisseuses.



Si vous décochez complètement l’option, un utilisateur ou une utilisatrice ayant l’autorisation de partager devra déterminer la ou les personnes spécifiques - par l’intermédiaire d’une entreprise, d’un groupe ou d’une équipe - avec lesquelles il ou elle souhaite partager l’objet.

</br>
</br>

**Bonne pratique**

Envisagez d’activer le paramètre « Ne jamais autoriser les utilisateurs et utilisatrices à supprimer les commentaires » sous Définir des restrictions supplémentaires dans un niveau d’accès.



**Voici pourquoi**

L’activation de cette option permet de s’assurer que les communications passées ne sont pas supprimées de Workfront. Certaines organisations exigent que l’historique complet des commentaires soit conservé à des fins d’audit.

</br>
</br>

**Bonne pratique**

Limitez le nombre d’administrateurs et administratrices système en faveur des administrateurs et administratrices de groupe.



**Voici pourquoi**

Les équipes d’administration système ont accès à tout Workfront, y compris aux paramètres globaux du système. Les paramètres auxquels les équipes d’administration du groupe peuvent accéder sont contrôlés par l’administrateur ou l’administratrice système et s’appliquent uniquement à ce groupe spécifique.



Le fait d’avoir des équipes d’administration de groupe permet aux administrateurs et administratrices système de déléguer de nombreuses responsabilités, ce qui leur permet de se concentrer sur des éléments plus importants, plutôt que sur la maintenance quotidienne de Workfront. Les équipes d’administration de groupe peuvent plus facilement rester en contact avec les besoins de leurs groupes, ce qui offre un meilleur service aux utilisateurs et utilisatrices.

</br>
</br>


**Bonne pratique**

Copiez un niveau d’accès existant et apportez des modifications, plutôt que de créer un nouveau niveau d’accès à partir de zéro.



**Voici pourquoi**

La copie d’un niveau d’accès existant assure une base cohérente pour les nouveaux niveaux d’accès, garantissant la similitude des paramètres initiaux. Cela permet également de gagner du temps, car les équipes d’administration système n’auront pas à configurer le niveau d’accès dans son intégralité.

</br>
</br>

**Bonne pratique**

Décrivez ce que chaque niveau d’accès peut faire dans la zone Description.



**Voici pourquoi**

La description doit être détaillée et préciser les paramètres de chaque type d’objet. Cela permet aux administrateurs et administratrices système, actuels et futurs, de savoir exactement ce que fait chaque niveau d’accès sans avoir à explorer en détails le niveau d’accès lui-même pour vérifier les paramètres.



Cela peut également faciliter la comparaison des niveaux d’accès dans un rapport. Le champ de description peut être rapidement ajouté à la vue pour découvrir sans tarder quelles sont les différences et, éventuellement, les raisons pour lesquelles un niveau d’accès différent a été créé.

</br>
</br>

**Bonne pratique**

Limitez-vous aux niveaux d’accès nécessaires pour atteindre vos objectifs de travail, idéalement quatre ou cinq, qui répondent aux besoins de la plupart des utilisateurs et utilisatrices du système.


**Voici pourquoi**

Le niveau d’accès garantit que lorsqu’un objet Workfront est partagé avec une personne, celle-ci dispose des droits nécessaires pour le modifier, le supprimer, etc. Vous pouvez rendre les niveaux d’accès plus généraux, car il est possible de configurer le partage d’éléments individuels afin qu’il soit plus spécifique.


En outre, le fait d’avoir moins de niveaux d’accès peut faciliter la maintenance d’un système et la mise en œuvre d’une stratégie, ce qui peut également accélérer l’intégration lorsque des personnes rejoignent l’entreprise ou changent de service.

</br>
</br>

**Bonne pratique**

Affectez au moins deux utilisateurs ou utilisatrices au niveau d’accès d’administration globale du système.

**Voici pourquoi**

Il est important que plusieurs personnes comprennent pourquoi Workfront a été configuré de la sorte, comment le gérer/maintenir et comment aider les utilisateurs et utilisatrices. Si une personne est absente du bureau, quitte l’organisation, est occupée, etc., cela permet de s’assurer qu’une autre personne dispose des informations et des connaissances pour gérer le système.

</br>
</br>

**Bonne pratique**

Limitez ce que les utilisateurs et utilisatrices peuvent faire des éléments Workfront en réalisant un partage, plutôt qu’en supprimant une fonctionnalité d’un niveau d’accès.


**Voici pourquoi**

Les niveaux d’accès contrôlent ce que les utilisateurs et les utilisatrices peuvent faire avec des éléments spécifiques au niveau global. Les autorisations de partage de chaque projet, tâche, portfolio, document, etc. contrôlent ce qu’une personne individuelle peut faire avec cet élément spécifique. Plutôt que de supprimer une fonctionnalité pour toutes les personnes disposant d’un niveau d’accès spécifique, affinez les autorisations de partage sur des éléments spécifiques afin que les utilisateurs et utilisatrices disposent de contrôles limités.
