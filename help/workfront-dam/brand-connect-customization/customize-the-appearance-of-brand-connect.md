---
title: Personnaliser l’apparence de [!UICONTROL Brand Connect]
description: Découvrez comment personnaliser la barre de navigation et le pied de page, ainsi que la page d’accueil et la page de connexion dans [!UICONTROL Brand Connect] pour [!UICONTROL Workfront DAM].
activity: use
feature: Digital Content and Documents
type: Tutorial
role: User
level: Beginner
team: Technical Marketing
jira: KT-8980
exl-id: cf286347-46f0-4a7a-9f06-921975f28765
doc-type: video
source-git-commit: d17df7162ccaab6b62db34209f50131927c0a532
workflow-type: ht
source-wordcount: '373'
ht-degree: 100%

---

# Personnaliser l’apparence de [!UICONTROL Brand Connect]

Dans cette vidéo, vous apprendrez à :

* Personnaliser la barre de navigation et le pied de page
* Personnaliser la page d’accueil et la page de connexion

>[!VIDEO](https://video.tv.adobe.com/v/335242/?quality=12&learn=on&enablevpops)

## Paramètre d’[!UICONTROL Apparence] supplémentaire

L’option [!UICONTROL Police de caractères] dans le menu [!UICONTROL Apparence] permet de mettre en forme l’ensemble du texte de votre [!UICONTROL Brand Portal] avec la police sélectionnée. Plus de 800 polices Google sont prises en charge.

![L’option [!UICONTROL Police] dans le menu [!UICONTROL Apparence] pour le [!UICONTROL Brand Portal]](assets/02-brand-connect-appearance-font.png)

## Widgets de page d’accueil

Personnalisez l’aspect de votre page d&#39;accueil [!UICONTROL Brand Connect] pour qu’il corresponde à votre organisation. Les widgets permettent d’ajouter des éléments tels que des dossiers et des diaporamas d’images. Si votre organisation comporte plusieurs [!UICONTROL Brand Connects], chacun possède sa propre page d’accueil, dont vous pouvez modifier l’aspect.

![Capture d’écran des widgets disponibles pour votre page d’accueil [!UICONTROL Brand Connect] ](assets/03-brand-connect-home-page-widgets.png)

Ces widgets sont disponibles :

**A. Carrousel** - Affiche plusieurs ressources dans un diaporama d’images. Vous pouvez ajouter des descriptions à chaque ressource. Cliquez sur l’icône Ajouter pour sélectionner les images à afficher dans le carrousel.

**B. Dossier** - Affiche un dossier contenant les ressources sélectionnées. Cliquez sur l’icône Ajouter pour ouvrir le [!UICONTROL Sélecteur de ressources] afin de sélectionner un dossier. Les ressources présentes dans le dossier sont visibles pour les utilisateurs et utilisatrices [!UICONTROL Brand Connect] mais ne peuvent être téléchargées que par les utilisateurs et utilisatrices autorisés.

**C. Lightbox** - Affiche une [!UICONTROL Lightbox] existante. Les ressources dans la [!UICONTROL Lightbox] sont visibles pour les utilisateurs et utilisatrices [!UICONTROL Brand Connect], mais ne peuvent être téléchargées que par les utilisateurs et utilisatrices autorisés.

**D. Directives relatives aux marques** - Affiche les directives relatives aux marques sur la page d’accueil dans la barre de navigation supérieure.

**E. Description** - Permet d’afficher des élément de texte courts.

**F. Description renseignée** - Crée un bloc de copie de texte avec un arrière-plan gris.

**G. HTML** - Permet d’utiliser de l’HTML et du CSS pour créer du contenu personnalisé. Par exemple, vous pouvez intégrer un lien vers une vidéo. Quelques [balises HTML sont à éviter](https://www.damsuccess.com/hc/en-us/articles/206170043-Brand-Connect-Admin-Guide#html).

## Ajouter une barre de recherche

Si vous concevez une page d’accueil personnalisée pour le [!UICONTROL Brand Connect] de votre organisation, les utilisateurs et utilisatrices doivent cliquer sur la zone [!UICONTROL Ressources] pour effectuer une recherche.

Cependant, les administrateurs et administratrices système peuvent créer une barre de recherche à l’aide du widget HTML et de la balise HTML suivante :

&lt;webdambp.headersearch>&lt;/webdambp.headersearch>
