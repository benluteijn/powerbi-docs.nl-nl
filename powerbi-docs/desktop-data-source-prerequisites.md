---
title: Vereisten voor Power BI-gegevensbronnen
description: Vereisten voor Power BI-gegevensbronnen
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
ms.openlocfilehash: 38a304fc3a8bc671baefeaef31d07ef576c0ad5a
ms.sourcegitcommit: 284b09d579d601e754a05fba2a4025723724f8eb
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 11/15/2017
---
# <a name="power-bi-data-source-prerequisites"></a>Vereisten voor Power BI-gegevensbronnen
Voor elke gegevensprovider ondersteunt Power BI een specifieke providerversie voor objecten. Zie [Gegevensbronnen](desktop-data-sources.md) (Engelstalig) voor meer informatie over gegevensbronnen die in Power BI beschikbaar zijn. In de volgende tabel worden deze vereisten beschreven.

| Gegevensbron | Provider | Minimaal vereiste providerversie | Minimaal vereiste gegevensbronversie | Ondersteunde gegevensbronobjecten | Downloadkoppeling |
| --- | --- | --- | --- | --- | --- |
| SQL Server |ADO.net (ingebouwd in .Net Framework) |.Net Framework 3.5 (uitsluitend) |SQL Server 2005+ |Tabellen/weergaven, scalaire functies, tabelfuncties |Opgenomen in .NET Framework 3.5 en hoger |
| Access |Microsoft Access-database-engine (ACE) |ACE 2010 SP1 |Geen beperking |Tabellen/weergaven |[Downloadkoppeling](http://go.microsoft.com/fwlink/?linkid=285987&clcid=0x409) |
| Excel (uitsluitend XLS-bestanden) (zie opmerking 1) |Microsoft Access-database-engine (ACE) |ACE 2010 SP1 |Geen beperking |Tabellen, bladen |[Downloadkoppeling](http://go.microsoft.com/fwlink/?linkid=285987&clcid=0x409) |
| Oracle (zie opmerking 2) |ODP.NET |ODAC 11.2 Release 5 (11.2.0.3.20) |9.x+ |Tabellen/weergaven |[Downloadkoppeling](http://go.microsoft.com/fwlink/?linkid=272376&clcid=0x409) |
| System.Data.OracleClient (ingebouwd in .Net Framework) |.NET Framework 3.5 |9.x+ |Tabellen/weergaven |Opgenomen in .NET Framework 3.5 en hoger | |
| IBM DB2 |ADO.Net-client van IBM (onderdeel van het stuurprogrammapakket voor de IBM-gegevensserver) |10.1 |9.1+ |Tabellen/weergaven |[Downloadkoppeling](http://go.microsoft.com/fwlink/?linkid=274911&clcid=0x409) |
| MySQL |Connector/Net |6.6.5 |5.1 |Tabellen/weergaven, scalaire functies |[Downloadkoppeling](http://go.microsoft.com/fwlink/?linkid=278885&clcid=0x409) |
| PostgreSQL |NPGSQL ADO.NET-provider |2.0.12 |7.4 |Tabellen/weergaven |[Downloadkoppeling](http://go.microsoft.com/fwlink/?linkid=282716&clcid=0x409) |
| Teradata |.Net-gegevensprovider voor Teradata |14+ |12+ |Tabellen/weergaven |[Downloadkoppeling](http://go.microsoft.com/fwlink/?linkid=278886&clcid=0x409) |
| SAP Sybase SQL Anywhere |iAnywhere.Data.SQLAnywhere voor .NET 3.5 |16+ |16+ |Tabellen/weergaven |[Downloadkoppeling](http://go.microsoft.com/fwlink/?linkid=324846) |

>[!NOTE]
>Voor Excel-bestanden met een .xlsx-extensie is geen aparte providerinstallatie vereist.

>[!NOTE]
>Voor de Oracle-providers is ook Oracle-clientsoftware (versie 8.1.7+) vereist.
> 
> 
