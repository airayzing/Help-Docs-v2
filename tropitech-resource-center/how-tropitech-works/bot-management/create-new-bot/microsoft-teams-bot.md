---
description: >-
  This page contains information on how to create Microsoft teams, bot on
  Microsoft developer panel.
---

# 📖 Microsoft Teams Bot

## Required information for Creating MS Teams Chatbot <a href="#required-information-for-creating-ms-teams-chatbot" id="required-information-for-creating-ms-teams-chatbot"></a>

To integrate your chatbot with MS Teams, ensure you have the following details:

* **Bot ID**
* **Bot Password**
* **Webhook Endpoint** (Update it in the Bot Details)
* **Create and Publish** an app for your organization



## Steps to complete integration <a href="#steps-to-complete-integration" id="steps-to-complete-integration"></a>

## Step 1: Setup MS Teams Bot <a href="#step-1-setup-ms-teams-bot" id="step-1-setup-ms-teams-bot"></a>

1. Login to the MS Teams using the following URL [https://teams.microsoft.com/v2/](https://teams.microsoft.com/v2/). If you do not have the MS Teams documentation, Create the one before proceeding.
2. Once logged in, Navigate to the developer portal of MS Teams.
3. Choose the "Tools" tab and click on "Bot Management Option"
4. On this Page, Locate the "New Bot" option and add the bot by giving it a name.
5. Once the bot is created, Enter the following Webhook endpoint address and click "save" to <mark style="background-color:yellow;">proceed. https://api.v7.botpenguin.com/ms-teams/webhook</mark>
6. Navigate to "Client Secrets" and add new and Copy the Provide secret key. Keep this secret key safe. This will be used while creating the configuration on Tropitech.
7. Return to the bot listing page and copy the "Bot ID". Keep this key safe. This will be used while creating the configuration on Tropitech.

## Step 2: Create the MS Teams App <a href="#step-2-create-the-ms-teams-app" id="step-2-create-the-ms-teams-app"></a>

1. Navigate back to the "Apps" tab and click on "New App".
2. Create the new app by providing the name. (e.g Tropitech)
3. Fill in the basic information of the App. An example of the same is as follows
   1. Short Name - Tropitech
   2. Full name - Tropitech - The chatbot builder platform
   3. Short description- Tropitech is an omnichannel platform to automate your communications.
   4. Long description - Tropitech is an advanced chatbot platform designed to streamline and enhance conversational experiences for businesses across various industries. With a focus on user-friendly interactions, Tropitech leverages artificial intelligence and natural language processing to create intelligent chatbots that can efficiently handle customer queries, provide information, and engage in meaningful conversations.
   5. Version - 1.0.0
   6. Developer or company name - Tropitech
   7. Website (must be a valid HTTPS URL) - [<mark style="background-color:yellow;">https://botpenguin.com/</mark>](https://botpenguin.com/)
   8. Privacy policy- [<mark style="background-color:yellow;">https://botpenguin.com/privacy-policy</mark>](https://botpenguin.com/privacy-policy)
   9. Terms of use <mark style="background-color:yellow;">-</mark> [<mark style="background-color:yellow;">https://botpenguin.com/terms-and-conditions</mark>](https://botpenguin.com/terms-and-conditions)
   10. App ID: Same as Bot ID
4. You can give your own branding to your app or leave as it is.
5.  Navigate to the "App Features" tab and add the "Bot". Once the next page opens, choose the relevant bot and assign the following scopes

    1. Personal
    2. Teams
    3. Group Chat

    Also, Check the following options under what your bot can do.

    1. Upload and Download files
6. Now, Move to the "Publish to Org" tab, and Submit your app for your organization.

## Step 3: Approve your app as Admin <a href="#step-3-approve-your-app-as-admin" id="step-3-approve-your-app-as-admin"></a>

1. Open the Teams admin portal using the following link [https://admin.teams.microsoft.com/](https://admin.teams.microsoft.com/)
2. Locate the "Manage Apps" options under the "Team Apps" Section. Search for your app and click on the same.
3. Click on the App and Click "Publish"
4. Once you have approved the apps, It takes some time to get listed for your users.

## Step 4: Save the configuration on Tropitech

1. Navigate to the [Tropitech Dashboard.](https://app.tropitechnology.com/)
2. Click on "Create new bot" on the top left.
3. Choose MS Teams as the channel.
4. Name your bot and Fill in the Bot ID and Bot Secret (Bot Password) which you copied in 1st step.

Once you have updated the same. Your bot will be created.

Please reach out to us at **soporte@tropitechnology.com** for further assistance.
