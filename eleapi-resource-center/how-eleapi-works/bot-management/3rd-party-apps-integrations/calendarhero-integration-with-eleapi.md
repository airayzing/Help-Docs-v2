---
description: This page contains the information about the 3rd party integrations.
---

# CalendarHero integration with EleAPI

### Use Case

Using this integration, you can send your leads' details such as Name, email, and phone to CalendarHero.

### Pre-requisite

* API Token

### Steps to Enable the Integration

1. **Get the Required 3rd Party Data**:
   * Obtain the API Token from your CalendarHero account.
2. **Authenticate Your Account**:
   * Enter the API Token obtained from CalendarHero into the corresponding field.
   * Proceed to authenticate your account credentials.
3. **Mapping the Variable**:
   * After authentication, you'll see the screen where you can map the eleapi’s answers by end-user to the fields of the CalendarHero system.
   * Use the "Question" dropdown to select the bot questions whose answers you want to store. If the dropdown isn't visible, type “/” to list down all the questions.
   * Map the selected questions to parameters in the CalendarHero system. If the dropdown isn't visible, manually enter the parameter names.
   * Add new variables as needed by clicking the “Add Parameter” button from the top right.
   * Click the “Save” button to activate your integration.
4. **Test Your Integration**:
   * Open your bot and create a new lead to test the integration. Ensure the lead is not created earlier.
   * Verify if the lead information is correctly sent to CalendarHero.
5. **Disconnect the Integration**:
   * To disconnect, navigate to the integration page under bot management.
   * Click on the 3rd party integrations and select the CalendarHero integration.
   * Click the “Disconnect” button.

### Notes

* Test leads creation in an incognito tab to avoid cache issues.
* Ensure proper subscription for using CalendarHero APIs.
* For further assistance, contact the support team.
