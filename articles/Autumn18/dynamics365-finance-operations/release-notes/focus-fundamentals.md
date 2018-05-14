---

title: Focus on Fundamentals
description: [Description]
author: MargoC
manager: AnnBe
ms.date: 5/14/2018
ms.assetid: 6df34582-1f82-43b8-8492-339c34232295
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
### Focus on Fundamentals

Usability & Productivity: Business users will experience increased performance
while scrolling through grids. This functionality is key for organizations with
larger sets of data.

-   Grid totals are now available to allow users to calculate totals for numeric
    columns in tabular grids.

-   Business users can create, save and share optimized views of forms that can
    be targeted for certain groups of users or for certain business tasks. These
    views have the potential to greatly simplify the user experience and improve
    productivity.

-   Business users can group data in a list based on the values in one or more
    columns and see subtotals for each grouping for numeric columns in the
    list. 

-   Additional improvements include allowing the date picker to be used for date
    fields in filtering, showing the available values for enum fields in
    filtering, exposing a legal entity filter for cross-company forms in the
    filter pane, improving the ability to find the field you want to filter on,
    correcting type-ahead behavior for filter fields in the Advanced filter/sort
    dialog, and enabling Excel-like filtering behavior of column headers. 

Personalization improvements: It is now simpler for users to add/remove columns,
hide any field via personalization (to simplify the experience when mandatory
fields are defaulted by business logic), copy fields between fast tabs (to
optimize the experience by putting the most important fields in a single fast
tab or by moving fields into grids), and expand/collapse controls while in
personalization mode. Users are now able to edit multiple records in a grid with
a single action. Hyperlinks added to fields can now be suppressed when not
desired, and the click behavior of the hyperlink aligns with other Office
products.

Dual currency: The reporting currency will be repurposed into a true second
accounting currency. From a GL perspective, the reporting currency will continue
to be calculated for every transaction posted to general ledger.  Some general
ledger processes will be enhanced, and a new journal will be added to post
transactions in only the reporting currency. For various subledgers, such as
fixed assets, there will be larger changes. For fixed assets, we will start to
maintain all transactions in the subledger for the reporting currency. When
running depreciation, it will depreciate the reporting currency amounts using
the depreciation methods, just as it does the accounting currency. Other
subledger modules impacted will be Accounts payable, Accounts receivable and
Cash management.

Simplification of pre-printed forms (invoices and statements): Customers will
save time and money by utilizing the new default customer invoice and statement
formats. The new formats provide options to print documents to pre-printed forms
as well as plain paper. Utilizing one of the new default templates will either
eliminate or minimize the need to modify customer statements and invoices.

Simplification through templates: Templates are available for creating free text
invoices. A template can be created from an existing free text invoice, or a new
template can be created and used when creating new invoices.

Productivity to view settlement transactions: Improve the viewing of settlements
by showing all related transactions for a settlement. Maintain multiple tabs so
users can see the original context of the transaction, the settled transactions,
and the related vouchers on a single form. This enhancement will alleviate the
pain of users needing to have multiple forms open to see the correlated
information.

Allow global number sequences: Global number sequences for customers and
customer groups allow business users to copy this data from one legal entity to
another. When the copy function is complete, the same customer number and
customer information will be shared in both legal entities. This improves
usability for inter-company scenarios. This functionality is also available for
vendor and vendor groups.

Vendor or customer approvals for specific fields: Enable approval of customers
and vendors when specific fields are edited. You will be able to select from a
list of fields that can be approved. Once the field is edited, you can submit
the changes to workflow. When the changes are approved, they will be applied to
the customer or vendor record.

Ease of data entry for dimension values: When a dimension has a backing entity
such as customer or vendor, the dimension value will default to the value
entered in the associated form. For example, the customer dimension would be
automatically set to the customer value used when a customer is created. New
options are available to enable one more dimensions to be defaulted. For
example, a business unit can be defaulted when the cost center is entered.

Consistent validation actions: The validation for journals will be improved to
check for the exact same validations that are done at time of posting.

Flexibility to change cash discounts: When editing a due date or base date in
the customer or vendor transactions form, the user can be prompted to update the
discount date. The due date and base date will be added in the transaction form
and there will be a parameter that enables the prompt for a discount date change
when the base date or due date is modified.

IBAN numbers will have additional validation: IBAN numbers will be validated to
ensure that the bank account number in the IBAN number matches the account
number on the bank account form.

Automatic ledger settlements: Ledger settlement rules can be set up that will
automatically settle ledger transactions based on user criteria. Batch
processing will be added so that the task can be run periodically.

Reverse Journal Posting: Reversals are improved to allow the reversal of
multiple general journal lines or an entire general journal. Reversal from the
voucher transaction form allows reversal of a limited number of subledger
journal entries. Reversals are also allowed from the accounting source explorer.

Additional demo data: Completing data entities and data packages to enable
seamless and efficient management of demo data to optimize for the best possible
sales and trial experience for prospects. These additional components focus on
scenarios for Manufacturing, Distribution, and Sales.

Improving on-hand inventory report performance: Customers with large volumes of
products and transactions find it a challenge to ensure prompt inventory-on-hand
information, given that the current design requires significant real-time
processing. Refactoring the approach to calculating and reporting on-hand
inventory allows for a far more responsive experience.

Supportability rules: Additional rules to identify and adjust sub-optimal setup
or configuration options have been added to the system. Examples include: delete
shipment terms that have never been used, delete payment terms that have never
been used, periodic clean-up of price and discount sales and purchase trade
agreements that have expired or never been used.

Go Local: Customers can opt for a fully data-resident online Dynamics 365
Finance and Operations subscription. All customer data, code, and metadata will
be contained in the data region of choice. Data residency will be made available
in the following data regions: Europe, Canada, UK and Australia.

 

Adding data archiving: Enterprise customers can segment data intelligently for
efficiency gains. Users can query historical data while maintaining performance
and cost on smaller sets of current data.

 

Test automation support: An administrator or functional power user can author,
run, and manage an automated test regression suite, based on task recordings,
that greatly reduces the impact and cost of validating updates to Dynamics 365
for Finance and Operations environments. These tests can be run on UAT
environments.

 

Cost-effective development for large organizations: A development organization
or partner can deploy and manage many development instances in a quick and
cost-effective manner. A local development environment is at par in
functionality with a cloud development environment (servicing, LCS connectivity,
access from outside the box). Build automation enables continuous delivery and
automatic deployment on test environments.

Edit analytical workspaces without leaving the client: End users can modify
ready-made analytical workspaces (including financial reports) themselves
without leaving the client or hiring developers. This capability extends to all
ready-made financial reports as well as all other reports in analytical
workspaces.

Ease troubleshooting for document routing agent: Document routing agent is used
to manage large print jobs being sent to on-premise printers. Now,
troubleshooting print issues is easy. Extensive error reporting and diagnostics
enable IT administrators to detect and fix issues without having to call
Support.

 

Upgrade automation: If you are a customer operating Dynamics 365 for Finance and
Operations, Enterprise edition you will be able to apply a major version upgrade
(such as 7.1 to 7.2) without involvement from the Microsoft Operations team.
Orchestration of upgrade steps, including preparation of a staging area, data
upgrade, and applying new versions are performed via an automated process. While
the Microsoft Operations team is available on a stand-by basis to assist with
queries or exceptions, you can schedule and carry out the entire process with
minimal downtime and at your convenience.

On-premises deployment: The on-premises deployment option for Dynamics 365 for
Finance and Operations has been enhanced in many areas, with a focus on
simplifying setup, operations, monitoring, and servicing.

United Arab Emirates (UAE) localization: Dynamics 365 for Finance and Operations
now supports mandatory regulatory requirements in United Arab Emirates (UAE).
The UAE localization covers the following functional areas: electronic VAT
return, electronic VAT FTA audit file (FAF), VAT reverse charge, sales invoice
report adjustments in the area of tax, simultaneous printing in English and
Arabic languages, and the user interface in ar-AE language. Microsoft has also
received the accreditation and certification required for tax accounting
software providers in UAE from UAE Federal Tax Authorities.

Russia localization: Dynamics 365 for Finance and Operations now supports
mandatory regulatory requirements in Russia (for on-premises deployment only).
The fall release of the Russian localization covers the following functional
areas: accounts payable/accounts receivable, advanced holders, bank and cash,
fixed assets, general ledger, financial reporting, electronic reporting,
inventory, tax registers, addresses/FIAS, and VAT. The remaining Russian
localization functionalities are targeted for general availability by the end of
calendar year 2018, including: cash flow management, alcohol sales declaration,
inventory management enhancements: bailment, goods in transit, optional posting
of transfer orders, inventory owner, third-party miscellaneous charges, and tax
declarations in electronic format.

Retail localization for Eastern Europe: Dynamics 365 for Finance and Operations
now supports mandatory regulatory retail requirements for six Eastern European
countries: Czech Republic, Estonia, Hungary, Latvia, Lithuania, and Poland. The
local functionality includes processing of cash payments in accounting according
to local regulations, defaulting of sales dates in retail invoices, substitution
of tax groups in return transactions, retail invoice numbering, and processing
of advance invoices for customer order deposits. The localization of call center
functionality for these countries will be available in later updates.

Fiscal printer integration sample for Italy: The integration sample supports one
of the popular fiscal printer models available on the Italian market and enables
printing fiscal receipts in all major retail sales scenarios in stores in Italy.
The sample is a part of the Retail SDK. It may be built and used as-is;
implementation partners may also extend the integration functionality or build
integration with other fiscal printer models based on the sample.

Retail upgrade and N-1 support for India: Customers in India can now upgrade
their Retail solutions from previous versions to Dynamics 365 for Finance and
Operations. In addition, the customers may take advantage of the N-1 support
that lets stores that run Dynamics AX 2012 R3 POS work with Retail headquarters
on Dynamics 365 for Finance and Operations after an upgrade.

INTELLIGENCE & INSIGHTS

Financial insights: Financial insights learns from historical invoice, payment,
and customer data to create a machine learning model which is used to predict
when an invoice will be paid. In addition to payment predictions, Financial
insights uses optimization strategies to help organizations improve the chances
of getting paid on time. It provides the ability to automatically apply an
optimization strategy to invoices and customers in Dynamics 365 for Finance and
Operations.

Financial insights will be shipped as an embedded solution within Dynamics 365
for Finance and Operations. It will also be shipped as a stand-alone solution
that users can sign up for and use with their organization’s data connected
through CDS. The stand-alone app does not require Finance and Operations to be
installed.

Insight apps – embed in the Finance and Operations client or available as
stand-alone apps

If you are a Finance and Operations user, ready-made insight apps are built into
the Finance and Operations client. The same apps can be downloaded and licensed
using AppSource for users who are not licensed Finance and Operations users. You
can also pin other insight apps (for example, apps that bring in data from other
systems) directly into the Finance and Operations client to enable rich
scenarios.

Globalization – Enhanced configurability: Configurability of features lets
partners and customers do extensions and customizations without coding. We
continue to extend both the depth and the breadth of configurability and added
the following new capabilities this area:

-   Static (validations) and dynamic performance rules for configuration. It
    will prevent performance degradations when partners or customers customize
    configurations and guide users while doing such customizations.

-   Automatic comparison of GER format executions with baselines defined in task
    guides which provides us and our partners and customers with automatic test
    capabilities. These tests focus on business users rather than engineers.

-   Relative paths in GER formulas. It will allow a quick re-mapping of the
    format if you need to switch to another data entity or xml node with similar
    structure.

-   Making some e-invoicing regulatory features configurable to simplify
    e-invoicing updates in case of law changes as well as partner and customer
    extensions of these features. E-invoicing is now one of the most frequently
    changed regulatory areas, especially in Latin America and Europe.

-   Providing configurable free text invoice templates out-of-the-box to allow
    customers and partners around the globe to easily modify them to meet their
    local requirements.

-   Enable separated model mapping from taxable document, so one set of taxable
    document and tax document can be shared by different Finance and Operations
    versions.

-   Enable configuring tax currency on tax component in the tax document to
    fulfill the customers with multi-branches in different countries.

-   Enable linear equations solver for tax calculation, users can only create
    tax calculation formulas with linear equations and it will result in nearly
    10 times performance improvement in tax calculation.
