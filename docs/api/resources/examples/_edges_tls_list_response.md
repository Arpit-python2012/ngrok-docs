<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-09-24T10:11:36Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_338pkZxdLNRRmbD3aNij0glZQYK",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_338pkZxdLNRRmbD3aNij0glZQYK"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_338pj6MoEWVDiSFCQna0ypOD6ww",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_338pj6MoEWVDiSFCQna0ypOD6ww"
        },
        "enabled": true
      },
      "created_at": "2025-09-24T10:11:25Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_338pjBob8Tu9R2V9WyDveVjwVFT",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_338pjBob8Tu9R2V9WyDveVjwVFT"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
