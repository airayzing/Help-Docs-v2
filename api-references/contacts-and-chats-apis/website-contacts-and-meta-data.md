---
description: This section contains the Leads and Chat API references
---

# Website Contacts & Meta Data

## Get the essentials first!

To use the BotBuddy AI APIs, You need to insure that you have following details with you.

A. **UUID -** You can get the UUID from the local web session storage as show in the image below:

<figure><img src="https://github.com/airayzing/helpdocs/blob/develop/.gitbook/assets/image%20(44).png" alt=""><figcaption><p>How to get the UUDI</p></figcaption></figure>

B. **Bot ID & User ID:** One can get the Bot ID and User ID from your Bot Script or Bot page URL. Below is the sample Example.

For Chatbot page URL

{% code overflow="wrap" lineNumbers="true" %}
```markup
// Chatbot Page URL Structure

https://page.botbuddyai.com/BotId/CustomerId

// The first value after .com is the BotId and second value is the CustomerId.
```
{% endcode %}

For Chatbot Script

<pre class="language-markup" data-overflow="wrap" data-line-numbers><code class="lang-markup"><strong>// Chatbot Script Structure
</strong>
&#x3C;script id="BotBuddy AI-messenger-widget" src="https://cdn.botbuddyai.com/BotBuddy AI.js" defer>BotId,CustomerId&#x3C;/script>

// The first value after defer> is the BotId &#x26; second value is the CustomerId.
</code></pre>

C. **Auth Token:** We haven't automated everything yet. Please contact our support team to get the same.

Now you are ready to run the POC

## API References

Please use the below APIs in order to play with your leads and chat data.

### Create a lead in the BotBuddy AI

As soon as any user opens up the Bot, It creates one UUId; pass the same along with the other required details to create and update the lead's details.

## API to update a chat/lead data

<mark style="color:orange;">`PUT`</mark> `https://api.v7.express-chat.ai/inbox/direct/lead`

As soon as any user opens up the Bot, It creates one UUId; pass the same along with the other required details to create and update the lead's details.

#### Headers

| Name                                         | Type   | Description |
| -------------------------------------------- | ------ | ----------- |
| x-bp-token<mark style="color:red;">\*</mark> | String | API Token   |

#### Request Body

| Name                                         | Type                                        | Description                                                                                                   |
| -------------------------------------------- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------- |
| uuid<mark style="color:red;">\*</mark>       | String                                      | Unique ID of a chat user                                                                                      |
| botId<mark style="color:red;">\*</mark>      | String                                      | Unique ID of the bot                                                                                          |
| customerId<mark style="color:red;">\*</mark> | String                                      | Unique ID of the customer account                                                                             |
| agentId                                      | Boolean                                     | Unique ID of the agent assigned                                                                               |
| status                                       | String                                      | Valid status for the chat. Available values: 'OPEN', 'INPROGRESS', 'REVIEW', 'ONHOLD', 'DEPENDANCY', 'CLOSED' |
| picture                                      | String                                      | A valid image HTTP URL                                                                                        |
| name                                         | String                                      | Name of the lead                                                                                              |
| email                                        | String                                      | Email of the lead                                                                                             |
| phone                                        | String                                      | Phone number of the lead                                                                                      |
| dialCode                                     | String                                      | Dial Code including "+" sign                                                                                  |
| notes                                        | Array<{title: string, description: string}> | Additional notes for the chat                                                                                 |
| tags                                         | Array\<String>                              | Additional tags for the chat                                                                                  |
| attributes                                   | Array<{key: string, value: string}>         | Custom attributes for the chat                                                                                |

{% tabs %}
{% tab title="200: OK API successfully processed" %}
```json
{
    "success": true,
    "message": "ok",
    "code": 200
}
```
{% endtab %}

{% tab title="400: Bad Request Bad request/parameters" %}
```javascript
{
    // Response
}
```
{% endtab %}

{% tab title="401: Unauthorized Unauthorized request" %}
```javascript
{
    // Response
}
```
{% endtab %}
{% endtabs %}

### Get leads listing and Its meta data

To get the listing of the leads and its meta data, Hit the below API with mandatory details.

## API to get listing of chats/leads

<mark style="color:blue;">`GET`</mark> `https://api.v7.express-chat.ai/inbox/direct/chats`

To get the listing of the leads and its meta data, Hit the below API with mandatory details.

#### Query Parameters

| Name                                         | Type   | Description                                                                |
| -------------------------------------------- | ------ | -------------------------------------------------------------------------- |
| botId<mark style="color:red;">\*</mark>      | String | Unique ID of the bot                                                       |
| customerId<mark style="color:red;">\*</mark> | String | Unique ID of the customer account                                          |
| page<mark style="color:red;">\*</mark>       | String | Page number                                                                |
| type<mark style="color:red;">\*</mark>       | String | <p>"lead" to fetch only leads</p><p>"non-lead" to fetch non lead chats</p> |

#### Headers

| Name                                          | Type   | Description |
| --------------------------------------------- | ------ | ----------- |
| x-bot-token<mark style="color:red;">\*</mark> | String | API Token   |

{% tabs %}
{% tab title="200: OK API successfully processed" %}
```json
{
    "success": true,
    "message": "ok",
    "data": [
        {
            "_id": "63d9ffa77a8d152facbe2f2f",
            "uuid": "7e88d192-9b20-4035-9b68-d4ac3d58a34f",
            "createdAt": "2023-02-01T05:59:03.533Z",
            "isOnline": false,
            "lastMessage": {
                "at": "2023-02-01T06:00:20.000Z",
                "by": "bot",
                "text": "Welcome to BotBuddy AI. I am here to help you."
            },
            "lastSeenAt": "2023-02-01T06:00:21.000Z",
            "profile": {
                "notes": [
                    {
                        "title": "Sample title",
                        "description": "Sample description",
                        "_id": "63db5c4abcbc3be2e95b20ae"
                    }
                ],
                "userDetails": {
                    "name": "Sample name",
                    "picture": "my-picture",
                    "contact": {
                        "email": "Sample email",
                        "phone": {
                            "number": "Sample number",
                            "prefix": "91"
                        }
                    },
                    "city": "Sample city",
                    "country": "Sample country",
                    "gender": "MALE",
                    "tags": [
                        "Sample tag"
                    ],
                    "attributes": [
                        {
                            "key": "ID",
                            "value": "BP001"
                        }
                    ]
                }
            },
            "status": "INPROGRESS",
            "updatedAt": "2023-02-02T06:46:34.119Z",
            "websiteVisits": 1,
            "_agentAssigned": "631aa793bcfa100487d13d0d"
        }
    ],
    "code": 200
}
```
{% endtab %}

{% tab title="400: Bad Request Bad Requests/Parameters" %}
```javascript
{
    // Response
}
```
{% endtab %}

{% tab title="401: Unauthorized Unauthorized request" %}
```javascript
{
    // Response
}
```
{% endtab %}
{% endtabs %}

### :question: Got any questions?

If you have any questions, you can look into our repository of FAQs, most likely, you will find your answer here, If not, write us at support@botbuddyai.com
