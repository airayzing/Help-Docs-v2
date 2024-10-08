---
description: This page contains the information about the 3rd party integrations.
---

# Insightly CRM integration with eleapi

## Insightly CRM Integration with eleapi

### Use Case

This integration enables you to transfer lead details such as Name, Email, and Phone from your eleapi platform to the Insightly CRM.

### Pre-requisite

To set up this integration, you'll need:

* An API Token from Insightly

### Steps to Enable the Integration

1. **Get Required 3rd Party Data:**
   * Obtain necessary information and your API Token from Insightly by referring to the [Insightly API Documentation](https://api.na1.insightly.com/v3.1/#!/Overview/Introduction).
2. **Authenticate Your Account:**
   * Enter the required details obtained from the previous step.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables:**
   * Once authenticated, you'll see a screen where you can map the eleapi’s answers to the fields of your Insightly CRM.
   * Select the bot questions from the "Question" dropdown or type "/" to list all questions.
   * Map these questions to parameters in your Insightly CRM. If dropdowns are not available, enter the parameter names manually.
   * Add new variables as needed by clicking the "Add Parameter" button.
   * Click “Save” to activate your integration.
4. **Test Your Integration:**
   * Open your bot and create a new lead to test the integration. Ensure that the lead is not created earlier.

### Disconnecting the Integration

To disconnect the integration:

1. Open the integration page under bot management.
2. Click on the 3rd party integrations and select the target integration (Insightly).
3. Click on the “Disconnect” button to disconnect.

### Notes

* To test leads, create the chat in an incognito tab to avoid cache issues.
* Ensure you have the proper subscription for the 3rd party to use the APIs.
* Please contact the support team if you need further assistance.
