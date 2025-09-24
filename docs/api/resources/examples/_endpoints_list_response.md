<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-24T10:11:30Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_338pj8li7XKlDtJFRT7g0Xrm86G",
        "uri": "https://api.ngrok.com/reserved_domains/rd_338pj8li7XKlDtJFRT7g0Xrm86G"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_338pjjUeHyv7Ggx85ktKvTFBidy",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-09-24T10:11:30Z",
      "uri": "https://api.ngrok.com/endpoints/ep_338pjjUeHyv7Ggx85ktKvTFBidy",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-24T10:11:28Z",
      "hostport": "f90bba92a23b.ngrok.paid:443",
      "id": "ep_338pjZXEluqGfQ5353JKnbtV7BO",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_338pd0pHJD7KRByhP6zq4oM4Z4e",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://f90bba92a23b.ngrok.paid",
      "tunnel": {
        "id": "tn_338pjZXEluqGfQ5353JKnbtV7BO",
        "uri": "https://api.ngrok.com/tunnels/tn_338pjZXEluqGfQ5353JKnbtV7BO"
      },
      "tunnel_session": {
        "id": "ts_338pjWyflaY2vAi5MfFkqfufTuY",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_338pjWyflaY2vAi5MfFkqfufTuY"
      },
      "type": "ephemeral",
      "updated_at": "2025-09-24T10:11:28Z",
      "upstream_url": "http://localhost:80",
      "url": "https://f90bba92a23b.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-24T10:11:25Z",
      "domain": {
        "id": "rd_338pj8li7XKlDtJFRT7g0Xrm86G",
        "uri": "https://api.ngrok.com/reserved_domains/rd_338pj8li7XKlDtJFRT7g0Xrm86G"
      },
      "edge": {
        "id": "edgtls_338pjBob8Tu9R2V9WyDveVjwVFT",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_338pjBob8Tu9R2V9WyDveVjwVFT"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_338pj5MUfhufK23PwEH4jDKr5Zb",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-09-24T10:11:25Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
