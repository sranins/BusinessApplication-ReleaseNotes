---

title: Single Sign-On for SQL Azure
description: Single Sign-On for SQL Azure
author: MargoC
manager: AnnBe
ms.date: 5/14/2018
ms.assetid: defe56c9-38a5-48c6-ba86-e1c6371bfb75
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Single Sign-On for SQL Azure


[!include[banner](../../../../includes/banner.md)]

Power BI Embedded has no awareness of the application’s user. For applications
that want to set row level security in Azure SQL database, there is a need to
pass the application’s user information to Azure SQL database. By enabling the
Single Sign-On Option, Power BI Embedded sends authenticated Azure Active
Directory credentials for users accessing reports, in the queries to the Azure
SQL database. This enables Power BI Embedded to respect security settings that
are configured at the data source level.
