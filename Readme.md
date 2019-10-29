Project for the web Power BI Template
=====================================

With the *Project for the web Power BI Template*, you can import and
analyze data from Project for the web into Power BI. The template is
designed to help you quickly connect to your Default Common Data Service
(CDS) instance in Dynamics 365 where your Project for the web data is
stored and download a variety of data to visually explore and monitor
all the key aspects of your PPM deployment. There are multiple visually
rich report pages for the portfolio, resource, and project overview.

Prerequisites
-------------

To use the Project for the web Power BI template, you need the
following:

-   Project Online Professional or Premium Subscription
-   Power BI Desktop or Power Bi Pro Subscription

Settings
--------

When opening the PBIT file, you will be asked to enter the URL of your
Dynamics 365 Common Data Service (CDS) default instance you are using
for Project for the web.

Enter it in this format: https:\\<spam><spam>(Default CDS
environment).(region).dynamics<spam><spam>.com

For example: http:\\<spam><spam>orgde6d15d8.crm.dynamics<spam><spam>.com

**To determine the Default CDS environment value of the URL**:

1.  While logged into Office 365, go to this site:
    https://web.powerapps.com
2.  On the PowerApps page, you'll find the default CDS environment value
    in the **Environments** section. For example: **orgde6d15d8**.

Put the value into the *Default CDS environment* portion of the URL. For
instance, using the example above:\
https:\\<spam><spam>orgde6d15d8.(region).dynamics<spam><spam>.com

**To determine the region value of the URL**:

The region value of the URL will usually be associated to the data
center that is close to you geographically. The following list shows the
region values associated with regional data centers.

  --------------------------------------------- -----------------
  **Region** <br/>                              **Value** <br/>
  North America <br/>                           crm <br/>
  South America <br/>                           crm2 <br/>
  Canada <br/>                                  crm3 <br/>
  Europe, Middle East and Africa (EMEA) <br/>   crm4<br/>
  Asia Pacific Area (APAC) <br/>                crm5 <br/>
  Oceania <br/>                                 crm6 <br/>
  Japan <br/>                                   crm7 <br/>
  India <br/>                                   crm8 <br/>
  North America 2 <br/>                         crm9 <br/>
  United Kingdom <br/>                          crm11 <br/>
  France <br/>                                  crm12 <br/>
  --------------------------------------------- -----------------

Put the value into the *region* portion of the URL. Using our previous
example, if the your data center is North American, the URL you need
would be: https:\\<spam><spam>orgde6d15d8.crm.dynamics<spam><spam>.com

**Check with your admin** If are unsure of the URL you need, check with
your Office 365 administrator and have them check for the value in the
[Power Platform Admin
Center](https://docs.microsoft.com/en-us/power-platform/admin/admin-guide).

> [!Note] See [Connect to Project for the web data through Power BI
> Desktop](https://docs.microsoft.com/project-for-the-web/connect-to-project-for-the-web-data-through-powerbi-desktop)
> for more information about determining the URL.

How the sample affects your tenant data
---------------------------------------

This sample has minimal impact on your tenant data. It only queries CDS
to retrieve project data to generate the dashboards in Power BI.

Questions and comments
----------------------

Additional resources
--------------------

-   [Getting started with Power BI
    Desktop](https://powerbi.microsoft.com/en-us/documentation/powerbi-desktop-getting-started/)

This project has adopted the [Microsoft Open Source Code of
Conduct](https://opensource.microsoft.com/codeofconduct/). For more
information, see the [Code of Conduct
FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact
<opencode@microsoft.com> with any additional questions or comments.
