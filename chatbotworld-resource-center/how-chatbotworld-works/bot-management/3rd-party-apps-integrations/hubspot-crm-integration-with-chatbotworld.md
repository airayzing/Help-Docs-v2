---
description: This page contains the information about the 3rd party integrations.
---

# Hubspot CRM integration with ChatbotWorld

This documentation provides instructions for integrating HubSpot CRM with ChatbotWorld. By following these steps, you'll be able to seamlessly send lead details such as Name, Email, and Phone to HubSpot CRM.

### Use Case

This integration facilitates the transfer of lead details captured by your chatbot to HubSpot CRM, streamlining your lead management process.

### Prerequisites

Before enabling the integration, ensure you have the following prerequisites:

* **API Token**: Obtain an API token from your HubSpot account.

### Steps to Enable the Integration

Follow these steps to enable the integration between HubSpot CRM and ChatbotWorld:

1. **Get the Required 3rd Party Data**:
   * Obtain the necessary API token from your HubSpot account. Refer to [this guide](https://knowledge.hubspot.com/integrations/how-do-i-get-my-hubspot-api-key) for assistance.
2. **Authenticate Your Account**:
   * Enter the obtained API token in the provided field.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables**:
   * After authentication, you'll be directed to a screen where you can map chatbot responses to HubSpot CRM fields.
   * Use the "Question" dropdown to select the bot questions whose answers you want to store. If you don't see the dropdown, type "/" to list all questions.
   * Map these answers to parameters in the next field. If you don't see the dropdown, enter the parameter name of your 3rd party system.
   * Add new variables by clicking the “Add Parameter” button from the top right.
   * Click the “Save” button to activate your integration.
4. **Test Your Integration**:
   * Open your bot and create a new lead to test the integration.
   * Ensure that the lead is not created earlier.

### Disconnect the Integration

If you need to disconnect the integration, follow these steps:

1. **Access Integration Page**:
   * Navigate to the integration page under bot management by clicking on "3rd Party Integrations" and selecting the target integration.
2. **Disconnect**:
   * Click on the “Disconnect” button to sever the connection.

### Notes

Here are some important notes to consider:

* **Testing Leads**: To test leads, create chats in an incognito tab to avoid cache issues.
* **Subscription Requirement**: Ensure you have the proper subscription for the 3rd party to use the APIs.
* **Further Assistance**: Contact our support team if you need additional help or encounter any issues during the integration process.

For further assistance, please contact [support team](mailto:support@example.com).
