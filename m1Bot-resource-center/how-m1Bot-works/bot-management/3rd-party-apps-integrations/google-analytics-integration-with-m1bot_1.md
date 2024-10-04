---
description: This page contains the information about the 3rd party integrations.
---

# Google Analytics integration with m1bot

To integrate your bot with Google Analytics, you'll need to follow these steps:

## Use case

Using this Integration you can send your leads details such as Name, email, phone to Google Analytics.

## Pre-requisite

* Measurement ID

## Steps to enable the integration

1. **Get the required 3rd party data**:
   * Visit [Google Analytics Developer Documentation](https://developers.google.com/analytics/devguides/reporting/data/v1/quickstart-client-libraries) to obtain necessary information.
2. **Authenticate your account**:
   * Enter the required details obtained from the above steps.
   * Proceed to authenticate your account credentials.
3. **Mapping the variable**:
   * Once authenticated, you will see the screen where you can map the chatbot’s answers by end-user to the fields of the Google Analytics system.
   * Click on the “Question” dropdown to select the bot questions whose answer you want to store. If you do not see the dropdown here, Type “/” which will list down all the questions.
   * Map the same to parameter in the next field. If you do not see the drop down here, Enter the parameter name of your 3rd party system.
   * Add a new variable by clicking the “Add Parameter” button from the top right.
   * Click the “Save” button to activate your integration.
4. **Test your integration**:
   * Open your bot, and create a new lead to test your integration. Ensure that your lead is not created earlier.
   * Verify if the lead information is correctly sent to Google Analytics.
5. **Disconnect the integration**:
   * Open the integration page under the bot management by clicking on the 3rd party integrations and then selecting the Google Analytics integration.
   * Click on the “Disconnect” button to disconnect.

## Notes

* In order to test the leads, create the chat in incognito tab to avoid cache issues.
* Make sure you have proper subscription for the 3rd party to use the APIs.
* Please contact the support team in case you further need help.
