---
title: Eenvoudig vlakdiagram
description: Eenvoudig vlakdiagram.
author: mihart
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-desktop
ms.topic: conceptual
ms.date: 05/05/2020
ms.author: rien
LocalizationGroup: Visualizations
ms.openlocfilehash: 18d16440e8894e69101357af700c9b295eaa30c6
ms.sourcegitcommit: a199dda2ab50184ce25f7c9a01e7ada382a88d2c
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 05/06/2020
ms.locfileid: "82866953"
---
# <a name="create-and-use-basic-area-charts"></a>Eenvoudige vlakdiagrammen maken en gebruiken

[!INCLUDE[consumer-appliesto-nyyn](../includes/consumer-appliesto-nyyn.md)]

[!INCLUDE [power-bi-visuals-desktop-banner](../includes/power-bi-visuals-desktop-banner.md)]

Het eenvoudige vlakdiagram (ook wel gelaagd vlakdiagram genoemd) is gebaseerd op het lijndiagram. Het gebied tussen as en lijn wordt gevuld met kleuren om het volume aan te geven. 

Vlakdiagrammen benadrukken de mate van wijzigingen in de loop van de tijd en kunnen worden gebruikt om de aandacht te vestigen op de totale waarde voor een trend. Gegevens die bijvoorbeeld de winst in de loop van de tijd voorstellen, kunnen worden afgezet in een vlakdiagram om de totale winst te benadrukken.

![](media/power-bi-visualization-basic-area-chart/power-bi-chart-example.png)

> [!NOTE]
> Voor het delen van uw rapport met een Power BI-collega moeten u beiden beschikken over een afzonderlijke Power BI Pro-licentie of moet het rapport zijn opgeslagen in Premium-capaciteit.

## <a name="when-to-use-a-basic-area-chart"></a>Wanneer wordt een eenvoudig vlakdiagram gebruikt?
In de volgende gevallen komen eenvoudige vlakdiagrammen goed van pas:

* om de volumetrend in een tijdreeks te bekijken en te vergelijken 
* voor afzonderlijke reeksen die een fysiek telbare verzameling voorstellen

### <a name="prerequisites"></a>Vereisten
In deze zelfstudie wordt gebruikgemaakt van het [PBIX-bestand met het voorbeeld van een retailanalyse](https://download.microsoft.com/download/9/6/D/96DDC2FF-2568-491D-AAFA-AFDD6F763AE3/Retail%20Analysis%20Sample%20PBIX.pbix).

1. Selecteer linksboven in de menubalk **Bestand** > **Openen**
   
2. Ga naar uw kopie van het **PBIX-bestand met het voorbeeld van een retailanalyse**

1. Open het **PBIX-bestand met het voorbeeld van een retailanalyse** in de rapportweergave ![Schermopname van het pictogram voor de rapportweergave.](media/power-bi-visualization-kpi/power-bi-report-view.png)

1. Selecteren ![Schermopname van het gele tabblad.](media/power-bi-visualization-kpi/power-bi-yellow-tab.png) om een nieuwe pagina toe te voegen.


## <a name="create-a-basic-area-chart"></a>Een eenvoudig vlakdiagram maken
 

1. Deze stappen helpen u bij het maken van een vlakdiagram waarin de omzet van dit jaar en die van vorig jaar per maand worden weergegeven.
   
   a. Selecteer in het deelvenster Velden achtereenvolgens **Verkoop \> Omzet vorig jaar** en **Omzet dit jaar > Waarde**.

   ![gegevenswaarden vlakdiagram](media/power-bi-visualization-basic-area-chart/power-bi-bar-chart.png)

   b.  Converteer het diagram naar een elementair vlakdiagram door het pictogram Vlakdiagram te selecteren in het deelvenster Visualisaties.

   ![pictogram vlakdiagram](media/power-bi-visualization-basic-area-chart/convertchart.png)
   
   c.  Selecteer **Tijd \> FiscalMonth** om deze waarde toe te voegen aan de bron **As**.   
   ![waarden voor assen vlakdiagram](media/power-bi-visualization-basic-area-chart/powerbi-area-chartnew.png)
   
   d.  Selecteer het beletselteken (rechtsboven in het visuele element) en kies **Sorteren op maand** om de waarden in de grafiek per maand weer te geven. Als u de sorteervolgorde wilt wijzigen, selecteert u het beletselteken opnieuw en selecteert u **Oplopend sorteren** of **Aflopend sorteren**.

## <a name="highlighting-and-cross-filtering"></a>Markeren en kruislings filteren
Zie [Een filter aan een rapport toevoegen](../power-bi-report-add-filter.md) voor meer informatie over het gebruik van het deelvenster Filters.

Selecteer een bepaald gebied of de bovenrand ervan in uw diagram als u dat gebied wilt markeren.  Als er zich in tegenstelling tot andere visualisatietypen andere visualisaties op dezelfde pagina bevinden, worden andere visualisaties op de rapportpagina niet kruislings gefilterd wanneer er een eenvoudige vlakdiagrammen worden gemarkeerd. Vlakdiagrammen zijn echter wel een doel voor kruislings filteren dat door andere visualisaties op de rapportpagina wordt geactiveerd. 

1. Probeer het uit door uw vlakdiagram te selecteren en te kopiëren naar de rapportpagina **Analyse van nieuwe winkels** (Ctrl+C en Ctrl+V).
2. Selecteer een van de gearceerde gebieden in het valkdiagram en selecteer vervolgens het andere gearceerde gebied. U ziet geen gevolgen voor de andere visualisaties op de pagina.
1. Selecteer nu een element. U ziet de gevolgen voor het vlakdiagram, dat kruislings wordt gefilterd.

    ![Voorbeelden van filter](media/power-bi-visualization-basic-area-chart/power-bi-area-chart-filters.gif) 

Zie [Interacties van visuals in rapporten](../service-reports-visual-interactions.md) voor meer informatie.


## <a name="considerations-and-troubleshooting"></a>Aandachtspunten en probleemoplossing   
* [Het rapport toegankelijker maken voor mensen met beperkingen](../desktop-accessibility.md)
* Met eenvoudige vlakdiagrammen kunnen waarden die het gevolg zijn van bedekking op de gelaagde vlakken niet effectief worden vergeleken. Power BI maakt gebruik van transparantie om de overlapping van gebieden aan te geven. Dit werkt echter alleen goed met twee of drie verschillende vlakken. Als u trends voor drie of meer metingen wilt vergelijken, kunt u lijndiagrammen gebruiken. Als u volumes voor drie of meer metingen wilt vergelijken, kunt u treemapgrafieken gebruiken.

## <a name="next-step"></a>Volgende stap
[Rapporten in Power BI](power-bi-visualization-card.md)  

