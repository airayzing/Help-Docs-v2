---
description: >-
  This page contains the API documentation for the getting all groups/segments
  in customers account.
---

# Getting Groups/Segments

### Get Segments/Groups

This API endpoint allows you to retrieve segments for your EleAPI application.

**Endpoint URL:** `https://api.v7.express-chat.com/inbox/segments`

**HTTP Method:** GET

#### Request Headers

* `Authorization`: A bearer token is required for authentication. Replace `[MASKED_TOKEN]` with your valid API token. This token is used to authenticate and authorize the request.

#### Sample Request

```bash
curl 'https://api.v7.express-chat.com/inbox/segments' \
  -H 'Authorization: Bearer [MASKED_TOKEN]' \
  -H 'Content-Type: application/json' \
  --compressed
```

Replace `[MASKED_TOKEN]` in the request with your actual API token.

#### Response

The API will respond with a JSON object containing the segments available in your EleAPI application. The response format may vary depending on the segments you have configured.

Please replace `[MASKED_TOKEN]` in the request with your actual API token for actual usage.

### :question: Got any questions?

If you have any questions, you can look into our repository of FAQs, most likely, you will find your answer here, If not, write us at enquiries@EleApi.io
