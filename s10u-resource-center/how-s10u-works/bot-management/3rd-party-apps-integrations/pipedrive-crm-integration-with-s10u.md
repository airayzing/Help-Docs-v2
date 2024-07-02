---
description: This page contains the information about the 3rd party integrations.
---

# Pipedrive CRM integration with S10U AI Studio

### Use Case

This integration allows you to seamlessly send lead details such as Name, Email, and Phone to the Pipedrive CRM from your S10U AI Studio platform.

### Pre-requisite

To set up this integration, you'll need:

* A Pipedrive domain
* An API Token from Pipedrive

### Steps to Enable the Integration

1. **Get Required 3rd Party Data:**
   * Obtain your API Token from Pipedrive by following [this link](https://pipedrive.readme.io/docs/how-to-find-the-api-token).
2. **Authenticate Your Account:**
   * Enter the required details obtained from the previous step.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables:**
   * After authentication, you'll see a screen where you can map the chatbot’s answers to the fields of your Pipedrive CRM.
   * Select the bot questions from the "Question" dropdown or type "/" to list down all the questions.
   * Map these questions to parameters in your Pipedrive CRM. If dropdowns are not available, enter the parameter names manually.
   * Add new variables as needed by clicking the "Add Parameter" button.
   * Click "Save" to activate your integration.
4. **Test Your Integration:**
   * Open your bot and create a new lead to test the integration. Ensure that the lead is not created earlier.

### Disconnecting the Integration

To disconnect the integration:

1. Open the integration page under bot management.
2. Click on the 3rd party integrations and select the target integration (Pipedrive).
3. Click on the "Disconnect" button to disconnect.

### Notes

* To test leads, create the chat in an incognito tab to avoid cache issues.
* Ensure you have the proper subscription for the 3rd party to use the APIs.
* Contact the support team if you need further assistance.
