---
title: Appliquer un processus d'approbation des événements dans une file d'attente des demandes
description: Implémentez un processus d’approbation par défaut pour rationaliser les workflows de demande, en veillant à ce que les demandes approuvées modifient leur statut de manière appropriée en « Nouveau ». Corrigez la confusion créée par les demandes rejetées en sélectionnant un changement de statut sur « Impossible de résoudre ».
activity: use
feature: Approvals
thumbnail: 335225.jpeg
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
jira: KT-17578
last-substantial-update: 2025-03-26T00:00:00Z
recommendations: noDisplay,catalog
doc-type: video
source-git-commit: 3fc3a58c829769ca06ffb93971ac75516dfbd5f2
workflow-type: tm+mt
source-wordcount: '376'
ht-degree: 5%

---

# Appliquer un processus d&#39;approbation des événements dans une file d&#39;attente des demandes

>[!PREREQUISITES]
>
>* [Créer un flux de requêtes](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/manage-work/request-queues/create-a-request-flow)
>* [Créer un processus de validation global et à usage unique](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/manage-work/approval-processes-and-milestone-paths/create-a-single-use-approval-process)


La vidéo explique le processus d’application d’un processus d’approbation par défaut lors de la création d’une file d’attente de demandes. &#x200B; Lorsqu&#39;une demande est créée, elle commence avec le statut « Nouveau - Approbation en attente » et une notification d&#39;approbation est envoyée à l&#39;approbateur désigné. &#x200B; S&#39;il est approuvé, le statut passe à « Nouveau », ce qui permet aux personnes affectées de commencer le travail. &#x200B; En cas de rejet, le statut peut revenir incorrectement à « Nouveau » en raison d&#39;une erreur courante dans la configuration du processus d&#39;approbation. &#x200B;
La vidéo montre que le processus d’approbation est déclenché lorsque le statut est défini sur « Nouveau », qui est le statut par défaut des nouvelles demandes. &#x200B; En cas de rejet, le système redéfinit par défaut le statut sur le précédent, ce qui n’est pas idéal pour les nouvelles requêtes. &#x200B; À la place, un autre statut, tel que « Ne sera pas résolu », doit être choisi. &#x200B; La vidéo indique également qu’aucun statut « Rejeté » n’est fourni par défaut, mais qu’un administrateur ou une administratrice système peut en créer un si nécessaire. &#x200B;

>[!VIDEO](https://video.tv.adobe.com/v/3455013/?quality=12&learn=on&enablevpops)

## Principaux points à retenir

* **Processus d’approbation par défaut :** lors de la création d’une file d’attente des demandes, vous pouvez appliquer un processus d’approbation par défaut qui affecte automatiquement un processus d’approbation à chaque demande.
* **Modifications de statut au moment de l’approbation :** les demandes approuvées changent leur statut de « Nouvelle - approbation en attente » en « Nouvelle », ce qui permet aux personnes affectées de commencer à travailler dessus.
* **Erreur courante dans la gestion des rejets :** si une demande est rejetée, le statut reviendra à « Nouveau » en raison d&#39;un paramètre système par défaut dans le processus d&#39;approbation.
* **Statut recommandé pour les demandes rejetées :** au lieu de revenir au statut précédent (« Nouveau »), il est préférable de choisir un autre statut, tel que « Ne sera pas résolu », pour éviter toute confusion.
* **Options de statut personnalisé :** aucun statut « Rejeté » n’est fourni par défaut, mais un administrateur ou une administratrice système peut en créer un, si nécessaire, pour une meilleure clarté du processus d’approbation.


## Tutoriels recommandés sur cette rubrique

* [Déléguer des tâches, des problèmes et des approbations](/help/manage-work/approval-processes-and-milestone-paths/delegate-approvals.md)
* [Comprendre les processus d’approbation propres à chaque groupe](/help/administration-and-setup/approval-processes-and-milestone-paths/group-specific-approval-processes.md)
* [Créer un flux de demandes](/help/manage-work/request-queues/create-a-request-flow.md)
* [Créer un processus de validation global et à usage unique](https://experienceleague.adobe.com/en/docs/workfront-learn/tutorials-workfront/manage-work/approval-processes-and-milestone-paths/create-a-single-use-approval-process)
