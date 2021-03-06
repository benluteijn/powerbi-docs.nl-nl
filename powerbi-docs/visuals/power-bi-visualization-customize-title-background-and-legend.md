---
title: Aan de slag met het opmaken van Power BI-visualisaties
description: De titel, achtergrond en legenda van een visualisatie aanpassen
author: mihart
ms.reviewer: ''
featuredvideoid: IkJda4O7oGs
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: conceptual
ms.date: 03/06/2020
ms.author: mihart
LocalizationGroup: Visualizations
ms.openlocfilehash: 7ff02eb07d4b052892cc80ab4710223d8d302a9f
ms.sourcegitcommit: 7aa0136f93f88516f97ddd8031ccac5d07863b92
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 05/05/2020
ms.locfileid: "78893431"
---
# <a name="customize-visualization-titles-backgrounds-and-legends"></a>Titels, legenda's en achtergronden van visualisaties aanpassen

In deze zelfstudie leert u een aantal verschillende manieren om uw visualisaties aan te passen. Er zijn heel veel mogelijkheden voor het aanpassen van uw visualisaties. De beste manier om ze allemaal te leren is door het deelvenster **Indeling** te verkennen (selecteer het pictogram van een verfroller). Dit artikel helpt u op weg door te laten zien hoe u de titel, legenda en achtergrond van een visualisatie kunt aanpassen en een thema kunt toevoegen.

U kunt niet alle visualisaties aanpassen. Zie de [volledige lijst](#visualization-types-that-you-can-customize) met visualisaties voor meer informatie.


## <a name="prerequisites"></a>Vereisten

- De Power BI-service of Power BI Desktop

- Het rapport Voorbeeld van een retailanalyse

## <a name="customize-visualization-titles-in-reports"></a>Visualisatietitels in rapporten aanpassen

Als u mee wilt doen, meld u dan aan bij Power BI Desktop en open het rapport [Voorbeeld van een retailanalyse](../sample-datasets.md).

> [!NOTE]
> Wanneer u een visualisatie aan een dashboard vastmaakt, wordt deze dashboardtegel. U kunt ook de tegels zelf aanpassen met [nieuwe titels, ondertitels en hyperlinks, en het formaat ervan kan worden gewijzigd](../service-dashboard-edit-tile.md).

1. Ga naar de pagina **New Stores** van het rapport **Voorbeeld van een retailanalyse**.

1. Selecteer het gegroepeerde kolomdiagram **Open Store Count by Open Month and Chain**.

1. Selecteer in het deelvenster **Visualisaties** het verfrollerpictogram om de opmaakopties weer te geven.

1. Selecteer **Titel** om die sectie uit te vouwen.

   ![Schermopname van het deelvenster Indeling met het verfrollerpictogram omkaderd en een pijl naar de vervolgkeuzelijst Titel.](media/power-bi-visualization-customize-title-background-and-legend/power-bi-format-menu.png)

1. Zet de schuifregelaar **Titel** op **Aan**.

1. Als u de titel wilt wijzigen, typt u *Store count by month opened* in het veld **Titeltekst**.

    ![Schermopname van het deelvenster Indeling met de ingevoerde titeltekst.](media/power-bi-visualization-customize-title-background-and-legend/power-bi-title.png)

1. Wijzig **Tekenkleur** in wit en **Achtergrondkleur** in blauw.    

    a. Selecteer de vervolgkeuzelijst en kies een kleur bij **Themakleuren**, **Recente kleuren** en **Aangepaste kleur**.
    
    ![Schermopname van de opties voor tekenkleur en achtergrondkleur.](media/power-bi-visualization-customize-title-background-and-legend/power-bi-color.png)

    b. Selecteer de vervolgkeuzelijst om het kleurvenster te sluiten.


1. Vergroot de tekengrootte naar **16 pt**.

1. De laatste aanpassing van de grafiektitel die we doen is het uitlijnen ervan op het midden van de visualisatie.

    ![Schermopname van de uitlijningsopties met de optie Centreren geselecteerd.](media/power-bi-visualization-customize-title-background-and-legend/power-bi-align.png)

    Op dit punt in de zelfstudie ziet de titel van uw gegroepeerde kolomdiagram er ongeveer als volgt uit:

    ![Schermopname van het zojuist geconfigureerde gegroepeerd kolomdiagram.](media/power-bi-visualization-customize-title-background-and-legend/power-bi-table.png)

Sla de wijzigingen op die u hebt aangebracht en ga naar de volgende sectie.

Als u om wat voor reden dan ook alle wijzigingen omgedaan wilt maken, selecteert u **Standaardinstelling herstellen** onderaan het aanpassingsvenster **Titel**.

![Schermopname van de optie Standaardinstelling herstellen.](media/power-bi-visualization-customize-title-background-and-legend/power-bi-revert.png)

## <a name="customize-visualization-backgrounds"></a>Visualisatieachtergrond aanpassen

Vouw met hetzelfde gegroepeerde kolomdiagram geselecteerd de opties voor  **Achtergrond** uit.

1. Zet de schuifregelaar **Achtergrond** op **Aan**.

1. Selecteer de vervolgkeuzelijst en kies een grijze kleur.

1. Wijzig de waarde voor **Doorzichtigheid** in **74%** .

Op dit punt in de zelfstudie ziet de achtergrond van uw gegroepeerde kolomdiagram er ongeveer als volgt uit:

![Schermopname van het gegroepeerde kolomdiagram met de achtergrondkleur bijgewerkt.](media/power-bi-visualization-customize-title-background-and-legend/power-bi-background.png)

Sla de wijzigingen op die u hebt aangebracht en ga naar de volgende sectie.

Als u om wat voor reden dan ook alle wijzigingen omgedaan wilt maken, selecteert u **Standaardinstelling herstellen** onderaan het aanpassingsvenster **Achtergrond**.

## <a name="customize-visualization-legends"></a>Visualisatielegenda aanpassen

1. Open de rapportpagina **Overview** en selecteer de grafiek **Total Sales Variance by FiscalMonth and District Manager**.

1. Selecteer op het tabblad **Visualisaties** het pictogram met de verfroller om het deelvenster Indeling te openen.

1. Vouw de opties bij **Legenda** uit:

    ![Schermopname van de legendakaart.](media/power-bi-visualization-customize-title-background-and-legend/power-bi-legends.png)

1. Zet de schuifregelaar **Legenda** op **Aan**.

1. Verplaats de legenda naar de linkerkant van de visualisatie.

1. Voeg een legendatitel in door **Titel** op **Aan** te zetten.

1. Typ *Manager* in het veld **Legendanaam**.

1. Wijzig **Kleur** in zwart.

Sla de wijzigingen op die u hebt aangebracht en ga naar de volgende sectie.

Als u om wat voor reden dan ook alle wijzigingen omgedaan wilt maken, selecteert u **Standaardinstelling herstellen** onderaan het aanpassingsvenster **Legenda**.

## <a name="customize-colors-using-a-theme"></a>Kleuren aanpassen met behulp van een thema

Met rapportthema's past u ontwerpwijzigingen toe op uw hele rapport. U kunt bijvoorbeeld uw bedrijfskleuren gebruiken, pictogrammen veranderen of een nieuwe indeling van visuals toepassen. Wanneer u een rapportthema toepast, worden voor alle visuals in het rapport de kleuren en indeling van het geselecteerde thema gebruikt.

Als u een thema wilt toepassen op uw rapport, selecteert u **Thema wisselen** in de menubalk. Kies een thema.  In het onderstaande rapport wordt gebruikgemaakt van het thema **Zon**.

 
![Rapporteren met behulp van thema Zon van gele, oranje en rode elementen](media/power-bi-visualization-customize-title-background-and-legend/power-bi-theme.png)

## <a name="visualization-types-that-you-can-customize"></a>Visualisatietypen die kunnen worden aangepast

Hier ziet u een lijst van de visualisaties en de aanpassingsopties die per visualisatie beschikbaar zijn:

| Visualisatie | Titel | Achtergrond | Legenda |
|:--- |:--- |:--- |:--- |
| Gebied | Ja | Ja |Ja |
| Staafdiagram | Ja | Ja |Ja |
| Kaart | Ja | Ja |n.v.t. |
| Kaart met meerdere rijen | Ja | Ja | n.v.t. |
| Kolom | Ja | Ja | Ja |
| Keuzelijst met invoervak | Ja | Ja | Ja |
| Ringdiagram | Ja | Ja | Ja |
| Choropletenkaart | Ja | Ja | Ja |
| Trechterdiagram | Ja | Ja | n.v.t. |
| Meter | Ja | Ja | n.v.t. |
| Belangrijkste beïnvloeder | Ja | Ja | n.v.t. |
| KPI | Ja | Ja | n.v.t. |
| Lijn | Ja | Ja | Ja |
| Kaart | Ja | Ja | Ja |
| Matrix | Ja | Ja | n.v.t. |
| Cirkeldiagram | Ja | Ja | Ja |
| V&A | Ja | Ja | n.v.t. |
| Spreidingsdiagram | Ja | Ja | Ja |
| Vorm | Ja | Ja | Ja |
| Slicer | Ja | Ja | n.v.t. |
| Tabel | Ja | Ja | n.v.t. |
| Tekstvak | nee | Ja | n.v.t. |
| Treemap | Ja | Ja | Ja |
| Waterval | Ja | Ja | Ja |

## <a name="next-steps"></a>Volgende stappen

- [Eigenschappen van x-as en y-as aanpassen](power-bi-visualization-customize-x-axis-and-y-axis.md)

- [Aan de slag met de kleuropmaak en de eigenschappen van assen](service-getting-started-with-color-formatting-and-axis-properties.md)

Nog vragen? [Misschien dat de Power BI-community het antwoord weet](https://community.powerbi.com/)
