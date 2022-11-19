---
title: Rôles de BAT et alertes par email
description: Découvrez comment activer les rôles de BAT et les alertes par email appropriés pour que les destinataires du BAT aient accès aux bons à tirer et aient une bonne visibilité sur le travail effectué dans [!DNL  Workfront].
activity: use
team: Technical Marketing
feature: Workfront Proof
type: Tutorial
role: User, Admin
level: Beginner
thumbnail: proof-roles-and-email-alerts.png
kt: 10177
exl-id: 15bfb18a-5392-4a91-a6a2-223f7ac30dc5
source-git-commit: 58a545120b29a5f492344b89b77235e548e94241
workflow-type: tm+mt
source-wordcount: '562'
ht-degree: 0%

---

# Rôles de BAT et alertes par email

Les rôles de BAT et les alertes par email permettent de piloter le workflow de BAT, en s&#39;assurant que les destinataires disposent du droit d&#39;accès aux BAT et d&#39;une bonne visibilité sur le travail en cours.

Examinons la terminologie de base du BAT :

* **Rôle de preuve —** Définit ce qu’un utilisateur peut faire avec un BAT (par exemple, commentaire, annotation, approbation, etc.).
* **Alerte email —** Emails envoyés aux personnes dans le workflow de BAT lorsqu’il y a une activité sur le BAT.

![Une image de la fonction [!UICONTROL Nouvelle preuve] avec la fenêtre [!UICONTROL Rôle BAT] et [!UICONTROL Alertes par email] en surbrillance.](assets/proof-roles-and-email-alerts.png)

L’administrateur de votre système de BAT peut définir les rôles de BAT par défaut et les alertes par e-mail pour les utilisateurs de BAT de votre entreprise. En outre, ces informations peuvent être intégrées aux modèles de workflow de BAT (également appelés modèles de workflow automatisés).

Cependant, il peut arriver que vous deviez définir ces informations manuellement lors du téléchargement d’un BAT.

[!DNL Workfront] propose les recommandations générales suivantes lors de l’attribution des rôles de BAT aux destinataires du BAT :

* **Réviseur et approbateur —** Ces utilisateurs peuvent à la fois faire des commentaires sur les BAT et prendre une décision (approuvée ou rejetée, par exemple) sur un BAT. Utilisez ce rôle de BAT pour les principaux intervenants internes et externes dans le processus de révision.
* **Réviseur —** Certaines personnes de votre workflow de BAT n&#39;ont qu&#39;à faire des commentaires, ce rôle est idéal pour elles. Le rôle de réviseur peut également être attribué à [!DNL Workfront] les utilisateurs qui chargent principalement des bons à tirer ou qui servent de propriétaire de BAT, mais qui ne font pas partie du processus de vérification.
* **Lecture seule —** Idéal pour les destinataires qui n&#39;ont besoin que de voir le BAT. [!UICONTROL Lecture seule] donne accès à la vue et n’autorise pas les commentaires.

[!DNL Workfront] propose les recommandations générales suivantes lors de l’attribution d’alertes par email aux destinataires du BAT :

* **Décision finale —** Un email est envoyé lorsque la dernière personne prend une décision sur le BAT. Affectez-le à la personne qui surveille le workflow du BAT. Il peut s’agir d’un gestionnaire de BAT, d’un propriétaire de BAT, d’un créateur de BAT, d’un chef de projet ou d’un autre [!DNL Workfront] utilisateur. [!DNL Workfront] recommande cette alerte lors de l’utilisation d’un workflow de base, de sorte que la personne qui surveille le BAT sache que toutes les décisions ont été prises.
* **Décisions —** Cela envoie des alertes car chaque partie prenante du workflow de vérification prend une décision sur le BAT. Cette option est préférable lorsque vous utilisez un workflow automatisé, avec plusieurs décisions. Affectez à la personne qui surveille le workflow du BAT. Il peut s’agir d’un gestionnaire de BAT, d’un propriétaire de BAT, d’un créateur de BAT, d’un chef de projet ou d’un autre [!DNL Workfront] utilisateur.
* **Désactivé —** Utilisez cette option pour que les utilisateurs invités du BAT limitent le nombre d’emails qu’ils reçoivent au sujet du BAT. Les destinataires sont toujours informés des nouveaux BAT, des nouvelles versions, des derniers BAT, ainsi que des [!DNL Workfront] les utilisateurs reçoivent des messages directs envoyés dans un commentaire de BAT en utilisant @username et les destinataires invités avec @emailaddress.

## Votre tour

1. Connectez-vous à Workfront et créez des utilisateurs qui utiliseront la vérification que vous n’avez pas créée auparavant. Définissez le profil des autorisations de BAT dans leurs paramètres utilisateur en fonction du rôle que la personne jouera dans les workflows de BAT.
1. Pour les utilisateurs déjà créés, modifiez leurs paramètres afin d’ajuster la sélection de profil des autorisations et BAT, si nécessaire.
1. Accédez à la zone de configuration de la vérification et à l’onglet Utilisateurs . Vérifiez les paramètres personnels de vos utilisateurs (langue, fuseau horaire, format de date, rôle de BAT par défaut et alerte par e-mail par défaut). Ceci est important si ces utilisateurs ont été créés avant que les valeurs par défaut du système global ne soient établies (ces paramètres sont abordés dans la section 1 de ce parcours d’apprentissage).

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
