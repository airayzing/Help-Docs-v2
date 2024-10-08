---
description: This page contains the information about the 3rd party integrations.
---

<<<<<<<< HEAD:tropitech-resource-center/how-tropitech-works/bot-management/3rd-party-apps-integrations/helpshift-integration-with-tropitech.md
# HelpShift integration with tropitech

### Use Case

This integration allows you to transfer lead details such as Name, Email, and Phone from your tropitech platform to HelpShift.
========
<<<<<<<< HEAD:m1Bot-resource-center/how-m1Bot-works/bot-management/3rd-party-apps-integrations/helpshift-integration-with-m1bot_1.md
# HelpShift integration with m1bot

### Use Case

This integration allows you to transfer lead details such as Name, Email, and Phone from your m1bot platform to HelpShift.
========
# HelpShift integration with EkoChat Connect

### Use Case

This integration allows you to transfer lead details such as Name, Email, and Phone from your EkoChat Connect platform to HelpShift.
>>>>>>>> a4cbe70f0174e74b40121f7a3e60e7bdc5c6e923:ekochatconnect-resource-center/how-ekochatconnect-works/bot-management/3rd-party-apps-integrations/helpshift-integration-with-ekochatconnect.md
>>>>>>>> e3924ba1285985f801a086ecf58553cde6ad400a:tropitech-resource-center/how-tropitech-works/bot-management/3rd-party-apps-integrations/helpshift-integration-with-m1bot.md

### Pre-requisite

Before setting up this integration, ensure you have:

* Domain Name
* API Key from HelpShift

### Steps to Enable the Integration

1. **Get Required 3rd Party Data:**
   * Obtain the necessary API Key and Domain Name from HelpShift. For assistance, refer to their documentation [here](https://developers.helpshift.com/rest-api/getting-started/).
2. **Authenticate Your Account:**
   * Enter the required details, including Domain Name and API Key obtained from HelpShift.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variables:**
   * Once authenticated, you'll see a screen where you can map the chatbot’s answers to the fields of your HelpShift system.
   * Select the bot questions from the "Question" dropdown or type "/" to list all questions.
   * Map these questions to parameters in your HelpShift system. If dropdowns are not available, enter the parameter names manually.
   * Add new variables as needed by clicking the "Add Parameter" button.
   * Click “Save” to activate your integration.
4. **Test Your Integration:**
   * Open your bot and create a new lead to test the integration. Ensure that the lead is not created earlier.

### Disconnecting the Integration

To disconnect the integration:

1. Open the integration page under bot management.
2. Click on the 3rd party integrations and select the target integration (HelpShift).
3. Click on the “Disconnect” button to disconnect.

### Notes

* To test leads, create the chat in an incognito tab to avoid cache issues.
* Ensure you have the proper subscription for the 3rd party to use the APIs.
* Please contact the support team if you need further assistance.
