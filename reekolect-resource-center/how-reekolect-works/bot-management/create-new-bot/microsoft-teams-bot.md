---
description: >-
  This page provides guidelines on creating a Microsoft Teams bot using the
  Microsoft Developer Panel.
---

# 📖 Microsoft Teams Bot

### Required Information for Creating an MS Teams Chatbot:

To integrate with Microsoft Teams, ensure you have the following details:

* **Bot ID**
* **Bot Password**
* **Webhook Endpoint** – Update this in the Bot Details.
* **App Creation & Publishing** – Develop and publish an app for your organization.

### Steps to complete integration <a href="#steps-to-complete-integration" id="steps-to-complete-integration"></a>

#### Step 1: Setup MS Teams Bot <a href="#step-1-setup-ms-teams-bot" id="step-1-setup-ms-teams-bot"></a>

1. Log in to MS Teams using the following URL: [https://teams.microsoft.com/v2/](https://teams.microsoft.com/v2/). If you do not have the MS Teams documentation, ensure it is created before proceeding.
2. Once logged in, navigate to the MS Teams Developer Portal.
3. Choose the "Tools" tab and click on "Bot Management Option"
4. On this page, find the **"New Bot"** option and create a bot by assigning it a name.
5. After the bot is created, enter the Webhook endpoint address and click **"Save"** to proceed.
6. Navigate to "Client Secrets" and add new and Copy the Provide secret key. Keep this secret key safe. This will be used while creating the configuration on Reekolect.
7. Navigate back to the bot listing page and copy the **"Bot ID."** Keep this key secure, as it will be required for configuring the bot on Reekolect.

#### Step 2: Create the MS Teams App

1. Navigate to the **"Apps"** tab and click on **"New App."**
2. Create a new app by providing a name (e.g., **Reekolect**).
3. Fill in the basic details of the app as follows(eg below):
   1. **Short Name**: Reekolect
   2. **Full Name**: Reekolect – The chatbot builder platform
   3. **Short Description**: Reekolect is an omnichannel platform designed to automate your communications.
   4. **Long Description**: Reekolect is a sophisticated chatbot platform that enhances and streamlines conversational experiences for businesses across various industries. Focused on user-friendly interactions, Reekolect leverages artificial intelligence and natural language processing to create intelligent chatbots capable of efficiently handling customer queries, providing information, and engaging in meaningful conversations.
   5. **Version**: 1.0.0
   6. **Developer or Company Name**: Reekolect
   7. **Website (must be a valid HTTPS URL)**: https://reekolect.com/
   8. **Privacy Policy**: https://reekolect.com/privacy-policy
   9. **Terms of Use**: https://reekolect.com/terms-and-conditions
   10. **App ID**: Same as **Bot ID**
4. You can give your own branding to your app or leave as it is.
5.  Go to the **"App Features"** tab and add the **"Bot."** Once the next page opens, select the appropriate bot and assign the following scopes:

    * **Personal**
    * **Teams**
    * **Group Chat**

    Additionally, enable the following capabilities under **"What your bot can do"**:

    * **Upload and Download Files**
6. Now, navigate to the **"Publish to Org"** tab and submit your app for approval within your organization.

#### Step 3: Approve Your App as Admin

1. Open the **Teams Admin Portal** using the following link: [https://admin.teams.microsoft.com/](https://admin.teams.microsoft.com/)
2. Navigate to the **"Manage Apps"** section under **"Team Apps."**
3. Search for your app and select it. Approve it by:
   1. Clicking on the app and selecting **"Publish."**
   2. Once approved, the app may take some time to appear for your users.

#### Step 4: Save the Configuration on Reekolect

1. Navigate to the **Reekolect Dashboard**.
2. Click on **"Create New Bot"** in the top left corner.
3. Select **MS Teams** as the channel.
4. Enter a name for your bot and input the **Bot ID** and **Bot Secret (Bot Password)** that you copied in Step 1.

Once the details are updated, your bot will be successfully created.

