---
description: This page contains the information about the 3rd party integrations.
---

# Flowlu integration with Romulus

### Use Case

This integration allows you to send lead details such as Name, email, and phone to Flowlu.

### Pre-requisite

* Flowlu Domain
* API Token
* Title

### Steps to Enable the Integration

1. **Get the Required 3rd Party Data**:
   * Obtain the Flowlu Domain, API Token, and Title from your Flowlu account.
2. **Authenticate Your Account**:
   * Enter the required details obtained from the previous step.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variable**:
   * After authentication, you'll see the screen where you can map the chatbot’s answers by end-user to the fields of the Flowlu system.
   * Use the "Question" dropdown to select the bot questions whose answers you want to store. If the dropdown isn't visible, type “/” to list down all the questions.
   * Map the selected questions to parameters in the Flowlu system. If the dropdown isn't visible, manually enter the parameter names.
   * Add new variables as needed by clicking the “Add Parameter” button from the top right.
   * Click the “Save” button to activate your integration.
4. **Test Your Integration**:
   * Open your bot and create a new lead to test the integration. Ensure the lead is not created earlier.
   * Verify if the lead information is correctly sent to Flowlu.
5. **Disconnect the Integration**:
   * To disconnect, navigate to the integration page under bot management.
   * Click on the 3rd party integrations and select the Flowlu integration.
   * Click the “Disconnect” button.

### Notes

* Test lead creation in an incognito tab to avoid cache issues.
* Ensure you have proper subscription for using Flowlu APIs.
* For further assistance, contact the support team.
