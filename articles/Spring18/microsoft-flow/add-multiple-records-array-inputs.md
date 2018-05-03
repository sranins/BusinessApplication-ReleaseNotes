---

title: Add multiple records to array inputs
description: There are many actions in Flow that take an array as input.
author: MargoC
manager: AnnBe
ms.date: 05/01/2018
ms.assetid: 4b9f5265-fa5f-40d9-8491-2a43c09d3b9b
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Add multiple records to array inputs




[!include[banner](../../includes/banner.md)]

There are many actions in Flow that take an array as input. For example, the
**Send email** action has a list of attachments that can be included with the
email. Before, you could pass just one attachment, or you could generate a list
of attachments from the outputs of another action by using the **Select**
action. However, there was no easy way to just have *two* attachments.

So we're happy to announce that, for any action that takes a list as an input,
you can now add as many items inline as you want.

![Adding multiple attachments](media/add-multiple-records-to-array-inputs-1.png "Adding multiple attachments")
<!-- Picture 5 -->


*Array inputs*

To add a second (or third, fourth, and so on) attachment, just click the **Add
new item** button below the main fields for that attachment. Each time, you'll
get a new set of the fields for the new attachment (or any other record that
you’re adding). To remove an item, select the ellipsis (...) menu next to the
first field in the record you want to delete.
