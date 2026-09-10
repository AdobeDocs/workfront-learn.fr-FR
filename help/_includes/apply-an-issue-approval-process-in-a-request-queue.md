---
source-git-commit: b150105844a42e06f5e96f787ad62a1b62185f91
workflow-type: tm+mt
source-wordcount: '385'
ht-degree: 51%

---
# Appliquer un processus d&#39;approbation des événements dans une file d&#39;attente des demandes - PARTAGÉ

>[!PREREQUISITES]
>
>* [Création d’un flux de demandes dans Workfront](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/request-queues/create-a-request-flow)
>* [Créer et gérer des processus de validation](https://experienceleague.adobe.com/fr/docs/workfront-learn/tutorials-workfront/manage-work/approval-processes-and-milestone-paths/create-a-single-use-approval-process)


La vidéo explique le processus d’application d’un processus d’approbation par défaut lors de la création d’une file d’attente de demandes. &#x200B; Lorsqu&#39;une demande est créée, elle commence avec le statut « Nouveau - Approbation en attente » et une notification d&#39;approbation est envoyée à l&#39;approbateur désigné. &#x200B; En cas d’approbation, le statut passe à « Nouveau », ce qui permet aux personnes affectées de commencer le travail. &#x200B; En cas de rejet, le statut peut revenir incorrectement à « Nouveau » en raison d&#39;une erreur courante dans la configuration du processus d&#39;approbation. &#x200B;
La vidéo montre que le processus d’approbation est déclenché lorsque le statut est défini sur « Nouveau », qui est le statut par défaut des nouvelles demandes. &#x200B; En cas de rejet, le système redéfinit par défaut le statut sur le précédent, ce qui n’est pas idéal pour les nouvelles requêtes. &#x200B;, choisissez plutôt un autre statut, tel que « Ne sera pas résolu ». &#x200B; La vidéo indique également qu’aucun statut « Rejeté » n’est fourni par défaut, mais qu’un administrateur ou une administratrice système peut en créer un si nécessaire. &#x200B;

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

