---
description: This page contains the information about the 3rd party integrations.
---

<<<<<<<< HEAD:m1Bot-resource-center/how-m1Bot-works/bot-management/3rd-party-apps-integrations/onpipeline-integration-with-m1bot_1.md
# Onpipeline integration with m1bot

### Use Case

This integration facilitates the transmission of lead details such as Name, Email, and Phone from your m1bot platform to the Onpipeline CRM.
========
# Onpipeline integration with EkoChat Connect

### Use Case

This integration facilitates the transmission of lead details such as Name, Email, and Phone from your EkoChat Connect platform to the Onpipeline CRM.
>>>>>>>> a4cbe70f0174e74b40121f7a3e60e7bdc5c6e923:ekochatconnect-resource-center/how-ekochatconnect-works/bot-management/3rd-party-apps-integrations/onpipeline-integration-with-ekochatconnect.md

### Pre-requisite

Before setting up this integration, ensure you have:

* Secret Token from Onpipeline

### Steps to Enable the Integration

1. **Get Required 3rd Party Data:**
   * Obtain the necessary Secret Token from Onpipeline. For assistance, refer to their documentation [here](https://www.onpipeline.com/developers/).
2. **Authenticate Your Account:**
   * Enter the required Secret Token obtained from Onpipeline.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables:**
   * Once authenticated, you'll see a screen where you can map the chatbot’s answers to the fields of your Onpipeline CRM.
   * Select the bot questions from the "Question" dropdown or type "/" to list all questions.
   * Map these questions to parameters in your Onpipeline CRM. If dropdowns are not available, enter the parameter names manually.
   * Add new variables as needed by clicking the "Add Parameter" button.
   * Click “Save” to activate your integration.
4. **Test Your Integration:**
   * Open your bot and create a new lead to test the integration. Ensure that the lead is not created earlier.

### Disconnecting the Integration

To disconnect the integration:

1. Open the integration page under bot management.
2. Click on the 3rd party integrations and select the target integration (Onpipeline).
3. Click on the “Disconnect” button to disconnect.

### Notes

* To test leads, create the chat in an incognito tab to avoid cache issues.
* Ensure you have the proper subscription for the 3rd party to use the APIs.
* Please contact the support team if you need further assistance.
