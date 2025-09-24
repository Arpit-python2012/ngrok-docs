<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-09-24T10:11:32Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_338pjxn0Y0wCJ5zQa87Ax3OXje5",
          "uri": "https://api.ngrok.com/event_destinations/ed_338pjxn0Y0wCJ5zQa87Ax3OXje5"
        }
      ],
      "id": "esb_338pk1xjwWAje4ZvSKRthVzymTb",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_338pk1xjwWAje4ZvSKRthVzymTb/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_338pk1xjwWAje4ZvSKRthVzymTb"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
```
