---
description: This page contains all the open APIs available for the WhatsApp
---

# 📄 WhatsApp Cloud API

## 1. Create and Sync Templates

The team will be required to create and get the templates approved by the Facebook WhatsApp Business Manager or m1bot Dashboard. Once It is done,

1. Go to m1bot Panel
2. Navigate to WhatsApp Automation and Then go to the manage section.
3. Under templates, You will be required to sync templates from Facebook, Once Done, App should use the get Templates API and save the template details. These details will be required to send Notifications.

## 2. API Key

In order to generate the WhatsApp API key,

1. Go to the m1bot Dashboard ( [https://m1bot.mark1.ai//](https://app.m1bot.com/) )
2. Find your bot and go to `WhatsApp Bot Settings` section.
3. Under `WhatsApp Bot Settings`, Navigate to the API key and Click on generate an API key.
4. You will require to update the webhook URL, on which we will send the delivery reports.
5. Once done, Copy the key and save it yourself.

## 3. APIs Endpoints

{% content-ref url="get-templates-list.md" %}
[get-templates-list.md](get-templates-list.md)
{% endcontent-ref %}

{% content-ref url="post-whatsapp-template-message.md" %}
[post-whatsapp-template-message.md](post-whatsapp-template-message.md)
{% endcontent-ref %}

{% content-ref url="post-send-message-api.md" %}
[post-send-message-api.md](post-send-message-api.md)
{% endcontent-ref %}

## Error Codes

Please refer to the link below for more info on the error codes

[https://developers.facebook.com/docs/whatsapp/on-premises/errors](https://developers.facebook.com/docs/whatsapp/on-premises/errors)
