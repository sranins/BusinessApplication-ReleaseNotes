---

title: Test flows with previous run data
description: Test flows with previous run data
author: MargoC
manager: AnnBe
ms.date: 05/01/2018
ms.assetid: f5051a32-ec3e-4fc5-a310-f5d1574723e9
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Test flows with previous run data




[!include[banner](../../includes/banner.md)]

When you’re editing a flow that you’ve run in the past, it can be useful to be
able to rerun the flow with the trigger data from a previous run. This gives you
a way to verify that your flow now behaves as you expect. This has been possible
before by going to the **Run history** view and selecting **Resubmit**. Now, to
streamline the editing experience, we are adding a **Test flow** button directly
in the designer.

![Test flow button](media/test-flows-previous-run-data-1.png "Test flow button")
<!-- Picture 1 -->


*Test flow button*

When you select Test flow, you will see a new pane with two options:

1.  **Perform the trigger action yourself.** The action depends on what the
    trigger is. For example, for a button trigger, you'll run the flow button;
    for an email trigger, you'll send yourself an email; and for a file trigger,
    you'll upload a file to SharePoint Online.

2.  **Use data from previous runs.** Here, if your flow has run before, you'll
    get a list of the most recent runs and can pick one to test your flow with.

![Test flow pane](media/test-flows-previous-run-data-2.png "Test flow pane")
<!-- Picture 2 -->


*Test flow pane*

After you run the flow, you'll immediately see the details of the flow run and
can watch each steps being executed. Finally, runs started via this route are
marked as Tests in the run history view, so you can distinguish them from flow
runs that were triggered normally.
