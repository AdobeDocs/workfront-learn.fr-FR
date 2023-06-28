---
title: Présentation du journal d’audit du système
description: Découvrez comment utiliser le journal d’audit du système pour vérifier quand des modifications ont été apportées et quand ajouter des éléments.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Beginner, Intermediate
thumbnail: 10040.jpeg
jira: KT-10040
exl-id: 9de6fd40-10fb-47a6-b186-3a38c411f1ac
source-git-commit: a25a49e59ca483246271214886ea4dc9c10e8d66
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 0%

---

# Présentation du journal d’audit système

Le journal d’audit du système est le meilleur moyen pour l’administrateur système de garder un oeil sur ce qui se passe dans [!DNL Workfront]. Considérez le journal comme votre source de vérité pour qui a fait ce qui change et quand.

Accédez au journal d’audit en accédant à la [!UICONTROL Préférences] dans la section [!UICONTROL Configuration] zone. Par défaut, les données des sept derniers jours s’affichent. Modifiez les critères de filtre pour afficher les données de différentes périodes.

Lorsqu’un utilisateur effectue certaines actions, [!UICONTROL Workfront] les enregistre dans la variable [!UICONTROL Journaux d’audit] de la section [!UICONTROL Configuration] zone.

![[!UICONTROL Type de journal] du menu déroulant [!UICONTROL Journaux d’audit] page [!UICONTROL Configuration]](assets/admin-fund-audit-log-1.png)

Chaque action enregistrée, ou consignée, affiche :

* Date et heure de la modification
* Type de journal
* Nom de l’utilisateur qui a terminé l’action.
* Objet
* Tout détail associé à l’action
* L’adresse IP

![[!UICONTROL Journal d’audit] list](assets/admin-fund-audit-log-2.JPG)

## Exporter le journal d’audit

L’export des données du journal d’audit permet aux administrateurs système de partager les informations avec les réviseurs internes/externes ou les spécialistes de la sécurité. Certaines organisations exigent que certains logs soient conservés pour être conformes aux réglementations de cybersécurité. D&#39;autres ont besoin que les informations soient importées dans un système de sécurité pour analyse.

Les journaux d’audit peuvent être exportés dans un fichier CSV (valeur séparée par des virgules), qui peut être ouvert dans une application de feuille de calcul ou un éditeur de texte brut. L’exportation étant limitée à 50 000 lignes à la fois, utilisez les filtres pour réduire la liste si le total dépasse 50 000 lignes.

![[!UICONTROL Exporter] bouton [!UICONTROL Journaux d’audit] page](assets/admin-fund-audit-log-3.png)

<!---
learn more URLs
Audit logs
Managing audit logs
--->
