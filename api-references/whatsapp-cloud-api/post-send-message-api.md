---
description: Use this API to send a WhatsApp message.
---

# POST Send Message API

#### API Endpoint

{% code overflow="wrap" %}
```
<https://api.v7.express-chat.com/whatsapp-automation/wa/send-message?apiKey=*API KEY*>

```
{% endcode %}

#### Request Headers

| Header       | Value            |
| ------------ | ---------------- |
| apiKey       | \*API KEY\*      |
| Content-Type | application/json |

{% tabs %}
{% tab title="Plain Text Messages" %}
**Request Body**

```json
{
    "userName": "Test",
    "wa_id": "910987654321",
    "type": "text",
    "message": {
        "text": "hi"
    }
}

```

**Parameters**

| Parameter      | Type   | Description                                                                                                                        |
| -------------- | ------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| userName       | string | The name of the user to whom the message is being sent.                                                                            |
| wa\_id         | string | The WhatsApp number of the user to whom the message is being sent. The number must contain the country code without the plus sign. |
| type           | string | The type of message being sent (e.g., text, image).                                                                                |
| message.text   | string | message that needs to sent                                                                                                         |
| message.label  | string | <p>The caption you want to send along with the image<br>(optional) Only if type is image</p>                                       |
| message.source | string | <p>The image link<br>(optional)<br>Only if type is image</p>                                                                       |

**Example**

{% code overflow="wrap" %}
```
curl --location 'https://api.v7.express-chat.com/whatsapp-automation/wa/send-message?apiKey=*API KEY*' \
--header 'apiKey: *API KEY*' \
--header 'Content-Type: application/json' \
--data '{
    "userName": "Test",
    "wa_id": "918859170007",
    "type": "text",
    "message": {
        "text": "hi"
    }
}'

```
{% endcode %}
{% endtab %}

{% tab title="Media Messages" %}
**Request Body**

```json
{
    "userName": "Test",
    "wa_id": "910987654321",
    "type": "image",
    "message": {
        "source": "https://imgv3.fotor.com/images/blog-cover-image/part-blurry-image.jpg",
        "label": "hey",
    }
}
```

**Parameters**

| Parameter      | Type   | Description                                                                                                                        |
| -------------- | ------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| userName       | string | The name of the user to whom the message is being sent.                                                                            |
| wa\_id         | string | The WhatsApp number of the user to whom the message is being sent. The number must contain the country code without the plus sign. |
| type           | string | The type of message being sent (e.g., text, image, document).                                                                      |
| message.source | string | The URL of the media being sent.                                                                                                   |
| message.label  | string | The text to attach to the media.                                                                                                   |
| message.type   | string | The type of media being sent (e.g., image, document).                                                                              |

**Example**

{% code overflow="wrap" %}
```
<<<<<<< HEAD
curl --location '<https://api.v7.m1bot.com/whatsapp-automation/wa/send-message?apiKey=*API KEY*>' \\\\
=======
curl --location '<https://api.v7.EkoChat Connect.com/whatsapp-automation/wa/send-message?apiKey=*API KEY*>' \\\\
>>>>>>> a4cbe70f0174e74b40121f7a3e60e7bdc5c6e923
--header 'apiKey: *API KEY*' \\\\
--header 'Content-Type: application/json' \\\\
--data '{
    "userName": "Test",
    "wa_id": "910987654321",
    "type": "image",
    "message": {
        "source": "<https://imgv3.fotor.com/images/blog-cover-image/part-blurry-image.jpg>",
        "label": "hey",
        "type": "image"
    }
}'

```
{% endcode %}
{% endtab %}
{% endtabs %}

### Error Codes

Refer to the [official documentation](https://developers.facebook.com/docs/whatsapp/on-premises/errors) for more information on error codes.
