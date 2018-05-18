---

title: Gateway fundamentals for Power BI
description: Gateway fundamentals for Power BI
author: MargoC
manager: AnnBe
ms.date: 5/14/2018
ms.assetid: 5b0c45ea-97e4-4e6f-8555-f2bc05ccb336
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Gateway fundamentals for Power BI


[!include[banner](../../../../includes/banner.md)]

>   This release includes multiple updates around improving fundamentals for the
>   Gateway in Power BI.

>   As part of the work to support multi-geo’s in Power BI, the gateway
>   experiences need to be updated so that users can leverage the on-premises
>   data gateway in those regions. Part of that effort including ensuring the
>   data source information (e.g. credentials) does not leave the region the
>   workspace is in (to comply with data sovereignty)

>   ![Machine generated alternative text:
G?) On-premises data gateway 
You are signed in as yshoukry@microsoft.com and are ready to register the 
gateway. 
Determine where your new on-premises data gateway will be deployed. 
Select Region: 
Brazil South 
@ Changing the Gateway region will restrict the regions in which you can use the gateway in. 
In Power Bl, only premium workspaces in the selected region will be able to use this 
gateway 
Individual Service Regions 
Logic Apps. Azure Analysis Services 
Brazil South 
Power BI 
Brazil South 
PowerApps. Microsoft Flow 
Not available 
Can't be used outside your default environment 
Done ](media/gateway-fundamentals-power-bi-1.jpg "Machine generated alternative text:
G?) On-premises data gateway 
You are signed in as yshoukry@microsoft.com and are ready to register the 
gateway. 
Determine where your new on-premises data gateway will be deployed. 
Select Region: 
Brazil South 
@ Changing the Gateway region will restrict the regions in which you can use the gateway in. 
In Power Bl, only premium workspaces in the selected region will be able to use this 
gateway 
Individual Service Regions 
Logic Apps. Azure Analysis Services 
Brazil South 
Power BI 
Brazil South 
PowerApps. Microsoft Flow 
Not available 
Can't be used outside your default environment 
Done ")
<!-- picture -->


>   Additionally, the high availability capabilities in the gateway are
>   transitioning from public preview to GA. Part of this effort includes
>   multiple experience improvements especially around better errors reporting
>   and improved user experience.

>   ![Machine generated alternative text:
Power 31 
Oose meru 
F a»ontes 
Recent 
Apps 
Sv•htch workspace 
cs Contoso Sales 
CS 
Cantoso Sales 
GATEWAY CLUSTERS 
v Sales_Cateway 
Finance_Gateway 
Tim •s_g ate way 
Andrews_Gateway 
Gateway_142-E392 
v Trial _Ga 
Test all cornections 
Add nav data source 
Gateway cluster settings 
NAME V 
Gateway 124002-12 
Gatev•ay 2 
Sarahs_g ateway 
H 2340 
ed Adrni migrators 
MACHINE NAME 
B I _team_machl 
Sarah's_computer 
HR_machinæC4 
ACTIONS 
Search 
Edit gatew•ay 
EI_GATEWAY 
On•prerH3es ditt gateway 
more about dusters ](media/gateway-fundamentals-power-bi-2.jpg "Machine generated alternative text:
Power 31 
Oose meru 
F a»ontes 
Recent 
Apps 
Sv•htch workspace 
cs Contoso Sales 
CS 
Cantoso Sales 
GATEWAY CLUSTERS 
v Sales_Cateway 
Finance_Gateway 
Tim •s_g ate way 
Andrews_Gateway 
Gateway_142-E392 
v Trial _Ga 
Test all cornections 
Add nav data source 
Gateway cluster settings 
NAME V 
Gateway 124002-12 
Gatev•ay 2 
Sarahs_g ateway 
H 2340 
ed Adrni migrators 
MACHINE NAME 
B I _team_machl 
Sarah's_computer 
HR_machinæC4 
ACTIONS 
Search 
Edit gatew•ay 
EI_GATEWAY 
On•prerH3es ditt gateway 
more about dusters ")
<!-- picture -->


>   We also have added/improved Kerberos single-sign-on support for SQL Server,
>   SAP Hana, SAP BW, Oracle, Teradata, Impala, and Spark, added SAML
>   single-sign-on support for SAP HANA, and expanded load balancing in the
>   on-premises data gateway for improved connectivity and performance.
