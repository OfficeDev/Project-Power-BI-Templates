Project for the web and Project Online Power BI Template
=====================================

With the *Consolidated Project for the web and Project Online Power BI Template*, you can import and
analyze data from Project for the web and Project Online into Power BI. The template is
designed to help you quickly connect to your Dataverse instance in Dynamics 365 
where your Project for the web data is stored and Project Web App tenant in Office 365
and download a variety of data to visually explore and monitor
all the key aspects of your PPM deployment. There are multiple visually
rich report pages for the portfolio, resource, and project overview.

Prerequisites
-------------

To use the Consolidated Project for the web and Project Online Power BI template, you need the
following:

-   Project Plan 3(formerly Project Online Professional) or Project Plan 5(formerly Project Online Premium) Subscription
-   Power BI Desktop or Power Bi Pro Subscription

Settings
--------

When opening the PBIT file, you will be asked to enter the URL of your
Dynamics 365 Dataverse instance you are using
for Project for the web.

Enter it in this format: https://<spam><spam>(Dataverse
environment).(region).dynamics<spam><spam>.com

For example: http://<spam><spam>orgde6d15d8.crm.dynamics<spam><spam>.com

**To determine the Dataverse environment value of the URL**:

1. Log on to Office: https://www.office.com
2. On the office.com page, in the left pane, select All Apps. On the All Apps, select Business Apps Tab 
   and select the Project Application of the org you want to build your reports on.
3. The App URL will give you the environment and region value.

Put the value into the Dataverse URL.

The region value of the URL will usually be associated to the data
center that is close to you geographically. The following list shows the
region values associated with regional data centers.

  --------------------------------------------- -----------------

   |**Region**|**Value**|
   |:---------------|:--------------|
   |North America|crm|
   |South America|crm2|
   |Canada |crm3|
   |Europe, Middle East and Africa (EMEA)|crm4|
   |Asia Pacific Area (APAC)|crm5|
   |Oceania|crm6|
   |Japan|crm7|
   |India|crm8|
   |North America 2|crm9|
   |United Kingdom|crm11|
   |France|crm12|
  --------------------------------------------- -----------------

**Check with your admin** If are unsure of the URL you need, check with
your Office 365 administrator and have them check for the value in the
[Power Platform Admin
Center](https://docs.microsoft.com/en-us/power-platform/admin/admin-guide).

> [!Note] See [Connect to Project for the web data through Power BI
> Desktop](https://docs.microsoft.com/project-for-the-web/connect-to-project-for-the-web-data-through-powerbi-desktop)
> for more information about determining the URL.

> [!Note] We have enabled the queries for Roadmap reports. The changes are still rolling out.  

Next you will be asked to enter the URL for your PWA site. Enter it in this format, replacing "contoso" with your site name. https://contoso.sharepoint.com/sites/pwa

How the sample affects your tenant data
---------------------------------------

This sample has minimal impact on your tenant data. It only queries Dataverse
to retrieve project data to generate the dashboards in Power BI.

Questions and comments
----------------------
Please provide feedback here: https://aka.ms/ReportingFeedback

Additional resources
--------------------

-   [Getting started with Power BI
    Desktop](https://powerbi.microsoft.com/en-us/documentation/powerbi-desktop-getting-started/)

This project has adopted the [Microsoft Open Source Code of
Conduct](https://opensource.microsoft.com/codeofconduct/). For more
information, see the [Code of Conduct
FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact
<opencode@microsoft.com> with any additional questions or comments.
