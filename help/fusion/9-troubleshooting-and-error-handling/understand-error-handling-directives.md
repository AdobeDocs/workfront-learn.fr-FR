---
title: Présentation des directives de gestion des erreurs
description: Découvrez les directives de gestionnaire d’erreurs qui permettent à l’exécution de continuer et celles qui arrêtent l’exécution dans  [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
jira: KT-9064
exl-id: cb8d0880-73d2-4118-b800-a126f8509309
recommendations: noDisplay,catalog
doc-type: video
source-git-commit: bbdf99c6bc1be714077fd94fc3f8325394de36b3
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 100%

---

# Présentation des directives de gestion des erreurs

Dans cette vidéo, vous apprendrez :

* Les trois directives de gestionnaire d’erreurs qui permettent à l’exécution de continuer
* Les deux directives de gestionnaire d’erreurs qui arrêtent l’exécution

>[!VIDEO](https://video.tv.adobe.com/v/335305/?quality=12&learn=on&enablevpops=1)

## Directives - Le scénario continue

### Reprendre

* Une sortie de substitution est spécifiée et fournie au module qui rencontre une erreur.
* Les modules suivants sont traités.
* Le statut d’exécution du scénario est marqué comme « succès ».

![Image d’une directive Reprendre](assets/troubleshooting-and-error-handling-2.png)

### Interrompre

* Le statut de l’exécution du scénario est stocké dans la file d’attente des exécutions incomplètes où l’erreur peut être résolue manuellement. Quelques exceptions sont mentionnées ici.
* Les modules suivants ne sont pas traités.
* S’il existe des bundles non traités, l’exécution du scénario se poursuit normalement.
* Le statut d’exécution du scénario est marqué comme « avertissement ».

![Image d’une directive Interrompre](assets/troubleshooting-and-error-handling-3.png)

### Ignorer

* L’erreur est ignorée et les modules suivants ne sont pas traités.
* S’il existe des bundles non traités, l’exécution du scénario se poursuit normalement.
* Le statut d’exécution du scénario est marqué comme « succès ».

![Image d’une directive Ignorer](assets/troubleshooting-and-error-handling-4.png)

## Directives - Arrêt du scénario

### Restauration

* L’exécution du scénario s’arrête immédiatement et une phase de restauration démarre sur tous les modules afin de tenter de rétablir leur état initial.
* Les modules suivants ne sont pas traités.
* À l’exception de certains types d’erreur, le scénario est désactivé après le « nombre d’erreurs consécutives » spécifié dans les paramètres du scénario.
* Le statut d’exécution du scénario est marqué comme « erreur ».

>[!NOTE]
>
>Il s’agit du comportement par défaut si aucun itinéraire de gestionnaire d’erreurs n’est associé au module et que le paramètre « Autoriser le stockage des exécutions incomplètes » dans Paramètres du scénario n’est pas coché.

![Image d’une directive Restaurer](assets/troubleshooting-and-error-handling-5.png)

### Valider

* L’erreur est ignorée et les modules suivants ne sont pas traités.
* S’il existe des bundles non traités, l’exécution du scénario se poursuit normalement.
* Le statut d’exécution du scénario est marqué comme « succès ».

![Image d’une directive Valider](assets/troubleshooting-and-error-handling-6.png)
