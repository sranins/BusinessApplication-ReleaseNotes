---

title: Spring '18 summary of what's new in Business Intelligence Platform
description: Spring '18 summary of what's new in Business Intelligence Platform
author: MargoC
manager: AnnBe
ms.date: 05/01/2018
ms.assetid: 294c79bd-058b-46f6-a825-b0c128ce21ec
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
# Spring ’18 summary of what’s new in Business Intelligence Platform

[!include[banner](../../includes/banner.md)]

## Jan ’18 - General Availability

### [Power BI Desktop](overview.md)

- [Ask Top N questions in Q&A](desktop/ask-top-n-questions-q-a.md) - Easily ask Top N questions in Q&A in both Power BI Desktop and Power BI Service.
- [Azure Active Directory authentication](desktop/azure-active-directory-authentication.md) - Leverage Azure Active Directory authentication when connecting to Azure SQL Database and Azure SQL Data Warehouse.
- [Hide pages from reading mode](desktop/hide-pages-reading-mode.md) - Authors control which report pages are exposed to users.

### [Power BI Service](desktop/filtering-data-view.md)

- [Ability to share and favorite reports](service/share-favorite-reports.md) - Shared reports appear in recent, favorites, and “shared with me” lists, similar to dashboards.
- [Push apps](service/push-apps.md) - Admins can automatically deploy Power BI apps to users.
- [Pin from apps to dashboard](service/pin-apps-dashboard.md) - Create dashboards that combine information from other shared dashboards, reports, or apps in an integrated view.
- [Persistent filters](service/pin-apps-dashboard.md)- With persistent filters, Power BI saves a user’s slicer and filter values, and automatically applies them when the user returns.
- Custom visual administrator control - Power BI admins can disable custom visuals for an organization.

### [Power BI Mobile](overview.md)

- [Visio custom visual support](mobile/visio-custom-visuals.md) - Custom visuals are presented in the mobile app when users tap the visual and sign into their Visio online account.
- [Responsive visuals optimized for phone layout](mobile/responsive-visualization-optimized-phone-layout.md) - Text—such as labels—also adjust based on the size of the visuals.

### [Power BI Embedded](overview.md)

- [Capacity API](embedded/capacity-api.md) – Using Enhanced Application Lifecycle Management capabilities, you can use APIs to assign or remove Workspaces from Power BI capacity.
- [Row-level security on Azure Analysis Services based on CustomData](embedded/row-level-security-azure-analysis-services-based-customdata.md) - Filter data based on the CustomData function in Azure Analysis Services for row-level security.
- [Custom layout](embedded/custom-layout.md) - Dynamically change the size and layout definitions of a report page. Use one of the layouts in Power BI Desktop, or a fixed size to match the application element.
- [Phased embedding](embedded/phased-embedding.md) - Load embedded content in the background to improve performance and get object metadata.
- [Single visual embedding](embedded/single-visual-embedding.md) - Embed one or more visuals inside an iFrame.

## Feb ’18 - General Availability

### [Power BI Desktop](overview.md)

- [Report level slicers](desktop/report-level-slicers.md) - Filter other pages of the report.
- [Cross-highlight across multiple visuals](desktop/cross-highlight-across-multiple-visuals.md) - Multi-select data points across visuals.
- [Quick measures](desktop/quick-measures.md) - Support for live connections and custom date tables.

### [Power BI Mobile](overview.md)

- [Ability to invite and favorite reports](mobile/invite-favorite-reports.md) - Users can view reports shared with them, share reports with others, view favorite reports, and mark reports as favorites.

### [Power BI Embedded](overview.md)

- [Azure monitoring](embedded/azure-monitoring.md) - With usage metrics, monitor the consumption of resources, and trigger actions when thresholds are met.
- [Azure US Government Cloud availability](embedded/available-us-government-customers.md) - Power BI Embedded is available for United States government customers.
- [Mobile layout support](embedded/mobile-layout-support.md) - Load embedded report pages in a phone layout.
- [Model Parameters API](embedded/model-parameters-api.md) - Get or set predefined model parameters using APIs.
- [Visual level filters](embedded/visual-level-filters.md) - Apply and capture filters for embedded visuals.

## Feb ’18 – Public Preview

### [Power BI Desktop](overview.md)

- [SAP HANA connector](desktop/sap-hana-connector.md) - Treats SAP HANA as a multi-dimensional source.
- [Organizational visuals store](desktop/sap-business-warehouse-bw-connector.md) - Discover and import custom visuals distributed by your Power BI administrator.

### [Power BI Service](desktop/filtering-data-view.md)

- Manage organizational visuals store - Power BI administrators can deploy and manage custom visuals for their organization.

## March ’18 - General Availability

### Power BI Desktop

- [Bookmarking](desktop/organizational-visuals-store.md) - Bookmark report states to keep track of an exploration, tell a story, or create custom navigation.
- New [SAP HANA](desktop/sap-hana-connector.md) and [SAP Business Warehouse (BW)](desktop/sap-business-warehouse-bw-connector.md) connectors.

### Power BI Service

- [Share content with consumer accounts](service/sharing-content-consumer-accounts.md) - Share content with other users who have email addresses from consumer email services and telecommunications providers.
- [Larger node sizes in Power BI Premium](service/larger-node-sizes-power-bi-premium.md) – Organizations can use P4 and P5 nodes to run larger workloads on premium capacity.
- [Performance reporting for Power BI Premium](service/performance-reporting-power-bi-premium.md) - Provides insights about how Premium capacity resources are utilized, troubleshooting performance issues, and deciding when to upgrade to a larger node size.

### [Power BI Mobile](overview.md)

- [Report tooltip touch optimization](mobile/report-tooltip-touch-optimization.md) - Data point selection with tap and hold gesture.
- [Power BI for mixed reality (Public Preview)](mobile/power-bi-mixed-reality.md) - Mixed reality experience for viewing dashboards and reports, and positioning them in their surroundings with Microsoft HoloLens. Available in Microsoft Store.
- [Persistent filters](service/persistent-filters.md) - Users resume working with report filters and slicers in the same state as their last interaction.
- [Phone optimization for embedded reports](mobile/phone-optimization-embedded-reports.md) - Mobile app developers who use embedded reports for phone optimized layout can resize and position visuals to fit the device.
- [External sharing](mobile/external-sharing.md) - Users can share reports and dashboards with external users.

### [Power BI Embedded](overview.md)

- [Available on German datacenters](embedded/available-german-datacenters.md).
- [Bookmarks support](embedded/bookmarks-support.md) - Apply bookmarks on embedded reports and control UI elements through APIs.
- [Update dashboard/tile](embedded/update-dashboard-or-tile.md) – With Application Lifecycle Management, developers can change deployed tiles and dashboards while retaining their original IDs.
- [Single sign-on (SSO) for Azure SQL database](embedded/single-sign-sso-azure-sql-database.md) - Optionally pass in authenticated Azure AD credentials in queries to the Azure SQL database. 

### Power BI report server

- Power BI Desktop features available since October ’17:

    - [Drill with filtering of all visuals on page](https://powerbi.microsoft.com/en-us/blog/power-bi-desktop-december-feature-summary/#drillFiltersOtherVisuals)
    - [Rule-based conditional formatting for table and matrix](https://powerbi.microsoft.com/en-us/blog/power-bi-desktop-november-2017-feature-summary/#conditionalFormatting)
    - [Cell alignment for table and matrix](https://powerbi.microsoft.com/en-us/blog/power-bi-desktop-november-2017-feature-summary/#alignment)
    - [Lock objects on your reports](https://powerbi.microsoft.com/en-us/blog/power-bi-desktop-november-2017-feature-summary/#lock)
    - [Report options for slow data sources](https://powerbi.microsoft.com/en-us/blog/power-bi-desktop-november-2017-feature-summary/#slowDataSource)
    - [Filtering performance improvements](https://powerbi.microsoft.com/en-us/blog/power-bi-desktop-november-2017-feature-summary/#filtering)
    - [Selection pane and visual display controls](https://powerbi.microsoft.com/en-us/blog/power-bi-desktop-november-2017-feature-summary/#selectionPane)
    - [Bookmarking](desktop/organizational-visuals-store.md)
    - [Report-level slicers](desktop/report-level-slicers.md)
    - [Quick measures](desktop/quick-measures.md)
    - [Cross-highlight across multiple visuals](desktop/cross-highlight-across-multiple-visuals.md)
    - [DirectQuery performance improvements](https://powerbi.microsoft.com/en-us/blog/power-bi-desktop-february-2018-feature-summary/#dqPerf)

## March ’18 - Public Preview

### [Power BI Desktop](overview.md)

- [Canvas tooltips](_Canvas_tooltips_(Public) - Design report pages for use as tooltips for a custom experience.

## April ’18 - General Availability

### Power BI Desktop

- [Control over linguistic schema](desktop/control-over-linguistic-schema.md) - Report authors can improve Q&A results for users by adjusting the linguistic schema with phrasing and synonyms specific to the model domain.
- [New experiences for Q&A in reports](desktop/user-experiences-q-reports.md) - Report authors can enable Q&A experiences for report consumers with suggested starting questions. These user experiences surface in Power BI Service, Power BI Embedded, and Cortana.
- [Organizational visuals store](desktop/sap-business-warehouse-bw-connector.md) - Discover and import custom visuals from the Power BI admin.

### [Power BI Service](desktop/filtering-data-view.md)

- [Data source setup improvements](service/data-source-setup-improvements.md) - Easily configure gateways and diagnose common errors.
- [Organizational visuals store](desktop/sap-business-warehouse-bw-connector.md) - Discover and import custom visuals from the Power BI admin.
- Administrator tenant usage reporting - APIs to allow admins gain insights into workspace, report, and dataset artifacts across the tenant.

### [Power BI Mobile](overview.md)

- [Drill-down and drill-up support](mobile/drill-down-drill-up-support.md) - Users drill down and drill up to analyze data on mobile via tap and hold to open a tooltip menu on report visuals.

### [Power BI Embedded](overview.md)

- [Azure load monitoring](embedded/azure-load-monitoring.md) - Monitor consumption of resources, and trigger actions when thresholds are met.
- [Onboarding experience](embedded/onboarding-experience-power-bi-embedded.md) - Onboarding tool makes initial setup fast and easy.
- [Show or hide report pages](embedded/show-or-hide-report-pages.md) - Set the visibility of embedded report pages through the API.
- [Get data APIs](embedded/get-data-apis.md) - Enable applications to extract data shown in visuals.
- [Themes support](embedded/themes-support.md) - Manage themes by session for embedded objects with JavaScript API.
- [Visual level configuration](embedded/visual-level-configuration.md) - Control which visual functions, such as focus mode and export data, are exposed to users.
- [Azure diagnostics](embedded/azure-diagnostics.md) - Use error logging for analysis and tracking.



## May ’18 - General Availability

### Power BI Desktop

- Drill-through on measures – Power BI now supports drilling through on measures. This includes passing through the filter and slicer context from the current page.
- [Conditional formatting based on another column](desktop/conditional-formatting-based-another-column.md) – Table and matrix visuals can leverage columns that aren’t necessarily part of the visual when they’re conditionally formatted.
- Incremental data refresh – Users can set up incremental data refresh policies that will be applied when they publish to the Power BI service.

## May ’18 – Public Preview

### Power BI Service

- [Incremental data refresh](service/data-source-setup-improvements.md) - Incrementally load new data into a dataset without reloading all the data.

## June ’18 - General Availability

### Power BI Desktop

- Filters on data view – In the data view of Power BI Desktop, users can now filter the data that they are working with.

### [Power BI Service](desktop/filtering-data-view.md)

- Multiple-geographic regions for Power BI Premium - Create Premium capacities in geographic locations that are different from the Power BI tenant to achieve compliance requirements.
- [Set up email subscriptions for other users](service/subscribe-other-users-email.md).
- [XMLA connectivity with Analysis Services](service/xmla-connectivity-analysis-services.md) - Treat Power BI Premium workspaces like Analysis Services servers and connect to them with existing tools.


### [Power BI Mobile](overview.md)

 - [Drill-through support](mobile/drill-support.md) - On mobile, use drill-through to navigate from one report page to another report page filtered by a selected entity.

### [Power BI Embedded](overview.md)

- [App-only token support](embedded/app-only-token-support.md) - Identify an application on the Power BI platform for enhanced deployment, security, and Application Lifecycle Management.
- [Workspace collection deprecation](embedded/workspace-collection-deprecation.md).
- [Export to PowerPoint](embedded/export-powerpoint.md) - Export an embedded object to PowerPoint.
- [Export to PDF](embedded/export-pdf.md) - Export an embedded object to PDF.

## June ’18 - Public Preview

### [Power BI Service](desktop/filtering-data-view.md)

- [Workspaces with Azure AD groups](service/workspaces-azure-ad-groups.md) - Workspaces have their own roles and permissions separate from Office 365 groups to enable more control over management of workspaces, including assigning workspace roles to individual users. The preview is available for customers with Power BI deployments that meet certain criteria. Contact your Microsoft account representative to learn more about how you can participate.

## July – September ’18 - General Availability

### [Power BI Service](desktop/filtering-data-view.md)

- [Dataset metadata translations](service/dataset-metadata-translations.md) - Users see dataset fields in their client locale and language when translations are defined in the dataset or Analysis Services model.
- Export to PDF - Export a Power BI report in PDF format.

## July – September ’18 – Public Preview

### [Power BI Desktop](overview.md)

- Model diagram and navigation – An improved modeling experience that scales to large and complex data models with many tables, calculations, and other objects.
- [Common Data Service for Analytics capability in Power BI connectivity](../common-data-service-analytics/power-bi-apps-cds-analytics.md) - Report authors can connect to data in Common Data Service for Analytics, add entities to data models, and mash-up Common Data Service for Analytics data with data from other sources.

### [Power BI Service](desktop/filtering-data-view.md)

- [Smart alerts](service/smart-alerts.md) - Users receive automatic alerts when there are important changes to data.

- [Query acceleration for large datasets](service/query-acceleration-large-datasets.md) - Dataset authors create in-memory aggregations to enable interactive queries over big data.

- Workspace search - Search for and find content across all the workspaces that you have access to.

- [SSRS reports for Power BI Premium](service/sql-server-reporting-services-ssrs-reports-power-bi-premium.md) - Publish and view SQL Server Reporting Services (SSRS) reports in Power BI Premium.

### [Common Data Service for Analytics in Power BI](../common-data-service-analytics/index.md)

- [Common Data Service for Analytics in Power BI (Public Preview)](../common-data-service-analytics/datapools.md) - Datapools become artifacts in Power BI, and users can create new datapools, manage access to existing datapools, manage data refresh from Common Data Service for Analytics, and monitor processing from within a Power BI workspace.

    - Use Power BI to import data to Common Data Service for Analytics - Use an authoring tool to import and transform data and map it to a common data model.
    - Manage Common Data Service for Analytics within Power BI workspaces.

- [Power BI apps for Common Data Service for Analytics](../common-data-service-analytics/power-bi-apps-cds-analytics.md) - Users can customize and manage apps from the Power BI Service without writing code. No Azure subscription is required.
- [Map data from Azure Blob storage to Common Data Service for Analytics](../common-data-service-analytics/extensible-azure.md) - Map existing Azure Blob storage to standard or custom entities in Common Data Service for Analytics. Mapped entities are available in Power BI Desktop for building datasets, reports, and dashboards.

### [Power BI Insights apps](insights-apps/insights-apps.md)

- [Power BI for Sales Insights](insights-apps/sales-insights.md) – Brings in key entities from either Dynamics 365 or Salesforce, allowing sales managers to track sales performance across products and salespeople.
- [Power BI for Service Insights](insights-apps/service-insights.md) – Takes advantage of Dynamics 365 for Customer Service, Field Service, or Project Service Automation data to provide insights in each of these areas.