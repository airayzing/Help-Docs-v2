---
description: This page contains the information about the 3rd party integrations.
---

# Jira CRM integration with EleAPI

### Use Case

This integration facilitates the transmission of lead details such as Name, Email, and Phone from your EleAPI platform to the Jira CRM.

### Pre-requisite

Before setting up this integration, ensure you have:

* API Token
* Email Address
* API URL for Jira

### Steps to Enable the Integration

1. **Get Required 3rd Party Data:**
   * Obtain the necessary API Token, Email Address, and API URL from Jira. For assistance, refer to their documentation or contact their support team.
2. **Authenticate Your Account:**
   * Enter the required details, including API Token, Email Address, and API URL obtained from Jira.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables:**
   * Once authenticated, you'll see a screen where you can map the eleapi’s answers to the fields of your Jira CRM.
   * Select the bot questions from the "Question" dropdown or type "/" to list all questions.
   * Map these questions to parameters in your Jira CRM. If dropdowns are not available, enter the parameter names manually.
   * Add new variables as needed by clicking the "Add Parameter" button.
   * Click “Save” to activate your integration.
4. **Test Your Integration:**
   * Open your bot and create a new lead to test the integration. Ensure that the lead is not created earlier.

### Disconnecting the Integration

To disconnect the integration:

1. Open the integration page under bot management.
2. Click on the 3rd party integrations and select the target integration (Jira).
3. Click on the “Disconnect” button to disconnect.

### Notes

* To test leads, create the chat in an incognito tab to avoid cache issues.
* Ensure you have the proper subscription for the 3rd party to use the APIs.
* Please contact the support team if you need further assistance.
