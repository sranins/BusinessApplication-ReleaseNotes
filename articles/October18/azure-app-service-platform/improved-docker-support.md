---

title: Improved Docker Support
description: Improved Docker Support
author: MargoC
manager: AnnBe
ms.date: 5/14/2018
ms.assetid: f92c500b-f034-426f-a177-292a49fcc965
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  **Improved Docker Support** 


[!include[banner](../../includes/banner.md)]

Since the release of Azure App Service support for Linux, the team has been
engaging with customers and the larger ecosystem (including that within broader
Azure team). With Docker and Kubernetes becoming de-facto standards for
Containers and Container Orchestration, customers are expecting to leverage
container ease of use and portability. In this period, the team has delivered:

-   **Linux and Container support on App Service Environment (ASE).** Following
    the preview announcement at //build 2018, pre-built and custom containers
    are now available for customers using ASEs. Large customers using ASEs can
    now build mixed workload (Windows and Linux) and secure them leveraging all
    the virtual private cloud capabilities ASE offers.

-   **Container Orchestrator compatibility.** Following the preview announcement
    at //build 2018, developers can deploy multi-container applications into App
    Service leveraging standard formats such as Docker Compose, Kubernetes yaml
    files and helm charts.

-   **Wide range of supported languages and stacks.** Azure App Service
    customers are expecting to deploy their code to a pre-configured environment
    that is managed and patched by the platform. Following customer
    prioritization, the team has made “stock” containers available in Java, Go
    and Ruby). The team will also be working on making stable versions on OSS
    languages available as they come out.
