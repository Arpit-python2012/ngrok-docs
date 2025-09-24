<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-09-24T10:11:10Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.ka7vtokcrmag2uhd.local-ngrok-cname.com",
      "created_at": "2025-09-24T10:11:09Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_338phEwYTXgxfN1IlaeSq8muWj0",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_338phEwYTXgxfN1IlaeSq8muWj0"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_338phAQKcJLbtFHRrl4cEjehE6S",
        "uri": "https://api.ngrok.com/tls_certificates/cert_338phAQKcJLbtFHRrl4cEjehE6S"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.ka7vtokcrmag2uhd.local-ngrok-cname.com",
      "created_at": "2025-09-24T10:11:09Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_338phB3q9WX6LEDv0yzDEqUzxbD",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_338phB3q9WX6LEDv0yzDEqUzxbD"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-09-24T10:10:39Z",
      "description": "Your dev domain",
      "domain": "supergloriously-unsophistic-scottie.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_338pdOeW9fdM7SZNlqfAgvNdiLb",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_338pdOeW9fdM7SZNlqfAgvNdiLb"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
