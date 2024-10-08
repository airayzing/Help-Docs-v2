---
description: This page contains the API documentation for the adding new WhatsApp contacts.
---

# Add WhatsApp Contact

### Introduction

<<<<<<< HEAD
The **Inbox User Import API** allows you to import WhatsApp contacts into the tropitech platform. You can use this API to create or update WhatsApp contacts with various attributes and contact information.
=======
<<<<<<< HEAD
The **Inbox User Import API** allows you to import WhatsApp contacts into the m1bot platform. You can use this API to create or update WhatsApp contacts with various attributes and contact information.
=======
The **Inbox User Import API** allows you to import WhatsApp contacts into the EkoChat Connect platform. You can use this API to create or update WhatsApp contacts with various attributes and contact information.
>>>>>>> a4cbe70f0174e74b40121f7a3e60e7bdc5c6e923
>>>>>>> e3924ba1285985f801a086ecf58553cde6ad400a

#### Base URL

```bash
https://api.v7.express-chat.com/inbox/users/import
```

### Authentication

To use this API, you need to include the following authentication header:

* **Authorization**: Bearer Token
  * Example: `Bearer eyJhbGciO*****InR5cCI6IkpXVCJ9...`

### Request Headers

The following request headers are required:

* **Content-Type**: application/json

### Request Data

The request should include a JSON array of user profiles to be imported. Each user profile should have the following structure:

```json
jsonCopy code[
  {
    "profile": {
      "userDetails": {
        "userProvidedName": "User Name",
        "contact": {
          "email": "user@email.com",
          "phone": {
            "number": "1234567890",
            "prefix": "91"
          }
        },
        "tags": [],
        "attributes": []
      }
    }
  }
]
```

#### Example CURL Request

```bash
curl 'https://api.v7.express-chat.com/inbox/users/import' \
  -H 'Authorization: Bearer eyJhbGciOiJSUzUxMiIsInR5cCI6IkpXVCJ9...' \
  -H 'Content-Type: application/json' \
  -H 'Accept: */*' \
<<<<<<< HEAD
  -H 'Origin: https://tropitech.mark1.ai/' \
  -H 'Referer: https://tropitech.mark1.ai//' \
=======
<<<<<<< HEAD
  -H 'Origin: https://m1bot.mark1.ai/' \
  -H 'Referer: https://m1bot.mark1.ai//' \
=======
  -H 'Origin: https://app.https://help.eko.chat' \
  -H 'Referer: https://app.https://help.eko.chat/' \
>>>>>>> a4cbe70f0174e74b40121f7a3e60e7bdc5c6e923
>>>>>>> e3924ba1285985f801a086ecf58553cde6ad400a
  -H 'Sec-Fetch-Dest: empty' \
  -H 'Sec-Fetch-Mode: cors' \
  -H 'Sec-Fetch-Site: same-site' \
  -H 'User-Agent: Your User-Agent' \
  --data-raw '[{"profile":{"userDetails":{"userProvidedName":"User Name","contact":{"email":"user@email.com","phone":{"number":"1234567890","prefix":"91"}},"tags":[],"attributes":[]}}}]' \
  --compressed
```

### Response

The API will respond with a status code and a JSON response body. The response body will contain information about the import operation.

* **Status Codes**:
  * `200 OK`: The import operation was successful.

#### Example Response

```json
jsonCopy code{
  "status": "success",
  "message": "User profiles imported successfully."
}
```

### Conclusion

<<<<<<< HEAD
The Inbox User Import API allows you to easily import user profiles into the tropitech platform. Make sure to follow the authentication and data format guidelines for successful imports.

### :question: Got any questions?

If you have any questions, you can look into our repository of FAQs, most likely, you will find your answer here, If not, write us at production@tropitech.co.za
=======
<<<<<<< HEAD
The Inbox User Import API allows you to easily import user profiles into the m1bot platform. Make sure to follow the authentication and data format guidelines for successful imports.

### :question: Got any questions?

If you have any questions, you can look into our repository of FAQs, most likely, you will find your answer here, If not, write us at production@m1bot.co.za
=======
The Inbox User Import API allows you to easily import user profiles into the EkoChat Connect platform. Make sure to follow the authentication and data format guidelines for successful imports.

### :question: Got any questions?

If you have any questions, you can look into our repository of FAQs, most likely, you will find your answer here, If not, write us at enquiries@https://help.eko.chat
>>>>>>> a4cbe70f0174e74b40121f7a3e60e7bdc5c6e923
>>>>>>> e3924ba1285985f801a086ecf58553cde6ad400a
