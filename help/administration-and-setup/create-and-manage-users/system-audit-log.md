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
source-git-commit: 4568e4e47b719e2dee35357d42674613112a9c43
workflow-type: ht
source-wordcount: '265'
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
