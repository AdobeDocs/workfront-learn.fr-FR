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
last-substantial-update: 2025-03-26T00:00:00Z
recommendations: noDisplay,catalog
doc-type: video
exl-id: 9200eeb4-db5d-45c1-9b17-28c6ca04de2d
source-git-commit: bbdf99c6bc1be714077fd94fc3f8325394de36b3
workflow-type: ht
source-wordcount: '376'
ht-degree: 100%

---

# Appliquer un processus d’approbation des problèmes dans une file d’attente des demandes

>[!PREREQUISITES]
>
>* [Créer un flux de demandes](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/request-queues/create-a-request-flow)
>* [Créer un processus d’approbation global et à usage unique](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/approval-processes-and-milestone-paths/create-a-single-use-approval-process)


La vidéo explique l’application d’un processus d’approbation par défaut lors de la création d’une file d’attente des demandes. Lorsqu’une demande est créée, elle commence avec le statut « Nouveau - Approbation en attente » et une notification d’approbation est envoyée à la personne en charge de l’approbation. Si elle est approuvée, le statut passe à « Nouveau », ce qui permet aux personnes affectées de commencer le travail. En cas de rejet, le statut peut revenir incorrectement à « Nouveau » en raison d’une erreur courante dans la configuration du processus d’approbation. 
La vidéo montre que le processus d’approbation est déclenché lorsque le statut est défini sur « Nouveau », qui est le statut par défaut des nouvelles demandes. En cas de rejet, le système redéfinit par défaut le statut sur le précédent, ce qui n’est pas idéal pour les nouvelles demandes. À la place, un autre statut, tel que « Impossible de résoudre », doit être choisi. La vidéo indique également qu’aucun statut « Rejeté » n’est fourni par défaut, mais qu’un administrateur ou une administratrice système peut en créer un si nécessaire.

>[!VIDEO](https://video.tv.adobe.com/v/3455013/?quality=12&learn=on&enablevpops=1)

## Points clés à retenir

* **Processus d’approbation par défaut :** lors de la création d’une file d’attente des demandes, vous pouvez appliquer un processus d’approbation par défaut qui affecte automatiquement un processus d’approbation à chaque demande.
* **Modifications de statut au moment de l’approbation :** les demandes approuvées changent leur statut de « Nouveau - approbation en attente » en « Nouveau », ce qui permet aux personnes affectées de commencer à travailler dessus.
* **Erreur courante dans la gestion des rejets :** si une demande est rejetée, le statut revient à « Nouveau » en raison d’un paramètre système par défaut dans le processus d’approbation.
* **Statut recommandé pour les demandes rejetées :** au lieu de revenir au statut précédent (« Nouveau »), il est préférable de choisir un autre statut, tel que « Impossible de résoudre », pour éviter toute confusion.
* **Options de statut personnalisé :** aucun statut « Rejeté » n’est fourni par défaut, mais un administrateur ou une administratrice système peut en créer un, si nécessaire, pour une meilleure clarté du processus d’approbation.


## Tutoriels recommandés sur cette rubrique

* [Déléguer des tâches, des problèmes et des approbations](/help/manage-work/approval-processes-and-milestone-paths/delegate-approvals.md)
* [Comprendre les processus d’approbation propres à chaque groupe](/help/administration-and-setup/approval-processes-and-milestone-paths/group-specific-approval-processes.md)
* [Créer un flux de demandes](/help/manage-work/request-queues/create-a-request-flow.md)
* [Créer un processus d’approbation global et à usage unique](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/approval-processes-and-milestone-paths/create-a-single-use-approval-process)
