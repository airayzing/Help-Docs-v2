---
description: API to get list of all the templates with their current status
---

# GET Templates List

#### API End Point

{% code overflow="wrap" %}
```
https://api.v7.express-chat.com/whatsapp-automation/wa/templates?apiKey=*API KEY*
```
{% endcode %}

#### Request Headers

| Header | Details |
| ------ | ------- |
| apiKey | API KEY |

#### Query Params

| Header | Details |
| ------ | ------- |
| apiKey | API KEY |

#### Examples

**Request**

{% code overflow="wrap" %}
```json
curl --location --request GET 'https://api.v7.eexpress-chat.com/whatsapp-automation/wa/templates?apiKey=*API KEY*' \\
--header 'apiKey: *API KEY*'
```
{% endcode %}

**Response**

Body

```json
{
    "success": true,
    "data": [
        {
            "_id": "62b5c16bf1d8decfa9a72335",
            "_user": "61c1c2058e0c5a1e9bb420f8",
            "configuration": {
                "name": "uniform_update",
                "category": "APPOINTMENT_UPDATE",
                "language": "en",
                "header": "text",
                "textHeader": "Hey how are you",
                "media": "",
                "mediaHeader": {
                    "image": "",
                    "video": ""
                },
                "body": "Hi I'm Joey\\nHow you doiiin",
                "footer": "thank you",
                "button": "",
                "ctaButtonType": [],
                "ctaButton": [],
                "quickReply": [
                    {
                        "id": "",
                        "text": ""
                    }
                ]
            },
            "whatsAppId": "Xk4qPq8u0HJbsIWcYgazd5ZDAK",
            "status": "APPROVED",
            "namespace": "b676ea4e_f9ce_44c8_b187_b98b40f85f9f",
            "createdAt": "2022-06-24T13:51:39.610Z",
            "updatedAt": "2022-06-24T13:52:19.838Z",
            "__v": 0
        },
       
    ]
}
```

Header

| Header                           | Details                              |
| -------------------------------- | ------------------------------------ |
| X-Powered-By                     | Express                              |
| Vary                             | Origin                               |
| Access-Control-Allow-Credentials | true                                 |
| \_user                           | 61c1c2058e0c5a1e9bb420f8             |
| Content-Type                     | application/json; charset=utf-8      |
| Content-Length                   | 7146                                 |
| ETag                             | W/"1bea-RhtE+UK94qGji1CaCyMvUWBM3E8" |
| Date                             | Wed, 03 Aug 2022 11:16:13 GMT        |
| Connection                       | keep-alive                           |
| Keep-Alive                       | timeout=5                            |
