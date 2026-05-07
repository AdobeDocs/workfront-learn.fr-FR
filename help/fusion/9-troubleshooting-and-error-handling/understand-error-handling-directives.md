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
product_v2: id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2: id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
subfeature_v2: id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
autotag-review: '2026-05-06T16:07:23.288Z'
source-git-commit: 9f00285646af281d6c4d93eb792f4c38eedefb40
workflow-type: tm+mt
source-wordcount: 318
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
