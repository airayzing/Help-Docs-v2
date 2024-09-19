---
description: This page contains the information about the 3rd party integrations.
---

# Chakra CRM integration with m1Bot

This documentation provides instructions for integrating Chakra CRM with m1Bot. By following these steps, you'll be able to seamlessly send lead details such as Name, Email, and Phone to Chakra CRM.

### Use Case

This integration facilitates the transfer of lead details captured by your chatbot to Chakra CRM, streamlining your lead management process.

### Prerequisites

Before enabling the integration, ensure you have the following prerequisite:

* **API Token**: Obtain an API token from your Chakra CRM account.

### Steps to Enable the Integration

Follow these steps to enable the integration between Chakra CRM and m1Bot:

1. **Get the Required 3rd Party Data**:
   * Obtain the necessary API token from your Chakra CRM account. Refer to [this guide](https://docs.chakrahq.com/docs/platform/api/api-keys) for assistance.
2. **Authenticate Your Account**:
   * Enter the obtained API token in the provided field.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables**:
   * After authentication, you'll be directed to a screen where you can map chatbot responses to Chakra CRM fields.
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

Use case

Using this Integration you can send you leads details such as Name, email, phone to the Chakra CRM

Pre-requisite

* API Token

Steps to enable the integrations

* Get the required 3rd party data from your 3rd party application account. You can use the following link for the same to take help [https://docs.chakrahq.com/docs/platform/api/api-keys](https://docs.chakrahq.com/docs/platform/api/api-keys)
* Authenticate your account
  * Enter the required details that you got from above steps
  * Proceed to authenticate your account credentials
* Mapping the variable
  * Once Authenticated, You will see the screen where you can map the chatbot’s answers by end user to the fields of target 3rd party system.
  * Click on the “Question” dropdown to select the bot questions whose answer you want to store. If you do not see the dropdown here, Type “/” which will list down all the questions.
  * Map the same to parameter in the next field. If you do not see the drop down here, Enter the parameter name of your 3rd party system.
  * Add new variable by clicking the “Add Parameter” button from top right.
  * Click “Save” button to activate your integration.
* Test your integration
  * Open you bot, and Create a new lead to test your integration. Make sure that your lead is not created earlier.
  * And you are done

Disconnect the integration.

* Open the the integration page under the bot management, by clicking on the 3rd party integrations and then selecting the target integration.
* Click on the “Disconnect” button to disconnect.

Notes

* In order to test the leads, Create the chat in incognito tab to avoid cache issues.
* Make sure you have proper subscription for the 3rd party to use the APIs
* Please contact support team, in case you further need help.
