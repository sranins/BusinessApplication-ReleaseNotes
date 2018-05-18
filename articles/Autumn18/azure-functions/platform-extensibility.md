---

title: Platform extensibility
description: Being an OSS project, Azure Functions enjoy wide community interest and engagement.
author: MargoC
manager: AnnBe
ms.date: 5/14/2018
ms.assetid: 2bd1557d-e213-425e-aa4b-48e1081e8fd9
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Platform extensibility


[!include[banner](../../includes/banner.md)]

Being an OSS project, Azure Functions enjoy wide community interest and
engagement. With the FaaS model becoming popular on many platforms including IoT
Edge form-factors, the Azure Functions team has been investing in:

-   **Azure Functions Linux in Consumption mode** – Azure Functions are now
    available in a Linux version that is billed-per-execution like the
    Windows-based consumption plan. Furthermore, they can also be run in Docker
    Containers and deployed using any container orchestrator.

-   **IoT Edge integration** – building on the momentum of the Intelligent Edge
    announcement in //build 2017 and 2018, Functions are now available as
    modules that can be deployed to an IoT Edge device. With Event Grid becoming
    available on IoT devices as well, applications can be built locally,
    deployed to Edge devices or executed at scale in the Public Cloud.

-   **Azure Functions V2.0 GA** – the Azure Functions V2.0 runtime includes new
    binary extensibility points as well as platform independence. V2.0 Functions
    can run on Linux as well as Windows and on other Cloud platforms leveraging
    Containers. Now in GA, Azure Functions V2.0 provides developers the ability
    to safely extend the languages supported for Functions, and as a proof point
    we have partnered with a third party to provide our Python language support
    which is now also GA.
