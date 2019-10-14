# IntegrationWithSFtoMSdynamic
Callout from Salesforce to Ms Dyanmics CRM

“Microsoft Dynamic 365” is ERP and CRM solutions provided by Microsoft. It provides solutions for different apps like Sales, Customer Service, Field Service, Project Service Automation, Finance & Operations, Talent and Retail.

Microsoft provides “Common Data Service Web API” a REST API. This Web API provides a RESTful programming experience, we can perform the different operations on organization data with this API.

Now, GoTo Azure portal 

Click on Azure Active Directory | App registrations | New registration.

Create New App
Copy the client ID (This will be used later in the integration code)
Click on Certification & secretes  | Copy the client secrete (later we will use this in integration code).

 Click on API permission and add API Permissions.
 Grant consent
 
 The first step for integrating any third party API is Authorization, so let’s authenticate the app (MS Dynamic CRM) and get the AccessToken by making HTTP request/callout using APEX code in Salesforce.
 
 Once you get the AccessToken after that , you can easily do your Get/Post/PUT requests from SF to MS Dynamics CRM
