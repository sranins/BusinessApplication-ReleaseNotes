---

title: Return data to PowerApps from a flow
description: Use Microsoft Flow to create logic that performs one or more tasks when an event occurs in a PowerApp.
author: MargoC
manager: AnnBe
ms.date: 05/01/2018
ms.assetid: 16e5cc7d-613b-4893-8cd2-24636afe03d9
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Return data to PowerApps from a flow




[!include[banner](../../includes/banner.md)]

Use Microsoft Flow to create logic that performs one or more tasks when an event
occurs in a PowerApp. For example, configure a button that creates an item in a
SharePoint list, sends an email or meeting request, or creates an online file.
You can also use a flow to return data to PowerApps. For example, configure a
flow that retrieves data from a web endpoint, SQL Server, or an Excel file in
SharePoint, and then processes that data by using built-in actions. You can
configure any control in the app to start the flow, which continues to run even
if you close PowerApps.

## Step 1
To set up a flow that calls data from PowerApps, first start your flow with the
PowerApps trigger.

![PowerApps trigger screen](media/step-one-1.png "PowerApps trigger screen")
<!-- Picture 40 -->


*PowerApps trigger*

Next, add whatever actions you want to run when your flow is called. Inside
these actions, you can use the **Ask in PowerApps** option to collect additional
parameters from the PowerApp.

## Step 2
After you have built your flow and collected the data you need, add
the **Respond to PowerApps** action. In this action, define the output fields
you want to provide to PowerApps. Name each field, and select Add Dynamic
Content to pass in data from the actions in the flow.

![Response action screen](media/step-two-1.png "Response action screen")
<!-- Picture 41 -->


*Response action*

## Step 3
The last step is to add your flow to the PowerApp in the formula bar. Select the
control to run your flow from, and then, on the **Action** tab on the ribbon,
select **Flow**. Select the flow you created to add it to the formula bar, and
pass any parameters that the flow requires.

![Set variable](media/step-three-1.png "Set variable")
<!-- Picture 42 -->


*Set variable*

We recommend that you use **Set()** or **UpdateContext()** to set a variable
that stores the result of your flow. That way, if multiple values are returned
from the flow, you can access different properties in various places in your
app. For example, the preceding flow returns two properties, **most_sales** and
**sellers**, and you can use either on a control.

![View result properties](media/step-three-2.png "View result properties")
<!-- Picture 43 -->


*View result properties*

Today, you can return basic types such as Text or Email. However, there might be
cases where you want to return a list of data to the PowerApp, such as a list of
names. In this case, you can use the **Join** action inside your flow and then
use the **Split** function in your PowerApp.

![Screenshot showing use of results in Gallery](media/step-three-3.png "Screenshot showing use of results in Gallery")
<!-- Picture 44 -->


*Use results in the gallery*

In the preceding example, notice that the result of the flow is set in
SalesInfoVariable, and then the gallery is bound to the table output by
splitting the names on a comma. If you have an array of objects in the flow, use
the **Select** action first, to choose the property you want to pass to the
PowerApp before joining the array.
