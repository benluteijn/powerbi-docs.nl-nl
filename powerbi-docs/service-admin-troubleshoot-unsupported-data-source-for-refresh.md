---
title: Problemen oplossen met een gegevensbron waarvoor vernieuwen niet wordt ondersteund
description: Problemen oplossen met een gegevensbron waarvoor vernieuwen niet wordt ondersteund
services: powerbi
documentationcenter: 
author: davidiseminger
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
ms.date: 09/06/2017
ms.author: davidi
ms.openlocfilehash: 93820e12602aa10754e3f905640c5e9b29cd7cc9
ms.sourcegitcommit: b3ee37e1587f1269ee7dd9daf1685a06dea3b50c
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 11/23/2017
---
# <a name="troubleshooting-unsupported-data-source-for-refresh"></a>Problemen oplossen met een gegevensbron waarvoor vernieuwen niet wordt ondersteund
Mogelijk wordt er een fout weergegeven wanneer u een gegevensset probeert te configureren voor een geplande vernieuwing.

        You cannot schedule refresh for this dataset because it gets data from sources that currently don’t support refresh.

Dit gebeurt wanneer de gegevensbron die u hebt gebruikt in Power BI Desktop de vernieuwingsbewerking niet ondersteunt. U moet de gegevensbron zoeken die u gebruikt en aan de hand van de lijst met ondersteunde gegevensbronnen in [Gegevens vernieuwen in Power BI](refresh-data.md) controleren of de gegevensbron wordt ondersteund. 

## <a name="find-the-data-source"></a>De gegevensbron zoeken
Als u niet zeker weet welke gegevensbron is gebruikt, kunt u dit controleren door de volgende stappen uit te voeren in Power BI Desktop.  

1. Zorg ervoor dat u het deelvenster **Rapport** weergeeft in Power BI Desktop.  
   ![](media/service-admin-troubleshoot-unsupported-data-source-for-refresh/tshoot-report-pane.png)
2. Selecteer **Query's bewerken** in het lint.  
   ![](media/service-admin-troubleshoot-unsupported-data-source-for-refresh/tshoot-edit-queries.png)
3. Selecteer **Geavanceerde editor**.  
   ![](media/service-admin-troubleshoot-unsupported-data-source-for-refresh/tshoot-advanced-editor.png)
4. Noteer de provider die wordt vermeld voor de bron.  In dit voorbeeld is de provider Active Directory.  
   ![](media/service-admin-troubleshoot-unsupported-data-source-for-refresh/tshoot-provider.png)
5. Controleer in [Gegevens vernieuwen in Power BI](refresh-data.md) of de provider voorkomt op de lijst met ondersteunde gegevensbronnen.  U zult zien dat Active Directory geen ondersteunde gegevensbron is en dus niet kan worden vernieuwd.  

## <a name="next-steps"></a>Volgende stappen
[Gegevens vernieuwen](refresh-data.md)  
[Power BI Gateway - Personal](personal-gateway.md)  
[On-premises gegevensgateway](service-gateway-onprem.md)  
[Problemen met de on-premises gegevensgateway oplossen](service-gateway-onprem-tshoot.md)  
[Problemen met Power BI Gateway - Personal oplossen](service-admin-troubleshooting-power-bi-personal-gateway.md)  

Nog vragen? [Misschien dat de Power BI-community het antwoord weet](http://community.powerbi.com/)
