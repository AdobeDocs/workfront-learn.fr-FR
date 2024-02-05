---
title: Rôles des BAT et alertes par e-mail
description: Découvrez comment activer les rôles d’épreuve et les alertes par e-mail appropriés pour que les destinataires de l’épreuve aient accès aux épreuves et aient une bonne visibilité sur le travail en cours dans  [!DNL  Workfront].
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User, Admin
level: Beginner
thumbnail: proof-roles-and-email-alerts.png
jira: KT-10177
exl-id: 15bfb18a-5392-4a91-a6a2-223f7ac30dc5
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: ht
source-wordcount: '551'
ht-degree: 100%

---

# Rôles des BAT et alertes par e-mail

Les rôles des épreuves et les alertes par e-mail permettent de piloter le workflow d’épreuves, en s’assurant que les destinataires ont le droit d’accéder aux épreuves et ont une bonne visibilité sur le travail en cours.

Examinons la terminologie de base des épreuves :

* **Rôle d’épreuve :** définit ce qu’un utilisateur ou une utilisatrice peut faire avec une épreuve (par exemple, commentaire, annotation, approbation, etc.).
* **Alerte par e-mail :** envoi d’e-mails aux personnes du workflow de l’épreuve lorsqu’il y a une activité sur l’épreuve.

![Image de la fenêtre [!UICONTROL Nouvelle épreuve] avec les colonnes [!UICONTROL Rôle d’épreuve] et [!UICONTROL Alertes par e-mail] en surbrillance.](assets/proof-roles-and-email-alerts.png)

Votre administrateur ou administratrice système des épreuves peut définir des rôles d’épreuve par défaut et des alertes par e-mail pour les utilisateurs et utilisatrices d’épreuves de votre organisation. En outre, ces informations peuvent être intégrées aux modèles de workflow d’épreuve (également appelés modèles de workflow automatisés).

Cependant, il peut arriver que vous deviez définir ces informations manuellement lors de l’import d’une épreuve.

[!DNL Workfront] propose les recommandations générales suivantes lors de l’affectation des rôles d’épreuve aux destinataires de l’épreuve :

* **Réviseur ou réviseuse et approbateur ou approbatrice :** ces utilisateurs et utilisatrices peuvent à la fois faire des commentaires sur les épreuves et prendre une décision (comme approuver ou rejeter) sur une épreuve. Utilisez ce rôle d’épreuve pour les principaux intervenants et intervenantes internes et externes du processus de révision.
* **Réviseur ou réviseuse :** certaines personnes dans votre workflow d’épreuve n’ont besoin que de rédiger des commentaires. Ce rôle est idéal pour celles-ci. Le rôle de réviseur ou réviseuse peut également être affecté aux utilisateurs et utilisatrices [!DNL Workfront] qui chargent principalement des épreuves ou sont propriétaires d’épreuves, mais qui ne font pas partie du processus de relecture.
* **Lecture seule :** idéal pour les destinataires qui n’ont besoin que de voir l’épreuve. La [!UICONTROL lecture seule] donne l’accès visuel et n’autorise pas les commentaires.

[!DNL Workfront] propose les recommandations générales suivantes lors de l’attribution d’alertes par e-mail aux destinataires de l’épreuve :

* **Décision finale :** un e-mail est envoyé lorsque la dernière personne prend une décision sur l’épreuve. Affectez ce rôle à la personne qui surveille le workflow de l’épreuve. Il peut s’agir d’un ou d’une gestionnaire d’épreuve, d’un ou d’une propriétaire d’épreuve, d’un créateur ou d’une créatrice d’épreuve, d’un chef ou d’une cheffe de projet ou d’un autre utilisateur ou d’une autre utilisatrice de [!DNL Workfront]. [!DNL Workfront] recommande cette alerte lors de l’utilisation d’un workflow de base, de sorte que la personne qui surveille l’épreuve sache que toutes les décisions ont été prises.
* **Décisions :** cette fonction envoie des alertes lorsque chaque intervenant ou intervenante du workflow prend une décision sur l’épreuve. Cette option est préférable lors de l’utilisation d’un workflow automatisé, avec plusieurs décisions. Affectez ce rôle à la personne qui surveille le workflow de l’épreuve. Il peut s’agir d’un ou d’une gestionnaire d’épreuve, d’un ou d’une propriétaire d’épreuve, d’un créateur ou d’une créatice d’épreuve, d’un chef ou d’une cheffe de projet ou d’un autre utilisateur ou d’une autre utilisatrice [!DNL Workfront].
* **Désactivé :** cette option permet aux utilisateurs et aux utilisatrices d’épreuve invités de limiter le nombre d’e-mails reçus au sujet de l’épreuve. Les destinataires sont toujours informés des nouvelles épreuves, des nouvelles versions, des épreuves urgentes, et les utilisateurs et utilisatrices [!DNL Workfront] reçoivent en plus les messages directs envoyés dans un commentaire d’épreuve via la fonction @nom_d’utilisateur, tandis que les destinataires invités les reçoivent via la fonction @adresse_e-mail.

## À vous

1. Connectez-vous à Workfront et créez des utilisateurs et utilisatrices qui utiliseront des épreuves que vous n’avez pas encore créées. Définissez le profil des autorisations d’épreuve dans leurs paramètres d’utilisateur ou d’utilisatrice en fonction du rôle que la personne endossera dans les workflows d’épreuves.
1. Pour les utilisateurs et utilisatrices déjà créés, modifiez leurs paramètres afin d’ajuster la sélection des profils des autorisations d’épreuve, le cas échéant.
1. Accédez à la zone de configuration des épreuves et accédez à l’onglet Utilisateurs. Vérifiez les paramètres personnels de vos utilisateurs et utilisatrices : langue, fuseau horaire, format de date, rôle d’épreuve par défaut et alerte e-mail par défaut. Ceci est important si ces utilisateurs et utilisatrices ont été créés avant que les valeurs par défaut globales du système ne soient établies.

<!--
Download the proof role and email alert guides to have on hand as you start uploading proofs and assigning proof recipients.
-->

<!--
## Learn more
* Notifications for proof comments and decisions
-->

<!--
## Guides
* Proof roles
* Email alerts
-->
