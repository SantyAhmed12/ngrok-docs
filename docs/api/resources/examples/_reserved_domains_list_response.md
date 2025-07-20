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
          "started_at": "2025-07-20T10:07:45Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.odhumd73mr6rbnna.local-ngrok-cname.com",
      "created_at": "2025-07-20T10:07:45Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_308P8MBQ7XxIzgqQtc23S3ml3P3",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_308P8MBQ7XxIzgqQtc23S3ml3P3"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_308P8Gh5U0pi51SABr4g91plhWB",
        "uri": "https://api.ngrok.com/tls_certificates/cert_308P8Gh5U0pi51SABr4g91plhWB"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.odhumd73mr6rbnna.local-ngrok-cname.com",
      "created_at": "2025-07-20T10:07:45Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_308P8IbXtBwVu19V0oplFuhAbAe",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_308P8IbXtBwVu19V0oplFuhAbAe"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-07-20T10:07:15Z",
      "description": "Your dev domain",
      "domain": "just-ready-cow.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_308P4YtnXlG9XHXHSYB65xGFRnq",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_308P4YtnXlG9XHXHSYB65xGFRnq"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
