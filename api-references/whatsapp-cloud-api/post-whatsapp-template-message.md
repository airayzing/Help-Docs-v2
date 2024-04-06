---
description: API to send the WhatsApp template message
---

# POST WhatsApp Template Message

#### Parameter Description

1. `userName`: refers to the name of the user we intend to send the message
2. `wa_id`: refers to the WhatsApp number of the user we intend to send the message **NOTE**: The number must contain the country code without the plus sign
3. `templateId`: refers to the ID of the template **NOTE:** Template must be approved before using this API
4. `params`: is used for the variables used in the template, it is an empty array in the case of a plain text template with no variables. In case of variables in the template, please refer to the JSON below

#### **API Endpoint**

```
https://api.v7.express-chat.com/whatsapp-automation/wa/send-template?apiKey=*API KEY*
```

#### Request Headers

| Header | Details |
| ------ | ------- |
| apiKey | API KEY |

#### Query Params

| Header | Details |
| ------ | ------- |
| apiKey | API KEY |

#### Body

```json
{
    "userName": "Divyansh Test",
    "wa_id": "9175080****",
    "templateId": "62b5c16bf*****cfa9a72335",
    "params": [
			{
				"type" : "header",
				 "parameters": [
                {
                            "type": "document",
                            "document": {
                            "link": "<https://www.africau.edu/images/default/sample.pdf>"
                            }
                }
            ]
			},
			{
                    "type": "body",
                    "parameters": [
                        {
                            "type": "text",
                            "text": "Abc"
                        },
                         {
                            "type": "text",
                            "text": "def"
                        },
                         {
                            "type": "text",
                            "text": "Monday"
                        }
                    ]
        }				
		 ]
}
```

#### Examples

**Request**

{% code overflow="wrap" %}
```json
curl --location --request POST '<https://api.v7.express-chat.com/whatsapp-automation/wa/send-template?apiKey=> *Shared Separately*' \\
--header 'apiKey: *API KEY*' \\
--header 'Content-Type: application/json' \\
--data-raw '{
    "userName": "Test",
    "wa_id": "91885917****",
    "templateId": "63dba1617****52face07078",
    "params": [
        {
            "type": "header",
            "parameters": [
                {
                            "type": "document",
                            "document": {
                            "link": "<https://www.africau.edu/images/default/sample.pdf>"
                            }
                }
            ]
        },
        {
                    "type": "body",
                    "parameters": [
                        {
                            "type": "text",
                            "text": "Abc"
                        },
                         {
                            "type": "text",
                            "text": "def"
                        },
                         {
                            "type": "text",
                            "text": "Monday"
                        }
                    ]
        }

    ]
}'
```
{% endcode %}

**Response**

Headers

| Header                           | Details                             |
| -------------------------------- | ----------------------------------- |
| X-Powered-By                     | Express                             |
| Vary                             | Origin                              |
| Access-Control-Allow-Credentials | true                                |
| \_user                           | 61c1c2058e0\*\*\*\*e9bb420f8        |
| \_bot                            | 62e77a807f1\*\*\*\*ecce980f0        |
| whatsAppId                       | \*\*\*\*bsIWcYgazd5ZDAK             |
| Content-Type                     | application/json; charset=utf-8     |
| Content-Length                   | 507                                 |
| ETag                             | W/"1fb-urlVjgGZAUBRNyxQDAOnZ3ONF1I" |
| Date                             | Wed, 03 Aug 2022 11:16:13 GMT       |
| Connection                       | keep-alive                          |
| Keep-Alive                       | timeout=5                           |
