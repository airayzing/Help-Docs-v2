---
description: >-
  This page contains information about the custom attributes and how you can use
  them in eleapi
---

# 🔤 Manage & Use Custom Attributes

Custom Attributes

Custom Attributes in eleapi are user-defined properties or variables that can be assigned to individual users within your eleapi platform. These attributes enable you to capture and store specific information about users, which they share during chat or can be accessed from external databases. Custom Attributes are a powerful tool for personalizing interactions and creating tailored experiences for users in your eleapi.

## Types of Custom Attributes

There are primarily two types of custom Attributes

1. Custom Attributes whose values are being defined by the answers given by users in the chat flow.
2. Custom Attributes whose values are being defined using the external API for any user.

## Primary Usage

Custom Attributes can be used for the following use cases

1. Personalize user interactions
2. Collect user data
3. Use in the WhatsApp broadcast campaigns
4. Enhance marketing, support, and engagement
5. Use of external APIs in chat flow
6. Export chat data that is not being exported by default

## Create & Manage Attributes

Custom attributes in eleapi allow you to personalize user interactions and collect specific data. Follow these steps to create and manage custom attributes:

### **Step 1: Navigate to the** eleapi **dashboard.**

* Log in to your eleapi account and access the dashboard.

### **Step 2: Access Account Settings.**

* On the side navigation bar, locate and click the "More" button.
* From the dropdown menu, select "Account/Settings."

### **Step 3: Manage Custom Attributes.**

* In the Account/Settings section, find and click on the "Custom Attributes" tab.
* Here, you'll find a list of all your custom attributes. You can edit, delete, bulk delete, and add new custom attributes from this tab.

### **Step 4: Create a New Custom Attribute.**

* To add a new attribute, click the "Add Attribute" button.
* Fill in the following details:
  * **Attribute Key**: This is the key that will be saved in the system. Keep it in lowercase characters without any special characters or spaces. For example, if you want to save the city for any user, you can use "city" as the attribute key.
  * **Attribute Name**: This will be the display name of the attribute, such as "City Name."
  * **Optional Details to fill in for saving API Response in custom attributes**
    * **Select Bot**: Choose the bot whose chat input you want to store.
    * **Select Flow**: Choose the flow of that bot.
    * **Select Question**: Choose the question whose answer you want to store.

{% hint style="info" %}
Refer to the following help doc to understand how can you use custom attributes to save your API responses.
{% endhint %}

{% content-ref url="call-external-apis-in-your-chat-flows.md" %}
[call-external-apis-in-your-chat-flows.md](call-external-apis-in-your-chat-flows.md)
{% endcontent-ref %}

And that's it! You've successfully created a custom attribute in eleapi. This attribute can now be used to personalize interactions, segment users, and enhance the overall eleapi experience.
