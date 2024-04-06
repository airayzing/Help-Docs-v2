---
description: >-
  This document provides an overview of how conversation-based pricing works on
  the WhatsApp Business Platform.
---

# 💰 Meta Conversation Pricing for WhatsApp Cloud API

{% hint style="info" %}
**Disclaimer:**

The information provided in this help document is based on Meta's (formerly Facebook) official documentation available at the following link: [https://developers.facebook.com/docs/whatsapp/pricing](https://developers.facebook.com/docs/whatsapp/pricing)

Please note that the content presented here may be subject to change over time, as per updates or revisions made by Meta. We strive to keep this document accurate and up-to-date, but we recommend referring to the official documentation for the most current and reliable information.
{% endhint %}

## **Conversations**

Conversations are 24-hour message threads between you and your customers. They are initiated when messages you send to customers are delivered. You can send any number on message back and forth within that 24 hrs window to that customer. The types of conversations are explained below in know section.

## **Meta Pricing**

Rates vary based on conversation category and country/region. You can download the rate card corresponding to your WhatsApp Business Account's currency for specific rates.

Please refer to the attached rate cards for detailed pricing information applicable from June 1, 2023.

[USD Rate Card](https://scontent-bom1-1.xx.fbcdn.net/v/t39.8562-6/343340495\_556945759927254\_5506526186653119432\_n.csv?\_nc\_cat=103\&ccb=1-7&\_nc\_sid=ae5e01&\_nc\_ohc=ZY\_dzpb7ryoAX9Mx\_7\_&\_nc\_ht=scontent-bom1-1.xx\&oh=00\_AfC9QY9nz38nNeaB\_udN4n6iP56v84XU93P8PNCZ2vWyUA\&oe=64C64410)

[AUD Rate Card](https://scontent-bom1-1.xx.fbcdn.net/v/t39.8562-6/343403527\_1399085574161257\_7957938098203512225\_n.csv?\_nc\_cat=106\&ccb=1-7&\_nc\_sid=ae5e01&\_nc\_ohc=0dHshAZqMrEAX9p00FX&\_nc\_ht=scontent-bom1-1.xx\&oh=00\_AfDuRa3CuJLJEUSBG4QPlqEZnGYLSbxRnbfIiSmLFaSXbQ\&oe=64C506A9)

[EUR Rate Card](https://scontent-bom1-2.xx.fbcdn.net/v/t39.8562-6/343404204\_769125344863137\_605638969643820424\_n.csv?\_nc\_cat=107\&ccb=1-7&\_nc\_sid=ae5e01&\_nc\_ohc=EhgOypr55u4AX9UOybB&\_nc\_ht=scontent-bom1-2.xx\&oh=00\_AfBixUdeavovhec0HE36zAcgIkW\_LopfXcPmgqUOEkSYFQ\&oe=64C5B73A)

[GBP Rate Card](https://scontent-bom1-1.xx.fbcdn.net/v/t39.8562-6/343731559\_767366834741749\_8464102507090895995\_n.csv?\_nc\_cat=106\&ccb=1-7&\_nc\_sid=ae5e01&\_nc\_ohc=9rvWnJg6FL0AX8E-ETD&\_nc\_ht=scontent-bom1-1.xx\&oh=00\_AfCaW3O-3vHSOkNPHsYMAqrEZxrQ1Rlyp7qiJ4WjN8HxrA\&oe=64C634EC)

[IDR Rate Card](https://scontent-bom1-2.xx.fbcdn.net/v/t39.8562-6/343421428\_261978626253428\_5697256897143398196\_n.csv?\_nc\_cat=100\&ccb=1-7&\_nc\_sid=ae5e01&\_nc\_ohc=7rhelaufKm4AX\_\_qm-0&\_nc\_ht=scontent-bom1-2.xx\&oh=00\_AfCmjVRJDJ7EePGmMZiMX--ARmqit7zg9IUfYvQwmLmZoQ\&oe=64C50353)

[INR Rate Card](https://scontent-bom1-2.xx.fbcdn.net/v/t39.8562-6/343732105\_148804091479211\_1063130843090288795\_n.csv?\_nc\_cat=109\&ccb=1-7&\_nc\_sid=ae5e01&\_nc\_ohc=AQwWFyks2lgAX-cEvSt&\_nc\_ht=scontent-bom1-2.xx\&oh=00\_AfD2ucYPGtRawKYi-sSvXO\_35917SMpUGYynf7Novha-nQ\&oe=64C5C376)

## Know More about some key concepts

### **Conversation Categories**

Conversations are categorized into the following types:

1. **Marketing**: Includes promotional messages, offers, informational updates, or invitations for customer responses.
2. **Utility**: Facilitates specific, agreed-upon requests or transactions, or provides updates on ongoing transactions.
3. **Authentication**: Enables user authentication with one-time passcodes for account verification, recovery, etc.
4. **Service**: Helps resolve customer inquiries and support-related matters.

{% hint style="info" %}
Please Note: Marketing, utility, and authentication conversations require template messages, while service messages use free-form messages.
{% endhint %}

### **Opening Conversations**

Conversations are opened when you send a template message or free-form message based on the following conditions:

1. **Marketing, Utility, and Authentication Conversations**: When you send an approved template message and no existing open conversation of that category exists with the customer.
2. **Service Conversations**: When you send a free-form message within the customer service window, and no open conversation with any category exists with the customer.

### **Customer Service Windows**

When a customer messages you, a 24-hour customer service window starts. Within this window, you can send free-form and template messages. Outside this window, you can only send template messages.

### **Conversation Duration**

Marketing, utility, authentication, and service conversations last 24 hours unless replaced by a newly opened free-entry point conversation. Free-entry point conversations last 72 hours.

### **Multiple Conversations**

Multiple open conversations are possible with a customer in the following situations:

1. Sending different template messages of various categories within 24 hours.
2. Sending a template message within 24 hours when an open service conversation exists.

### **Free Tier Conversations**

Each WhatsApp Business Account gets 1,000 free service conversations each month across all business phone numbers. Marketing, utility, and authentication conversations are not part of the free tier.

### **Free Entry Point Conversations**

A free entry point conversation opens when a customer messages via a Click to WhatsApp Ad or Facebook Page Call-to-Action button, and you respond within 24 hours. It lasts 72 hours and automatically closes all other open conversations with the customer.

For further assistance or clarifications, feel free to reach out to our support team.
