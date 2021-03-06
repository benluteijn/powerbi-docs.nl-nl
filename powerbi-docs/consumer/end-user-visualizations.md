---
title: Als een consument werken met visualisaties (visuals)
description: 'Concepten en terminologie in Power BI: visualisaties, visuals. Wat is een Power BI-visualisatie of -visual?'
author: mihart
ms.reviewer: ''
ms.service: powerbi
ms.subservice: powerbi-consumer
ms.topic: conceptual
ms.date: 01/29/2020
ms.author: mihart
LocalizationGroup: Visualizations
ms.openlocfilehash: 1aaacfae3c9af4517f6b028852e46059884dd3d5
ms.sourcegitcommit: 7aa0136f93f88516f97ddd8031ccac5d07863b92
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 05/05/2020
ms.locfileid: "79113861"
---
# <a name="interact-with-visuals-in-reports-dashboards-and-apps"></a>Werken met visuals in rapporten, dashboards en apps

[!INCLUDE[consumer-appliesto-ynny](../includes/consumer-appliesto-ynny.md)]

In de meest eenvoudige vorm is een ***visualisatie*** (of *visual*) een type diagram dat is samengesteld door Power BI-*ontwerpers* met behulp van de gegevens in rapporten en gegevenssets. 

Visuals bevinden zich op dashboards, in rapporten en kunnen met Power BI Q&A snel worden gemaakt. Wanneer een ontwerper een visual in een rapport maakt, kan hij of zij deze visual aan een dashboard *vastmaken*. Een [visual op een dashboard wordt een *tegel*](end-user-tiles.md) genoemd. dit dashboard heeft acht tegels. 

![Dashboard met tegels](media/end-user-visualizations/power-bi-dashboard.png)

> [!TIP]
> We raden u aan om eerst het overzichtsonderwerp [Power BI-basisconcepten voor *gebruikers*](end-user-basic-concepts.md) te lezen voordat u deze meer gedetailleerde inhoud leest.

## <a name="what-can-i-do-with-visuals"></a>Wat kan ik doen met visuals?

Visuals worden gemaakt door *ontwerpers* van rapporten en dashboards en gedeeld met *gebruikers*. Als gebruiker hebt u vele opties voor het werken met visuals om inzichten te onthullen en om zakelijke beslissingen te nemen die zijn gebaseerd op gegevens. De meeste van deze opties worden in de onderstaande tabel vermeld met koppelingen naar stapsgewijze instructies.

Voor veel van deze opties kan uw beheerder of de *ontwerper* de mogelijkheid om deze functies te bekijken of te gebruiken voor u uitschakelen. En sommige van deze functies werken alleen voor specifieke visuals.  Als u vragen hebt, neemt u contact op met uw beheerder of de eigenaar van het rapport of dashboard. Als u de eigenaar wilt zoeken, selecteert u het dashboard of de vervolgkeuzelijst van het rapport. 

![Titel vervolgkeuzelijst met daarin de eigenaar](media/end-user-visualizations/power-bi-owner.png)


> [!IMPORTANT]
> Maar eerst iets over Q&A. Q&A is het zoekhulpprogramma voor natuurlijke taal van Power BI. U typt een vraag in natuurlijke taal en met Q&A wordt de vraag beantwoord in de vorm van een visual. Q&A biedt gebruikers een manier om direct hun eigen visuals te maken. De visuals die u maakt met Q&A, kunnen echter niet worden opgeslagen. Maar als er iets specifieks is dat u wilt leren van de gegevens, en de ontwerper deze info niet heeft opgenomen in een rapport of dashboard, is Q&A een goede optie. Zie [Q&A voor gebruikers](end-user-q-and-a.md) voor meer informatie over Q&A.



|Taak  |Op een dashboard  |In een rapport  | In Q&A
|---------|---------|---------|--------|
|[Opmerkingen voor uzelf toevoegen aan een visual of een gesprek beginnen met collega’s over de visual](end-user-comment.md).     |  Ja       |   Ja      |  nee  |
|[Het rapport openen en verkennen waarin de visual is gemaakt](end-user-tiles.md).     |    Ja     |   nb      |  nee |
|[Een lijst met filters en slicers weergeven die van invloed zijn op de visual](end-user-report-filter.md).     |    als u opent in de focusmodus     |   Ja      |  nee |
|[Een visual in Q&A openen en verkennen (als de *ontwerper* Q&A heeft gebruikt om de visual te maken)](end-user-q-and-a.md).     |   Ja      |   nb      |  nb  |
|[Een visual maken in Q&A (voor het verkennen kunt u deze niet opslaan) ](end-user-q-and-a.md).     |   Ja      |   als ontwerper Q&A aan het rapport heeft toegevoegd      |  Ja  |
|[Power BI vragen om voor u te zoeken naar interessante feiten of trends](end-user-insights.md) in de gegevens van de visual.  Deze automatisch gegenereerde visuals worden *inzichten* genoemd.     |    ja, voor tegels    |  nee       | nee   |
|[Slechts één visual tegelijk weergeven met behulp van de *focusmodus*](end-user-focus.md).     | ja, voor tegels        |   ja, voor visuals      | nb  |
|[Opzoeken wanneer de visual de laatste keer is vernieuwd](end-user-fresh.md).     |  Ja       |    Ja     | nb  |
|[Slechts één visual tegelijk weergeven, zonder randen of navigatievensters, met behulp van de modus *volledig scherm*](end-user-focus.md).     |   Ja      |  Ja       | standaard  |
|[Afdrukken](end-user-print.md).     |  Ja       |   Ja      | nee  |
|[Dieper ingaan op de visual door filters voor visuals toe te voegen en te wijzigen.](end-user-report-filter.md)     |    nee     |   Ja      | nee  |
|Een visual aanwijzen om aanvullende details en knopinfo weer te geven.     |    Ja     |   Ja      | Ja  |
|[Andere visuals op de pagina kruislings filteren en kruislings markeren.](end-user-interactions.md)    |   nee      |   Ja      | nb  |
|[De gegevens weergeven die worden gebruikt om de visual te maken](end-user-show-data.md).     |  nee       |   Ja      | nee  |
| [De manier wijzigen waarop de visual is gesorteerd](end-user-change-sort.md). | nee  | Ja  | kan sortering wijzigen door de vraag opnieuw te verwoorden  |
| Een spotlight toevoegen aan een visual. | nee  | Ja  |  nee |
| [Exporteren naar Excel.](end-user-export.md) | Ja | Ja | nee|
| [Maak een melding](end-user-alerts.md) om u te waarschuwen wanneer een waarde hoger is dan de drempelwaarde die u hebt ingesteld.  | Ja  | nee  | nee |
| [De andere visuals op de pagina kruislings filteren en kruislings markeren](end-user-report-filter.md).  | nee      | Ja  | nb |
| [Details weergeven van een visual met een hiërarchie](end-user-drill.md).  | nee  | Ja   | nee |

## <a name="next-steps"></a>Volgende stappen
Terug naar de [Basisconcepten voor gebruikers](end-user-basic-concepts.md)    
[Een visual selecteren om een rapport te openen](end-user-report-open.md)    
[Typen visuals die beschikbaar zijn in Power BI](end-user-visual-type.md)