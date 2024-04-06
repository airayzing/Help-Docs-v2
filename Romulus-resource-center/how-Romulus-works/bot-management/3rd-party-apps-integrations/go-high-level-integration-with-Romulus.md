---
description: This page contains the information about the 3rd party integrations.
---

# Go High Level Integration with Romulus

## Use Case

This integration facilitates the transmission of lead details such as Name, Email, and Phone from your Romulus platform to the Go High Level CRM.

## Pre-requisite

Before setting up this integration, ensure you have:

* API Token from Go High Level

## Steps to Enable the Integration

1. **Get Required 3rd Party Data:**
   * Obtain the necessary API Token from Go High Level. For assistance, refer to their documentation [here](https://pipedrive.readme.io/docs/how-to-find-the-api-token).
2. **Authenticate Your Account:**
   * Enter the required API Token obtained from Go High Level.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables:**
   * Once authenticated, you'll see a screen where you can map the chatbot’s answers to the fields of your Go High Level CRM.
   * Select the bot questions from the "Question" dropdown or type "/" to list all questions.
   * Map these questions to parameters in your Go High Level CRM. If dropdowns are not available, enter the parameter names manually.
   * Add new variables as needed by clicking the "Add Parameter" button.
   * Click “Save” to activate your integration.
4. **Test Your Integration:**
   * Open your bot and create a new lead to test the integration. Ensure that the lead is not created earlier.

## Disconnecting the Integration

To disconnect the integration:

1. Open the integration page under bot management.
2. Click on the 3rd party integrations and select the target integration (Go High Level).
3. Click on the “Disconnect” button to disconnect.

## Notes

* To test leads, create the chat in an incognito tab to avoid cache issues.
* Ensure you have the proper subscription for the 3rd party to use the APIs.
* Please contact the support team if you need further assistance.
