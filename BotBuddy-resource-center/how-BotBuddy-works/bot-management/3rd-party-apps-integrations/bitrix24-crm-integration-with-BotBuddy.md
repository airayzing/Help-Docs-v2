---
description: This page contains the information about the 3rd party integrations.
---

# Bitrix24 CRM Integration with BotBuddy

## Use Case

This integration enables the transfer of lead details such as Name, Email, and Phone from your BotBuddy platform to the Bitrix24 CRM.

## Pre-requisite

Before setting up this integration, ensure you have:

* Inbound Webhook URL
* Lead Title
* Source for the leads

## Steps to Enable the Integration

1. **Get Required 3rd Party Data:**
   * Obtain the necessary details from your Bitrix24 CRM account.
2. **Authenticate Your Account:**
   * Enter the required details obtained from Bitrix24.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables:**
   * Once authenticated, you'll see a screen where you can map the chatbot’s answers to the fields of your Bitrix24 CRM.
   * Select the bot questions from the "Question" dropdown or type "/" to list all questions.
   * Map these questions to parameters in your Bitrix24 CRM. If dropdowns are not available, enter the parameter names manually.
   * Add new variables as needed by clicking the "Add Parameter" button.
   * Click “Save” to activate your integration.
4. **Test Your Integration:**
   * Open your bot and create a new lead to test the integration. Ensure that the lead is not created earlier.

## Disconnecting the Integration

To disconnect the integration:

1. Open the integration page under bot management.
2. Click on the 3rd party integrations and select the target integration (Bitrix24).
3. Click on the “Disconnect” button to disconnect.

## Notes

* To test leads, create the chat in an incognito tab to avoid cache issues.
* Ensure you have the proper subscription for the 3rd party to use the APIs.
* Please contact the support team if you need further assistance.
