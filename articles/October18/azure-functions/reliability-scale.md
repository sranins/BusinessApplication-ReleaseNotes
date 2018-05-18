---

title: Reliability and Scale
description: Organizations are now taking production-level dependencies on Azure Functions to implement scenarios ranging in diversity between mobile backends, Microservices, SaaS extensibility and data processing pipelines.
author: MargoC
manager: AnnBe
ms.date: 5/14/2018
ms.assetid: cc29accf-67ee-4d58-ada5-299cb9d84de5
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Reliability and Scale


[!include[banner](../../includes/banner.md)]

Organizations are now taking production-level dependencies on Azure Functions to
implement scenarios ranging in diversity between mobile backends, Microservices,
SaaS extensibility and data processing pipelines. With the mission critical
requirements come unique challenges around reliability, performance, and
diagnostics capabilities. To help with critical customer needs, the team has
been focusing on:

-   **Self-service diagnostics**: Azure Functions users can now diagnose
    production issues using the App Service Diagnostics experience in the Azure
    Portal. They can perform health checks and address specific issues in depth.
    Furthermore, with Azure App Insight integration, developers can dig down
    into issues or track application level data flows using the application map
    capability.

-   **Scalability and efficiency:** With a significant set of enhancements
    implemented for HTTP scale-out, Azure Functions meet and exceed response
    times and throughput of other major cloud providers. Azure Functions
    customers operating at high scale can take advantage of auto scaling their
    apps from consumption billing to app hosting plan billing thus making large
    scale applications significantly cheaper.

-   **New deployment model**: With the new zip deploy capability, developers can
    now publish their Functions code packaged in zip files allowing for faster
    “cold start” performance and lock-down of production environments.

-   **Durable Functions**: With Durable Functions, developers can implement more
    advanced scenarios/patterns such as long-running/stateful functions, fan-out
    and fan-in, and asynchronous HTTP patterns. With the GA of Durable Functions
    and the announced support for more languages, developers can keep innovating
    and stretch the boundaries of the FaaS model.
