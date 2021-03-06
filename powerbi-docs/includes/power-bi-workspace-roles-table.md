---
title: Power BI-werkruimterollen
description: Tabel Power BI-werkruimterollen
services: powerbi
author: maggiesMSFT
ms.service: powerbi
ms.topic: include
ms.date: 04/23/2020
ms.author: maggies
ms.custom: include file
ms.openlocfilehash: 5ed3a65f1ef65640c76ada765931a85714aad3af
ms.sourcegitcommit: 7aa0136f93f88516f97ddd8031ccac5d07863b92
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 05/05/2020
ms.locfileid: "82781340"
---
De functies van de vier rollen zijn: beheerders, leden, inzenders en lezers. Al deze mogelijkheden, met uitzondering van bekijken en ermee werken, vereisen een Power BI Pro-licentie.

|Mogelijkheid   | Beheerder  | Lid  | Inzender  | Lezer |
|---|---|---|---|---|
| De werkruimte bijwerken en verwijderen.  | X  |   |   |   | 
| Personen, met inbegrip van andere beheerders, toevoegen/verwijderen.  | X  |   |   |   |
| Leden of anderen met minder machtigingen toevoegen.  |  X | X  |   |   |
| Apps publiceren en bijwerken. |  X | X  |   |   |
| Items en apps delen.<sup>1</sup> |  X | X  |   |   |
| Anderen toestaan items opnieuw te delen.<sup>1</sup> |  X | X  |   |   |
| Apps op de startpagina van collega's weergeven |  X | X  |   |   |
| Dashboards en rapporten weergeven op de startpagina van collega's |  X | X  | X |   |
| Inhoud in de werkruimte maken, bewerken en verwijderen.  |  X | X  | X  |   |
| Rapporten publiceren naar de werkruimte, inhoud verwijderen.  |  X | X  | X  |   |
| Een rapport in een andere werkruimte maken op basis van een gegevensset in deze werkruimte.<sup>1</sup> |  X | X  | X  |   |
| Een rapport kopiëren.<sup>2</sup> | X | X | X |  |
| De vernieuwing van gegevens plannen via de on-premises gateway.<sup>3</sup> | X | X | X |  |
| Verbindingsinstellingen voor de gateway wijzigen.<sup>3</sup> | X | X | X |  |
| Een item bekijken en ermee werken.<sup>4</sup> |  X | X  | X  | X  |
| Gegevens lezen die zijn opgeslagen in gegevensstromen in de werkruimte | X | X | X | X |

1. Inzenders en kijkers kunnen items in een werkruimte delen als ze machtigingen voor opnieuw delen hebben.
2. Als u een rapport wilt kopiëren en een rapport wilt maken in een andere werkruimte op basis van een gegevensset in deze werkruimte, hebt u een machtiging nodig voor het maken van de gegevensset. Voor gegevenssets in deze werkruimte hebben de personen met de rollen Beheerder, Lid en Inzender een Samenstellingsmachtiging via hun werkruimterol.
3. Houd er rekening mee dat u ook machtigingen nodig hebt voor de gateway. Deze machtigingen worden elders beheerd, onafhankelijk van de werkruimterollen en -machtigingen. Zie [Een on-premises gateway beheren](https://docs.microsoft.com/data-integration/gateway/service-gateway-manage) voor meer informatie.
4. Zelfs als u geen Power BI Pro-licentie hebt, kunt u items in de Power BI-service bekijken en ermee werken als de items zich in een werkruimte in een Premium-capaciteit bevinden.

