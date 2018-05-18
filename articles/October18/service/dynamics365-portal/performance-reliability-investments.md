---

title: Performance and Reliability Investments
description: Performance and Reliability Investments
author: MargoC
manager: AnnBe
ms.date: 5/14/2018
ms.assetid: 93347fe1-05ca-483b-835d-2b81dfa7fe55
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Performance and Reliability Investments




[!include[banner](../../../includes/banner.md)]

With our continuing goal to increase the performance and reliability of the
Dynamics 365 Portal platform, this release will see these major enhancements:

1.  Introduction of **Premium Azure Service Bus** clusters to power the Portal
    Cache and Search Index invalidation features:

-   Migration to the new resources will be automatic and transparent for all
    Portal types (Trial and Production).

-   Every portal user, Admin or otherwise, will benefit from the increased
    reliability of the platform and the reduced latency in seeing entity changes
    take effect in the Portal UI and in KB Search results.

-   Enhanced automation and telemetry to provide automatic load balancing to
    eliminate noisy-neighbor scenarios

-   Design allows for high volume clients to be run on dedicated hardware

1.  [Internal] With the **TPS Service Bus integration**, all Organization and
    Licensing Events are now processed via a higher bandwidth pipeline than in
    previous releases.

-   This will primarily decrease the provisioning time of new Portals, including
    time spent in the "Getting Setup..." page.

-   Administrators will also see benefits in that changes to Portal Add-on
    Licenses take effect much sooner than previous releases.
