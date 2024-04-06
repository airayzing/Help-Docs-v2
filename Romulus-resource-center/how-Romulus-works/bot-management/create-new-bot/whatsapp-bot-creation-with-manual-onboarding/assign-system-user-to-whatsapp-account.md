---
description: >-
  This page contains the information in how you can assign system user to the
  WhatsApp Account
---

# 🦸‍♀️ Assign System User to WhatsApp Account

This document will guide you through the step-by-step process of granting control of a WhatsApp Business Account to a system user using the Meta Business Suite. By following these instructions, you can ensure that the system user has the necessary access to perform actions using a System User access token.

#### **Step 1:** Access the Meta Business Suite

1. Open your web browser and navigate to the [Meta Business Suite](https://business.facebook.com/).
2. Log in to your Meta Business Suite account using your credentials.

#### **Step 2:** Locate and Access Business Settings

1. In the Meta Business Suite, find the top-left dropdown menu that displays your business account name.
2. Click on the Settings (gear) icon next to your business account name.

#### **Step 3:** Navigate to Business Settings

1. After clicking the Settings (gear) icon, a dropdown menu will appear.
2. Click on "Business settings" from the dropdown menu.

#### **Step 4:** Create a system user

1. Navigate to `System Users` "Users" in the sidebar.
2.  Click on "System Users" and click "Add" to add a new user\
    \


    <figure><img src="../../../../../.gitbook/assets/1 – 28.png" alt=""><figcaption></figcaption></figure>
3.  Accept the policy to start adding user\
    \


    <figure><img src="../../../../../.gitbook/assets/1 – 29.png" alt=""><figcaption></figcaption></figure>
4.  Once the "Create system user" pop-up opens, Give a name (E.g. BP-WhatsApp) and keep the user role as "Admin"\
    \


    <figure><img src="../../../../../.gitbook/assets/1 – 30.png" alt=""><figcaption></figcaption></figure>
5.  Once the system user is added, Click on the "Generate new token"\
    \


    <figure><img src="../../../../../.gitbook/assets/1 – 31.png" alt=""><figcaption></figcaption></figure>
6. Once the "Generate Token" pop-up opens up,
   1. Select the App that you created earlier.
   2. Choose Token expiration as "Never"
   3. Assign following permissions
      1. business\_management
      2. catalog\_management
      3. whatsapp\_business\_messaging
      4.  whatsapp\_business\_management\
          \


          <figure><img src="../../../../../.gitbook/assets/1 – 32.png" alt=""><figcaption></figcaption></figure>
   4. Click "Generate Token"
7. Copy the token and save it safely.

#### **Step 5:** Access WhatsApp Business Accounts

1. In the Business settings page, navigate to the "Accounts" section.
2. Click on "WhatsApp Accounts."

<figure><img src="../../../../../.gitbook/assets/1 – 33.png" alt=""><figcaption></figcaption></figure>

#### **Step 6:** Assign a System User

1. On the WhatsApp Accounts page, you will see a gray "Add People" button. Click on it.
2. A list of available system users will appear.

<figure><img src="../../../../../.gitbook/assets/1 – 34.png" alt=""><figcaption></figcaption></figure>

#### **Step 7:** Assign Full Control

1. Select the appropriate system user from the list.
2. Assign "Full control" permissions to the selected system user over the WhatsApp Business Account.

<figure><img src="../../../../../.gitbook/assets/1 – 35.png" alt=""><figcaption></figcaption></figure>

Congratulations! You have successfully granted control of a WhatsApp Business Account to a system user. This allows the system user to access endpoints that require control of the WhatsApp Business Account using a System User access token.

Please ensure to grant access to trusted and authorized system users only. If you encounter any difficulties during the process or have further questions regarding WhatsApp Business Account control, please refer to the official Meta documentation or contact their support team for assistance.
