---

title: XRM Sandbox extensibility
description: XRM Sandbox extensibility
author: MargoC
manager: AnnBe
ms.date: 5/14/2018
ms.assetid: 708d4258-72f4-4c2b-954b-fad7bf84042d
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  XRM Sandbox extensibility


[!include[banner](../../includes/banner.md)]

In March 2018, we produced in private-preview a demonstration of our vision for
extensibility of CDS with the introduction of Azure Functions, provided in a way
that frees developers from needing to manage/configure Azure at all. We have
received great feedback from our customers here.

But our top priority for Dynamics 365 is delivering a product that “just works”
for all our customers. To that end, we are announcing a new set of diagnosis and
debugging capabilities for existing XRM plugin developers. These capabilities
are built on the exact same Azure App Service and Azure Function platform which
enables customers to quickly identify application issues (with exceptions
event-log messages, and application counters) and perform steps such as
generating memory dumps and recycling applications. By moving XRM plugins to run
in this model, we have put all our weight behind an experience to enable plugin
developers to be successful. Furthermore, we benefit from the tooling which best
enables our support/product engineers to provide the best experience in solving
customer plugin issues.
