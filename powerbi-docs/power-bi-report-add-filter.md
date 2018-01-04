---
title: Een visualisatie-, pagina-, drillthrough- of rapportfilter aan een rapport toevoegen
description: Een paginafilter, visualisatiefilter of rapportfilter aan rapport in Power BI toevoegen
services: powerbi
documentationcenter: 
author: mihart
manager: kfile
backup: 
editor: 
tags: 
qualityfocus: monitoring
qualitydate: 
ms.service: powerbi
ms.devlang: NA
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: powerbi
ms.date: 10/28/2017
ms.author: mihart
ms.openlocfilehash: d409633129c6c203e897d76c0acf043bf09ea29d
ms.sourcegitcommit: 99cc3b9cb615c2957dde6ca908a51238f129cebb
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 11/13/2017
---
# <a name="add-a-filter-to-a-power-bi-report-in-editing-view"></a>Een filter aan een Power BI-filter toevoegen (in de bewerkingsweergave)
> [!TIP]
> U wordt aangeraden eerst [About filters and highlighting in Power BI reports](power-bi-reports-filters-and-highlighting.md) (Over filters en markeren in Power BI-rapporten) te lezen.
> 
> 

## <a name="what-is-the-difference-between-report-filters-in-editing-view-versus-reading-view"></a>Wat is het verschil tussen rapportfilters in de bewerkingsweergave versus de leesweergave?
U kunt in twee modi met rapporten werken: in de [leesweergave](service-interact-with-a-report-in-reading-view.md) en de [bewerkingsweergave](service-interact-with-a-report-in-editing-view.md).  De beschikbare filtermogelijkheden zijn afhankelijk van de modus waarin u werkt.

* In de bewerkingsweergave kunt u rapport-, pagina- en visualisatiefilters toevoegen. Als u het rapport opslaat, worden de filters ook opgeslagen. Personen die het rapport bekijken in de leesweergave, kunnen werken met de filters die u hebt toegevoegd, maar ze kunnen de wijzigingen niet opslaan.
* In de leesweergave kunt u werken met elk rapport-, pagina- en visualisatiefilter dat al in het rapport aanwezig is, maar u kunt wijzigingen aan de filters niet opslaan.

> [!NOTE]
> In dit artikel wordt beschreven hoe u filters maakt in de **bewerkingsweergave** voor rapporten.  Zie [Interacting with filters in report Reading View](service-interact-with-a-report-in-reading-view.md) (Werken met filters in de leesweergave voor rapporten) voor meer informatie over filters in de leesweergave.
> 
> 

## <a name="visual-filters-page-filters-drillthrough-filters-and-report-filters"></a>Visualisatiefilters, paginafilters, drillthrough-filters en rapportfilters
Een **paginafilter** kan worden toegepast op alle visuele elementen van een rapportpagina. Een **visualisatiefilter** kan worden toegepast op één visueel element van een rapportpagina. Een **rapportfilter** kan worden toegepast op alle pagina's van een rapport.

![](media/power-bi-report-add-filter/power-bi-add-filter-reading-view.png)

## <a name="add-a-filter-to-a-specific-visualization-aka-visual-filter"></a>Een filter toevoegen aan een specifieke visualisatie (ook wel een visualisatiefilter genoemd)
U kunt dit op twee manieren doen: 

* door op een veld te filteren dat al door de visualisatie wordt gebruikt;
* door een veld te identificeren dat nog niet door de visualisatie wordt gebruikt en dit veld rechtstreeks toe te voegen aan de bucket **Filters op niveau van visuele elementen**.

### <a name="by-filtering-the-fields-already-in-the-visualization"></a>Velden filteren die al in de visualisatie aanwezig zijn
1. Open [het rapport in de bewerkingsweergave](service-reading-view-and-editing-view.md).
   
   ![](media/power-bi-report-add-filter/power-bi-edit-view.png)
2. Open het deelvenster Visualisaties en filters en het deelvenster Velden (indien nog gesloten).
   
   ![](media/power-bi-report-add-filter/power-bi-display-panes.png)
3. Selecteer een visueel element om het te activeren. Alle velden die door het visuele element worden gebruikt, worden geïdentificeerd in het deelvenster **Velden** en tevens vermeld in het deelvenster **Filters** (onder de kop **Filters op niveau van visuele elementen**).
   
   ![](media/power-bi-report-add-filter/power-bi-default-visual-filter.png)
4. We gaan nu een filter toevoegen aan een veld dat al door de visualisatie wordt gebruikt. 
   
   * Schuif omlaag naar het gebied **Filters op niveau van visuele elementen** en selecteer de pijl om het te filteren veld uit te vouwen. In dit voorbeeld filteren we het veld **StoreNumberName**
     
      ![](media/power-bi-report-add-filter/power-bi-visual-level-filter.png) 
   * Stel het besturingselement voor filters in op **Basic**, **Advanced** of **Top N** in (zie [How to use report filters](power-bi-how-to-report-filter.md) (Rapportfilters gebruiken)). In dit voorbeeld selecteren we eenvoudig (basic) filteren en plaatsen markeringstekens naast de getallen 10, 11, 15 en 18.
     
      ![](media/power-bi-report-add-filter/power-bi-basic-filters.png) 
   * Het visuele element wordt overeenkomstig het nieuwe filter gewijzigd. Als u het rapport met het filter opslaat, kunnen lezers van het rapport met het filter werken in de leesweergave door waarden te selecteren of te wissen.
     
      ![](media/power-bi-report-add-filter/power-bi-filter-effect.png)
5. Nu gaan we een geheel nieuw veld aan de visualisatie toevoegen, als een zogenaamd filter op visueel niveau.
   
   * Selecteer in het deelvenster Velden het veld dat u wilt toevoegen als een nieuw filter op visueel niveau en sleep het naar het gebied **Filters op niveau van visuele elementen**.  In dit voorbeeld slepen we **District Manager** naar de bucket **Filters op niveau van visuele elementen** en selecteren alleen Andrew Ma. 
     
      ![](media/power-bi-report-add-filter/power-bi-andrew.png)
   * U ziet dat **District Manager** *niet* aan de visualisatie zelf wordt toegevoegd. De visualisatie bestaat nog steeds uit **WinkelNummerNaam** als de as en **Omzet van dit jaar** als de waarde.  
     
      ![](media/power-bi-report-add-filter/power-bi-visualization.png)
   * De visualisatie zelf wordt nu gefilterd om alleen de verkopen van Andrew voor de opgegeven winkels van dit jaar te laten zien.
     
     ![](media/power-bi-report-add-filter/power-bi-filtered-andrew.png)

## <a name="add-a-filter-to-an-entire-page-aka-page-view-filter"></a>Een filter toevoegen aan een hele pagina (ook wel paginaweergavefilter genoemd)
1. Open [het rapport in de bewerkingsweergave](service-reading-view-and-editing-view.md).
2. Open het deelvenster Visualisaties en filters en het deelvenster Velden (indien nog gesloten).
3. Selecteer in het deelvenster Velden het veld dat u wilt toevoegen als een nieuw filter op paginaniveau en sleep het naar het gebied **Filters op paginaniveau**.  
4. Selecteer de waarden die u wilt filteren en stel de besturingselementen voor het filter in op **Basic** of **Advanced** (zie [How to use report filters](power-bi-how-to-report-filter.md) (Rapportfilters gebruiken)).
   
   Alle visualisaties op de pagina waarop dit filter van invloed is, worden opnieuw getekend in overeenstemming met de wijziging. 
   
   ![](media/power-bi-report-add-filter/filterpage.gif)

Als u het rapport met het filter opslaat, kunnen lezers van het rapport met het filter werken in de leesweergave door waarden te selecteren of te wissen.

## <a name="add-a-drillthrough-filter"></a>Een drillthrough-filter toevoegen
Met drillthrough in Power BI-service en Power BI Desktop kunt u een *doelpagina* voor uw rapport maken die zich op een bepaalde entiteit richt, zoals een leverancier, klant of fabrikant. Gebruikers kunnen nu vanaf de andere rapportpagina's met de rechtermuisknop op een gegevenspunt voor die entiteit klikken en inzoomen op de betreffende pagina.

### <a name="create-a-drillthrough-filter"></a>Een drillthrough-filter maken
Open hiertoe het voorbeeld van klantwinstgevendheid in de bewerkingsweergave. Stel dat u een pagina wilt die zich richt op leidinggevende, zakelijke gebieden.   

1. Voeg een nieuwe pagina aan het rapport toe en geef deze de naam **Leidinggevend team**. Dit wordt de drillthrough-*doelpagina*.
2. Voeg visualisaties toe die belangrijke metrische gegevens voor de bedrijfstakken van het leidinggevend team volgen.    
3. Voeg ook **Leidinggevende > Naam leidinggevende** toe aan de drillthrough-filters.    
   
    ![](media/power-bi-report-add-filter/power-bi-drillthrough-filter.png)
   
    Er wordt een pijl Vorige aan de rapportpagina toegevoegd.  Als een gebruiker deze pijl Vorige selecteert, wordt hij of zij teruggestuurd naar de *oorspronkelijke* rapportpagina - de pagina waarop voor drillthrough is gekozen. De pijl Vorige werkt alleen in de leesweergave.
   
     ![](media/power-bi-report-add-filter/power-bi-back-arrow.png)

### <a name="use-the-drillthrough-filter"></a>Het drillthrough-filter gebruiken
We gaan nu kijken hoe het drillthrough-filter werkt.

1. Begin op de rapportpagina **Team Scorecard**.    
2. Stel dat u Andrew Ma bent en u wilt de rapportpagina Leidinggevend team filteren met slechts uw eigen gegevens.  Klik in het diagram in het gebied linksboven op een groene gegevenspunt om de menuoptie Drillthrough te openen.
   
    ![](media/power-bi-report-add-filter/power-bi-drillthrough.png)
3. Selecteer **Drillthrough > Leidinggevend team** om in te zoomen op de rapportpagina met de naam **Leidinggevend team**. De pagina wordt gefilterd en er wordt informatie weergegeven over het gegevenspunt waarop u met de rechtermuisknop hebt geklikt, in dit geval Andrew Ma. Alleen het veld in de verdieping Drillthrough-filters wordt doorgegeven aan de drillthrough-pagina van het rapport.  
   
    ![](media/power-bi-report-add-filter/power-bi-drillthrough-executive.png)

## <a name="add-a-filter-to-an-entire-report-aka-report-filter"></a>Een filter aan een heel rapport toevoegen (ook wel rapportfilter genoemd)
1. Open [het rapport in de bewerkingsweergave](service-reading-view-and-editing-view.md).
2. Open het deelvenster Visualisaties en filters en het deelvenster Velden (indien nog gesloten).
3. Selecteer in het deelvenster Velden het veld dat u wilt toevoegen als een nieuw filter op rapportniveau en sleep het naar het gebied **Filters op rapportniveau**.  
4. Selecteer de waarden die u wilt filteren (Zie [Rapportfilters gebruiken](power-bi-how-to-report-filter.md)).

De visuele elementen op de actieve pagina (en ook op alle andere pagina's van het rapport) worden gewijzigd overeenkomstig het nieuwe filter. Als u het rapport met het filter opslaat, kunnen lezers van het rapport met het filter werken in de leesweergave door waarden te selecteren of te wissen.

1. Selecteer de pijl Vorige om terug te keren naar de vorige rapportpagina.

## <a name="troubleshooting"></a>Problemen oplossen
### <a name="why-your-visual-level-filter-and-page-level-filter-may-return-different-results"></a>Waarom de filters op visueel niveau en op paginaniveau verschillende resultaten kunnen retourneren
Als u een filter op visueel niveau toevoegt, wordt er gefilterd op de geaggregeerde resultaten.  De standaardaggregatie is Som, maar u kunt [het samenvoegingstype wijzigen](service-aggregates.md) (Engelstalig).  

Als u een filter op paginaniveau toevoegt, wordt er zonder aggregeren gefilterd.  Dit gebeurt omdat een pagina meerdere visuele elementen kan bevatten die elk verschillende aggregatietypen kunnen gebruiken.  Het filter wordt dus op elke gegevensrij toegepast.

Als u het deelvenster Velden niet ziet, controleer dan of u in de [bewerkingsweergave](service-interact-with-a-report-in-editing-view.md) voor rapporten zit

## <a name="next-steps"></a>Volgende stappen
 [How to use report filters](power-bi-how-to-report-filter.md) (Rapportfilters gebruiken)

  [Filters and highlighting in reports](power-bi-reports-filters-and-highlighting.md) (Filters en markeren in rapporten)

[Interact with filters and highlighting in report Reading View](service-interact-with-a-report-in-reading-view.md) (Werken met filters en markeringen in de leesweergave voor rapporten)

[Change how report visuals cross-filter and cross-highlight each other](service-reports-visual-interactions.md) (Wijzigen hoe visuele rapportelementen elkaar kruislings filteren en markeren)

Hebt u nog vragen? [Misschien dat de Power BI-community het antwoord weet](http://community.powerbi.com/)
