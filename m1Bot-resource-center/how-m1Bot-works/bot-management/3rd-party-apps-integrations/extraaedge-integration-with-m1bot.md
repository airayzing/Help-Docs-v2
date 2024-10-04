---
description: This page contains the information about the 3rd party integrations.
---

<<<<<<<< HEAD:m1Bot-resource-center/how-m1Bot-works/bot-management/3rd-party-apps-integrations/extraaedge-integration-with-m1bot_1.md
# ExtraaEdge integration with m1bot

To integrate m1bot with ExtraaEdge, follow these steps:
========
# ExtraaEdge integration with EkoChat Connect

To integrate EkoChat Connect with ExtraaEdge, follow these steps:
>>>>>>>> a4cbe70f0174e74b40121f7a3e60e7bdc5c6e923:ekochatconnect-resource-center/how-ekochatconnect-works/bot-management/3rd-party-apps-integrations/extraaedge-integration-with-ekochatconnect.md

## Use case

Using this Integration, you can send your leads' details such as Name, email, phone to ExtraaEdge.

## Pre-requisite

* AuthToken
* Source

## Steps to enable the integration

1. **Get the required 3rd party data**:
   * You will need to obtain the AuthToken and Source from your ExtraaEdge account. Contact ExtraaEdge support for assistance.
2. **Authenticate your account**:
   * Enter the AuthToken and Source obtained from the above steps.
   * Proceed to authenticate your account credentials.
3. **Mapping the variable**:
   * Once authenticated, you will see the screen where you can map the chatbot’s answers by end-user to the fields of the ExtraaEdge system.
   * Click on the “Question” dropdown to select the bot questions whose answer you want to store. If you do not see the dropdown here, type “/” which will list down all the questions.
   * Map the same to parameter in the next field. If you do not see the dropdown here, Enter the parameter name of your 3rd party system.
   * Add a new variable by clicking the “Add Parameter” button from the top right.
   * Click the “Save” button to activate your integration.
4. **Test your integration**:
   * Open your bot and create a new lead to test your integration. Ensure that your lead is not created earlier.
   * Verify if the lead information is correctly sent to ExtraaEdge.
5. **Disconnect the integration**:
   * Open the integration page under the bot management by clicking on the 3rd party integrations and then selecting the ExtraaEdge integration.
   * Click on the “Disconnect” button to disconnect.

## Notes

* In order to test the leads, create the chat in an incognito tab to avoid cache issues.
* Make sure you have proper subscription for the 3rd party to use the APIs.
* Please contact the support team if you further need help.
