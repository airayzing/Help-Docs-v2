---
description: This page contains the information about the 3rd party integrations.
---

# SendInBlue integration with Romulus

### Use Case

This integration enables you to send lead details such as Name, email, and phone to SendInBlue.

### Pre-requisite

* API Key

### Steps to Enable the Integration

1. **Get the Required 3rd Party Data**:
   * Obtain the API Key from your SendInBlue account.
2. **Authenticate Your Account**:
   * Enter the API Key obtained from the previous step.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variable**:
   * After authentication, you'll see the screen where you can map the chatbot’s answers by end-user to the fields of the SendInBlue system.
   * Use the "Question" dropdown to select the bot questions whose answers you want to store. If the dropdown isn't visible, type “/” to list down all the questions.
   * Map the selected questions to parameters in the SendInBlue system. If the dropdown isn't visible, manually enter the parameter names.
   * Add new variables as needed by clicking the “Add Parameter” button from the top right.
   * Click the “Save” button to activate your integration.
4. **Test Your Integration**:
   * Open your bot and create a new lead to test the integration. Ensure the lead is not created earlier.
   * Verify if the lead information is correctly sent to SendInBlue.
5. **Disconnect the Integration**:
   * To disconnect, navigate to the integration page under bot management.
   * Click on the 3rd party integrations and select the SendInBlue integration.
   * Click the “Disconnect” button.

### Notes

* Test lead creation in an incognito tab to avoid cache issues.
* Ensure you have the proper subscription for using SendInBlue APIs.
* For further assistance, contact the support team.
