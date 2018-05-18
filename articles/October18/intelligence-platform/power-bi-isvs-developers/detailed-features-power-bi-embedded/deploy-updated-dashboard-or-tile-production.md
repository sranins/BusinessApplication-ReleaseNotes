---

title: Deploy an updated dashboard or tile to production
description: Deploy an updated dashboard or tile to production
author: MargoC
manager: AnnBe
ms.date: 5/14/2018
ms.assetid: edb86306-f665-4e74-8a9f-ac5288a92170
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Deploy an updated dashboard or tile to production




[!include[banner](../../../../includes/banner.md)]

Enhancing Application Lifecycle Management (ALM) by enabling changes in
tiles/dashboards that are already deployed, while preserving their original IDs.
Once a dashboard or a tile has been updated to a newer version, the developer
can deploy the update into production dashboards by using the ‘updateTile’ API
and stating the source and target tiles. The content of the tile will be
updated, but the IDs will not change, making the update smooth and fast.
