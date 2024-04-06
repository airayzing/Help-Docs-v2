---
description: This page contains the information about the 3rd party integrations.
---

# Drip CRM integration with BotBuddy

## Drip CRM Integration with BotBuddy

### Use Case

Using this Integration, you can send your leads' details such as Name, email, and phone to Drip CRM.

### Pre-requisite

* Drip CRM Account Id
* API Token

### Steps to Enable the Integration

1. **Get the Required 3rd Party Data**:
   * Obtain the Drip CRM Account Id and API Token from your Drip CRM account.
2. **Authenticate Your Account**:
   * Enter the Drip CRM Account Id and API Token obtained from the previous step.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variable**:
   * After authentication, you'll see the screen where you can map the chatbot’s answers by end-user to the fields of the Drip CRM system.
   * Use the "Question" dropdown to select the bot questions whose answers you want to store. If the dropdown isn't visible, type “/” to list down all the questions.
   * Map the selected questions to parameters in the Drip CRM system. If the dropdown isn't visible, manually enter the parameter names.
   * Add new variables as needed by clicking the “Add Parameter” button from the top right.
   * Click the “Save” button to activate your integration.
4. **Test Your Integration**:
   * Open your bot and create a new lead to test the integration. Ensure the lead is not created earlier.
   * Verify if the lead information is correctly sent to Drip CRM.
5. **Disconnect the Integration**:
   * To disconnect, navigate to the integration page under bot management.
   * Click on the 3rd party integrations and select the Drip CRM integration.
   * Click the “Disconnect” button.

### Notes

* Test leads creation in an incognito tab to avoid cache issues.
* Ensure proper subscription for using Drip CRM APIs.
* For further assistance, contact the support team.
