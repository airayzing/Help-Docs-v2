---
description: This page contains the information about the 3rd party integrations.
---

# MoEngage CRM integration with ChatbotWorld

This documentation provides step-by-step instructions for integrating MoEngage CRM with ChatbotWorld. By following these steps, you'll be able to seamlessly send lead details such as Name, Email, and Phone to MoEngage CRM.

### Use Case

This integration facilitates the transfer of lead details captured by your chatbot to MoEngage CRM, streamlining your lead management process.

### Prerequisites

Before enabling the integration, ensure you have the following prerequisites:

* **API URL**: Obtain the API URL from your MoEngage CRM account.
* **APP ID**: Obtain the APP ID from your MoEngage CRM account.
* **DATA API KEY**: Obtain the DATA API KEY from your MoEngage CRM account.

### Steps to Enable the Integration

Follow these steps to enable the integration between MoEngage CRM and ChatbotWorld:

1. **Get the Required 3rd Party Data**:
   * Obtain the necessary API URL, APP ID, and DATA API KEY from your MoEngage CRM account. Refer to [this guide](https://developers.moengage.com/hc/en-us/articles/4413167462804-Track-User#h\_01HRVRH0WAW0BHPVKS6WQ9X7HG) for assistance.
2. **Authenticate Your Account**:
   * Enter the required API URL, APP ID, and DATA API KEY in the provided fields.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables**:
   * Once Authenticated, you'll see the screen where you can map the chatbot’s answers by end user to the fields of the target 3rd party system.
   * Click on the “Question” dropdown to select the bot questions whose answers you want to store. If you don't see the dropdown, type "/" to list all questions.
   * Map these answers to parameters in the next field. If you don't see the dropdown here, enter the parameter name of your 3rd party system.
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
