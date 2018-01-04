---
title: Een responsieve slicer maken waarvan u de grootte kunt wijzigen in Power BI
description: Meer informatie over het maken van een voor uw rapport op maat gemaakte responsieve slicer waarvan u de grootte kunt wijzigen
services: powerbi
documentationcenter: 
author: maggiesMSFT
manager: kfile
backup: 
editor: 
tags: 
qualityfocus: no
qualitydate: 
ms.service: powerbi
ms.devlang: NA
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: powerbi
ms.date: 12/08/2017
ms.author: maggies
ms.openlocfilehash: f95f126cc6a7c95fbe3227b712281a7d3f81e320
ms.sourcegitcommit: b780b7108fd9b52398b8377b52836f0e0fedc96e
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 12/09/2017
---
# <a name="create-a-responsive-slicer-you-can-resize-in-power-bi-preview"></a>Een responsieve slicer maken waarvan u de grootte kunt wijzigen in Power BI (preview)

Responsieve slicers worden in grootte aangepast zodat ze overal op het rapport passen. U kunt de grootte en vorm van responsieve slicers aanpassen, van horizontaal naar vierkant naar verticaal. De waarden in de slicer worden hierop automatisch gerangschikt. In Power BI Desktop kunt in de Power BI-service horizontale slicers en slicers voor datum/bereik responsief maken. Slicers voor datum/bereik hebben tevens verbeterde aanraakgebieden, zodat u ze eenvoudiger razendsnel kunt wijzigen. U kunt responsieve slicers zo klein of groot maken als u zelf wilt. Het formaat wordt ook automatisch aangepast zodat ze goed op rapporten in de Power BI-service en in de mobiele Power BI-apps passen. 

![Responsieve slicers kunnen verschillende vormen hebben](media/power-bi-slicer-filter-responsive/responsive-slicer-gif.gif)

## <a name="create-a-slicer"></a>Een slicer maken

De eerste stap bij het maken van een dynamische slicer is het maken van een eenvoudige slicer. 

1. Selecteer het pictogram **Slicer** ![Slicerpictogram](media/power-bi-slicer-filter-responsive/power-bi-slicer-icon.png) in het deelvenster **Visualisaties**.
2. Sleep het veld dat u wilt filteren naar **Veld**.

    ![Een veld aan de slicer toevoegen](media/power-bi-slicer-filter-responsive/power-bi-slicer-field.png)

## <a name="convert-to-a-horizontal-slicer"></a>Naar een horizontale slicer converteren

1. Selecteer de slicer en selecteer vervolgens in het deelvenster **Visualisaties** het tabblad **Indeling**.
2. Vouw de sectie **Algemeen** uit en selecteer vervolgens voor **Afdrukstand** de optie **Horizontaal**.

    ![De slicer instellen op horizontaal](media/power-bi-slicer-filter-responsive/power-bi-slicer-horizontal.png) 

1.  Waarschijnlijk wilt u de weergave breder maken om weer waarden weer te geven.

     ![De slicer breder maken](media/power-bi-slicer-filter-responsive/power-bi-slicer-wide-horizontal.png)

## <a name="make-it-responsive-and-experiment-with-it"></a>De slicer responsief maken en hiermee experimenteren

Deze stap is eenvoudig. 

1. Stel bij **Afdrukstand** in de sectie **Algemeen** van het tabblad **Indeling** de optie **Responsief (voorbeeldweergave)** in op **Aan**.  

    ![De slicer is nu responsief](media/power-bi-slicer-filter-responsive/power-bi-slicer-wide-responsive.png)

1. Nu kunt u ermee experimenteren. Versleep de hoeken om de slicer korter, hoger, breder of smaller te maken. Als u de slicer klein genoeg maakt, wordt alleen nog een filterpictogram weergegeven.

    ![Responsieve slicer die zo klein is dat het een filterpictogram wordt](media/power-bi-slicer-filter-responsive/power-bi-slicer-small-filter-icon.png)

## <a name="add-it-to-a-phone-report-layout"></a>Toevoegen aan de rapportindeling voor telefoons

In Power BI Desktop kunt u voor elke pagina van een rapport een telefoonindeling maken. Als een pagina een telefoonindeling heeft, wordt de pagina op een mobiele telefoon in afdrukstand Staand weergegeven. Anders moet u deze weergeven in de afdrukstand Liggend. 

1. Selecteer in het menu **Beeld** de optie **Telefoonindeling**.

     ![Pictogram Telefoonindeling, menu Beeld](media/power-bi-slicer-filter-responsive/power-bi-phone-layout-menu.png)
    
1. Sleep alle visuals die u in het telefoonrapport wilt weergeven in het raster. Wanneer u de responsieve slicer sleept, stelt u dit op de gewenste grootte in; in dit geval slechts een filterpictogram.

    ![De slicer toevoegen aan de indeling van het telefoonrapport](media/power-bi-slicer-filter-responsive/power-bi-slicer-phone-layout.png)

Meer informatie over het maken van [rapporten die zijn geoptimaliseerd voor de mobiele Power BI-apps](desktop-create-phone-report.md).

## <a name="make-a-time-or-range-slicer-responsive"></a>Een slicer voor tijd of bereik responsief maken

U kunt dezelfde stappen volgen om een slicer voor tijd of bereik responsief te maken. Nadat u **Responsief** hebt ingesteld op **Aan**, ziet u een aantal dingen:

- In visuals wordt de volgorde van de invoervakken geoptimaliseerd op basis van de grootte die is toegestaan op het canvas. 
- De weergave van gegevenselementen wordt geoptimaliseerd om de slicer zo bruikbaar mogelijk te maken op basis van de grootte die is toegestaan op het canvas. 
- Door de nieuwe ronde handvatten op de schuifregelaars zijn de aanraakinteracties geoptimaliseerd. 
- Wanneer een visual te klein wordt om nog nuttig zijn, wordt het een pictogram weergegeven dat de betreffende visual vertegenwoordigt. Als u hiermee wilt werken, dubbeltikt u hierop om de visual in de focusmodus te openen. Dit bespaart kostbare ruimte op de rapportpagina zonder verlies van de functionaliteit.

## <a name="next-steps"></a>Volgende stappen

- [Zelfstudie: slicers in Power BI-service](power-bi-visualization-slicers.md)
- Nog vragen? [Misschien dat de Power Bi-community het antwoord weet](http://community.powerbi.com/)