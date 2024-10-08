---
description: This page contains the information about the 3rd party integrations.
---

# Drip CRM integration with tropitech

## Drip CRM Integration

This documentation provides instructions for integrating Drip CRM with your chatbot. By following these steps, you'll be able to seamlessly send lead details such as Name, Email, and Phone to Drip CRM.

### Use Case

This integration allows you to efficiently transfer lead details captured by your chatbot to Drip CRM, facilitating streamlined lead management.

### Prerequisites

Before enabling the integration, ensure you have the following prerequisites:

* **Drip CRM Account Id**: Obtain your Drip CRM account ID.
* **API Token**: Obtain an API token from your Drip CRM account.

### Steps to Enable the Integration

Follow these steps to enable the integration between Drip CRM and your chatbot:

1. **Get the Required 3rd Party Data**:
   * Obtain the necessary account ID and API token from your Drip CRM account. Refer to [this guide](https://help.drip.com/hc/en-us/articles/4424702665357-Pipedrive) for assistance.
2. **Authenticate Your Account**:
   * Enter the obtained Drip CRM account ID and API token in the provided fields.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables**:
   * After authentication, you'll be directed to a screen where you can map chatbot responses to Drip CRM fields.
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

For further assistance, please contact [support team](mailto:ventas@tropitechtechnology.com).
