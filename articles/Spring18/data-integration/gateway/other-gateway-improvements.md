---

title: Other gateway improvements
description: Other gateway improvements
author: MargoC
manager: AnnBe
ms.date: 05/01/2018
ms.assetid: 94bacbfe-08ce-46b7-a787-6ad61a052524
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---

# Other gateway improvements

[!include[banner](../../../includes/banner.md)]

Other gateway improvements include:

-   Gateways will automatically fall back on the HTTPS protocol when
    communicating with the Azure Service Bus if the default TCP protocol fails
    for any reason.

-   Turning on additional logging in the gateway client will capture mashup
    engine logging.

-   Gateway admins can configure the number of mashup engine containers that run
    simultaneously on the gateway machine by changing the
    MashupDefaultPoolContainerMaxCount setting in the gateway configuration
    file. This file is named
    Microsoft.PowerBI.DataMovement.Pipeline.GatewayCore.dll.config and is
    located in the gateway’s installation directory.

-   Monthly updates for the mashup engine match the version released in Power BI
    Desktop.
