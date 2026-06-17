---
title: Appliquer un processus d’approbation des problèmes dans une file d’attente des demandes
description: Mettez en œuvre un processus d’approbation par défaut pour rationaliser les workflows des demandes, en veillant à ce que les demandes approuvées passent de manière appropriée au statut « Nouveau ». Dissipez la confusion concernant les demandes rejetées en sélectionnant un changement de statut sur « Impossible de résoudre ».
activity: use
feature: Approvals
thumbnail: 335225.jpeg
type: Tutorial
role: User
level: Intermediate
team: Technical Marketing
jira: KT-17578
last-substantial-update: '2025-03-26T00:00:00.000Z'
recommendations: noDisplay,catalog
doc-type: video
exl-id: 9200eeb4-db5d-45c1-9b17-28c6ca04de2d
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
subfeature_v2:
  - id: c10f2e93-7a58-4212-aa24-684c265ebe76
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
autotag-review: '2026-05-06T15:58:59.618Z'
source-git-commit: f0f541bf3fd6db69e6d813cf81456a5df6848d49
workflow-type: tm+mt
source-wordcount: 291
ht-degree: 84%

---

# Appliquer un processus d’approbation des problèmes dans une file d’attente des demandes

>[!PREREQUISITES]
>
>* [Création d’un flux de demandes dans Workfront](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/request-queues/create-a-request-flow)
>* [Créer et gérer des processus de validation](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/approval-processes-and-milestone-paths/create-a-single-use-approval-process)


La vidéo explique le processus d’application d’un processus d’approbation par défaut lors de la création d’une file d’attente de demandes. &#x200B; Lorsqu&#39;une demande est créée, elle commence avec le statut « Nouveau - Approbation en attente » et une notification d&#39;approbation est envoyée à l&#39;approbateur désigné. &#x200B; En cas d’approbation, le statut passe à « Nouveau », ce qui permet aux personnes affectées de commencer le travail. &#x200B; En cas de rejet, le statut peut revenir incorrectement à « Nouveau » en raison d&#39;une erreur courante dans la configuration du processus d&#39;approbation. &#x200B;
La vidéo montre que le processus d’approbation est déclenché lorsque le statut est défini sur « Nouveau », qui est le statut par défaut des nouvelles demandes. &#x200B; En cas de rejet, le système redéfinit par défaut le statut sur le précédent, ce qui n’est pas idéal pour les nouvelles requêtes. &#x200B;, choisissez plutôt un autre statut, tel que « Ne sera pas résolu ». &#x200B; La vidéo note également qu’aucun statut « Rejeté » n’est fourni par défaut, mais qu’un administrateur système peut en créer un si nécessaire. &#x200B;

>[!VIDEO](https://video.tv.adobe.com/v/3455013/?quality=12&learn=on&enablevpops=1)

## Points essentiels à retenir

* **Processus d’approbation par défaut :** lors de la création d’une file d’attente des demandes, vous pouvez appliquer un processus d’approbation par défaut qui affecte automatiquement un processus d’approbation à chaque demande.
* **Modifications de statut au moment de l’approbation :** les demandes approuvées changent leur statut de « Nouveau - approbation en attente » en « Nouveau », ce qui permet aux personnes affectées de commencer à travailler dessus.
* **Erreur courante dans la gestion des rejets :** si une demande est rejetée, le statut revient à « Nouveau » en raison d’un paramètre système par défaut dans le processus d’approbation.
* **Statut recommandé pour les demandes rejetées :** au lieu de revenir au statut précédent (« Nouveau »), il est préférable de choisir un autre statut, tel que « Impossible de résoudre », pour éviter toute confusion.
* **Options de statut personnalisé :** aucun statut « Rejeté » n’est fourni par défaut, mais un administrateur ou une administratrice système peut en créer un, si nécessaire, pour une meilleure clarté du processus d’approbation.


## Tutoriels recommandés sur cette rubrique

* [Déléguer efficacement les tâches, événements et approbations](/help/manage-work/approval-processes-and-milestone-paths/delegate-approvals.md)
* [Comprendre les processus d’approbation propres à chaque groupe](/help/administration-and-setup/approval-processes-and-milestone-paths/group-specific-approval-processes.md)
* [Création d’un flux de demandes dans Workfront](/help/manage-work/request-queues/create-a-request-flow.md)
* [Créer et gérer des processus de validation](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/approval-processes-and-milestone-paths/create-a-single-use-approval-process)
