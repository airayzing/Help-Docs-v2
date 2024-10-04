---
description: >-
  This page contains information about how you can call external APIs in your
  chat flows.
---

# 🖥️ Call external APIs in your chat flows

{% hint style="success" %}
Currently, the API chat component is only being supported for WhatsApp Bot, Coming soon for the rest of the channels.
{% endhint %}

## What is an external API?

An external API (Application Programming Interface) refers to a set of rules and protocols that allow one software application to interact and communicate with another external software system, service, or platform. It enables different software programs to access and exchange data and functionalities seamlessly, even if they are developed by different organizations or run on different servers.

## Types of APIs

There are several types of APIs, each serving specific purposes and use cases.

{% hint style="info" %}
We are currently supporting the JSON-based RESTful APIs with the API key, JWT Token, or public APIs
{% endhint %}

## Workflows of using APIs in ChatFlow

Here is the flow for using the APIs in the Chatflows

<figure><img src="https://github.com/airayzing/helpdocs/blob/develop/.gitbook/assets/image%20(46).png" alt=""><figcaption><p>Workflows of using APIs in ChatFlow</p></figcaption></figure>

## Using APIs in the Chatflows

<<<<<<<< HEAD:product-guides-and-training/must-know-how-of-m1Bot/call-external-apis-in-your-chat-flows.md
To seamlessly integrate APIs into your chat flows in m1bot, follow these steps:

#### **Step 1: Access the** m1bot **Dashboard**

* Log in to your m1bot account and access the dashboard.
========
To seamlessly integrate APIs into your chat flows in EkoChat Connect, follow these steps:

#### **Step 1: Access the** EkoChat Connect **Dashboard**

* Log in to your EkoChat Connect account and access the dashboard.
>>>>>>>> a4cbe70f0174e74b40121f7a3e60e7bdc5c6e923:product-guides-and-training/must-know-how-of-ekochatconnect/call-external-apis-in-your-chat-flows.md

#### **Step 2: Navigate to the Developers Section**

* From the side navigation bar, locate and click on "More."
* Within the "More" section, select "Developers."

#### **Step 3: Prepare Custom Attributes**

* Before proceeding, ensure you have added all the necessary custom attributes that you'll require for the API interactions. Custom attributes will help capture and manage data. Refer to the doc before creating and managing the custom attributes

{% content-ref url="manage-and-use-custom-attributes.md" %}
[manage-and-use-custom-attributes.md](manage-and-use-custom-attributes.md)
{% endcontent-ref %}

#### **Step 4: Add a New API**

* In the "Developers" section, find "Your APIs" and click on "Add API" at the top right corner.

#### **Step 5: Configure Your API**

* Under "Configure APIs," set the following details. The structure is similar to Postman for testing APIs:
<<<<<<<< HEAD:product-guides-and-training/must-know-how-of-m1Bot/call-external-apis-in-your-chat-flows.md
  * **API Name**: This is the display name for the API, used for better readability within m1bot.
========
  * **API Name**: This is the display name for the API, used for better readability within EkoChat Connect.
>>>>>>>> a4cbe70f0174e74b40121f7a3e60e7bdc5c6e923:product-guides-and-training/must-know-how-of-ekochatconnect/call-external-apis-in-your-chat-flows.md
  * **API Method**: Specify the HTTP method (e.g., GET, POST, PUT).
  * **Enter API URL**: Provide the URL for the API you intend to call.
  * **Query Parameters**: Add any required query parameters.
  * **Headers**: Include necessary headers for the API.
  * **Body**: Define the request body if needed.

{% hint style="info" %}
Note: If you want to insert custom variables within the API, use "/" as a placeholder. However, for the initial setup, you'll need to enter the actual values to test the API and save the response structure.
{% endhint %}

#### **Step 6: Test the API**

<<<<<<<< HEAD:product-guides-and-training/must-know-how-of-m1Bot/call-external-apis-in-your-chat-flows.md
* Proceed to "Manage API Response" and click on "Test" the API with actual values. This will help m1bot understand the API response structure.

#### **Step 7: Map API Response to Custom Attributes**

* In the "Manage API Response" tab, you can map the API response variables to your m1bot custom attributes.
========
* Proceed to "Manage API Response" and click on "Test" the API with actual values. This will help EkoChat Connect understand the API response structure.

#### **Step 7: Map API Response to Custom Attributes**

* In the "Manage API Response" tab, you can map the API response variables to your EkoChat Connect custom attributes.
>>>>>>>> a4cbe70f0174e74b40121f7a3e60e7bdc5c6e923:product-guides-and-training/must-know-how-of-ekochatconnect/call-external-apis-in-your-chat-flows.md

#### **Step 8: Replace Actual Values**

* If required, replace the actual values in your API configuration with the custom attributes that you've mapped.

#### **Step 9: Access Your Chatflow**

* Navigate to your Bot's chatflow by clicking on "Edit your Chatflow" under the "Bots" section.

#### **Step 10: Select the "API" Chat Component**

* In the list of chat components, choose the "API" chat component.

#### **Step 11: Call the API**

* In the right panel, call the API by selecting the API you've configured earlier by its name.

#### **Step 12: Map the next Questions**

* Map the next question based on your API's response code (e.g., 200, 300, etc.). If the API response code doesn't match any predefined values, it will trigger the response mapped to "others."

And you're done! Your API is ready to enhance your chatbot's functionality and provide dynamic interactions based on API responses.
