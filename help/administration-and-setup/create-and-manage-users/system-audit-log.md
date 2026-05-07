---
title: Comprendre le journal d’audit du système
description: Découvrez comment utiliser le journal d’audit du système pour vérifier à quel moment des modifications ont été apportées et les éléments concernés.
feature: System Setup and Administration
activity: deploy
type: Tutorial
team: Technical Marketing
role: Admin
level: Beginner, Intermediate
thumbnail: 10040.jpeg
jira: KT-10040
exl-id: 9de6fd40-10fb-47a6-b186-3a38c411f1ac
TQID: https://experienceleague.adobe.com/xMxWQ53TUXVjS-H8EuK3nf7jt8v4vUgKoZVsmApc-JM
product_v2: id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
feature_v2: id: d968a1bc-9a90-4926-a531-bcf272c32aad
role_v2: id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
level_v2: id: b5a62a22-46f7-4f0d-b151-3fc640bef588id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2: id: d095671a-1355-40aa-8b5f-06c33c68080bid: eddd9b14-83bd-4ff4-9072-54a4a484abb7
source-git-commit: 36674ed53c8645f556862bb2d99f3bfd6c993c1e
workflow-type: tm+mt
source-wordcount: 267
ht-degree: 100%

---

# Comprendre le journal d’audit du système

Le journal d’audit du système est le meilleur moyen pour l’administrateur ou l’administratrice système de garder un œil sur ce qui se passe dans [!DNL Workfront]. Considérez le journal comme votre source de vérité pour connaître l’identité des personnes qui ont effectué tel ou tel changement et le moment où cela a été réalisé.

Accédez au journal d’audit en allant à la section [!UICONTROL Préférences] de la zone [!UICONTROL Configuration]. Par défaut, les données des sept derniers jours s’affichent. Modifiez les critères de filtre pour afficher les données de périodes différentes.

Lorsqu’un utilisateur ou une utilisatrice effectue certaines actions, [!UICONTROL Workfront] les enregistre dans la section [!UICONTROL Journaux d’audit] de la zone [!UICONTROL Configuration].

Le menu déroulant ![[!UICONTROL Type de journal], sur la page [!UICONTROL Journaux d’audit] dans [!UICONTROL Configuration]](assets/admin-fund-audit-log-1.png)

Chaque action enregistrée, ou consignée, affiche :

* La date et l’heure de la modification
* Le type de journal
* Le nom de l’utilisateur ou l’utilisatrice qui a effectué l’action
* L’objet
* Tout détail associé à l’action
* L’adresse IP

Liste du ![[!UICONTROL Journal d’audit]](assets/admin-fund-audit-log-2.JPG)

## Exporter le journal d’audit

L’export des données du journal d’audit permet aux équipes d’administration système de partager les informations avec des auditeurs et auditrices internes/externes ou des spécialistes de la sécurité. Certaines organisations exigent que certains journaux soient conservés pour se conformer aux réglementations en matière de cybersécurité. D’autres ont besoin que les informations soient importées dans un système de sécurité pour analyse.

Les journaux d’audit peuvent être exportés dans un fichier CSV (valeurs séparées par des virgules), qui peut être ouvert dans un tableur ou un éditeur de texte. L’export étant limité à 50 000 lignes à la fois, utilisez les filtres pour réduire la liste si le total dépasse ce chiffre.

Bouton ![[!UICONTROL Exporter] sur la page [!UICONTROL Journaux d’audit]](assets/admin-fund-audit-log-3.png)

<!--
learn more URLs
Audit logs
Managing audit logs
-->
