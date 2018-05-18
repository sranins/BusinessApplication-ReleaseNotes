---

title: Supporting Azure Active Directory application authentication
description: Supporting Azure Active Directory application authentication
author: MargoC
manager: AnnBe
ms.date: 5/14/2018
ms.assetid: cba1b690-0d07-4400-8bf6-80de880157ba
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Supporting Azure Active Directory application authentication




[!include[banner](../../../../includes/banner.md)]

Currently building a Power BI Embedded application (aka "app owns data
scenario") requires the creation of a master user account, storing the
credentials for that account and then using them in the application code for
performing non-interactive sign-in to Power BI. Azure Active Directory has
special support for applications authenticating using their own identity without
a user context. This support was designed for app-only authentication, allows
higher control and security, has less limitations and is the recommended
approach. We are adding support for application authentication to Power BI
Embedded. This will enhance the deployment, security and Application Lifecycle
Management for applications using Power BI Embedded.
