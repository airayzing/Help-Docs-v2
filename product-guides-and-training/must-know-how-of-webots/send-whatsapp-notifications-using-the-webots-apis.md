---
description: >-
  This page contains the Information on how can you send WhatsApp Notifications
  from your platform using the WeBots APIs
---

# 📨 Send WhatsApp notifications using the WeBots APIs

Before we start, Let's understand the basic workflow.

To create a notification bot with WeBots, follow these steps:

**Step 1: Get Your API Key**

* Start by obtaining your API key for integration. Refer to the below doc for more details

{% content-ref url="../../api-references/whatsapp-cloud-api/" %}
[whatsapp-cloud-api](../../api-references/whatsapp-cloud-api/)
{% endcontent-ref %}

**Step 2: Setup the WebHook Endpoint**

* Configure the WebHook endpoint where your bot will send and receive messages. Refer to the below doc for more details

{% content-ref url="../../api-references/whatsapp-cloud-api/" %}
[whatsapp-cloud-api](../../api-references/whatsapp-cloud-api/)
{% endcontent-ref %}

**Step 3: Create Notification Templates**

* Ensure you've created the required notification templates that your bot will use for messaging.

**Step 4: Retrieve Notification Templates**

* Call the "Get Template API" to retrieve all the templates you've created. Refer to the below doc for more details

{% content-ref url="../../api-references/whatsapp-cloud-api/get-templates-list.md" %}
[get-templates-list.md](../../api-references/whatsapp-cloud-api/get-templates-list.md)
{% endcontent-ref %}

**Step 5: Send Messages**

* Utilize the "POST WhatsApp Template API" to send messages using the templates. Refer to the below doc for more details

{% content-ref url="../../api-references/whatsapp-cloud-api/post-whatsapp-template-message.md" %}
[post-whatsapp-template-message.md](../../api-references/whatsapp-cloud-api/post-whatsapp-template-message.md)
{% endcontent-ref %}

**Step 6: Configure Webhook Handling**

* Implement the necessary code to handle the webhook on the configured endpoint. This is where your bot will receive and process incoming messages and notifications.

**Step 7: You're Done!**

* With these steps completed, your notification bot is ready to send and receive messages using your templates, ensuring efficient and effective communication with your audience.
