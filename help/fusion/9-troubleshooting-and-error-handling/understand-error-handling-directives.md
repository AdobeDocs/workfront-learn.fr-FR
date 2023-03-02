---
title: Comprendre les directives de gestion des erreurs
description: Découvrez les directives de gestionnaire d’erreurs qui permettent à l’exécution de continuer et celles qui arrêtent l’exécution, dans [!DNL Adobe Workfront Fusion].
activity: use
team: Technical Marketing
type: Tutorial
feature: Workfront Fusion
role: User
level: Beginner
kt: 9064
exl-id: cb8d0880-73d2-4118-b800-a126f8509309
doc-type: video
source-git-commit: d39754b619e526e1a869deedb38dd2f2b43aee57
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 0%

---

# Comprendre les directives de gestion des erreurs

Dans cette vidéo, vous apprendrez :

* Les trois directives de gestionnaire d’erreurs qui permettent à l’exécution de continuer
* Les deux directives de gestionnaire d’erreurs qui arrêtent l’exécution

>[!VIDEO](https://video.tv.adobe.com/v/335305/?quality=12)

## Directives - Le scénario se poursuit

### Reprendre

* Une sortie de substitution est spécifiée et fournie au module qui rencontre une erreur.
* Les modules suivants sont traités.
* L’état d’exécution du scénario est marqué comme &quot;succès&quot;.

![Image d’une directive Reprendre](assets/troubleshooting-and-error-handling-2.png)

### Rompre

* L’état de l’exécution du scénario est stocké dans la file d’attente des exécutions incomplètes où l’erreur peut être résolue manuellement. Il y a cependant quelques exceptions qui sont mentionnées ici.
* Les modules suivants ne sont pas traités.
* S’il existe des lots non traités, l’exécution du scénario se poursuit normalement.
* L’état d’exécution du scénario est marqué comme &quot;avertissement&quot;.

![Image d’une directive Break](assets/troubleshooting-and-error-handling-3.png)

### Ignorer

* L’erreur est ignorée et les modules suivants ne sont pas traités.
* S’il existe des lots non traités, l’exécution du scénario se poursuit normalement.
* L’état d’exécution du scénario est marqué comme &quot;succès&quot;.

![Image d’une directive Ignorer](assets/troubleshooting-and-error-handling-4.png)

## Directives — Arrêt du scénario

### Retour arrière

* L’exécution du scénario est arrêtée immédiatement et une phase de restauration est lancée sur tous les modules afin de tenter de rétablir leur état initial.
* Les modules suivants ne sont pas traités.
* Sauf quelques types d’erreur, le scénario est désactivé après le &quot;nombre d’erreurs consécutives&quot; spécifié dans les paramètres du scénario.
* L’état d’exécution du scénario est marqué comme &quot;erreur&quot;.

>[!NOTE]
>
>Il s’agit du comportement par défaut si aucun itinéraire de gestionnaire d’erreurs n’est associé au module et que le paramètre &quot;Autoriser le stockage des exécutions incomplètes&quot; sous Paramètres du scénario n’est pas coché.

![Image d’une directive de restauration](assets/troubleshooting-and-error-handling-5.png)

### Valider

* L’erreur est ignorée et les modules suivants ne sont pas traités.
* S’il existe des lots non traités, l’exécution du scénario se poursuit normalement.
* L’état d’exécution du scénario est marqué comme &quot;succès&quot;.

![Image d’une directive de validation](assets/troubleshooting-and-error-handling-6.png)
