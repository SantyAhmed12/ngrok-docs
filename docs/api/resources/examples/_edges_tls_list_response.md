<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-07-20T10:08:12Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_308PBhY7WIUQ2uA0La8TmXSoHH3",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_308PBhY7WIUQ2uA0La8TmXSoHH3"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_308PAM1Mp2l9yJGf2Quhl6GdQZB",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_308PAM1Mp2l9yJGf2Quhl6GdQZB"
        },
        "enabled": true
      },
      "created_at": "2025-07-20T10:08:01Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_308PAM8QHgTHvLr1j3PwrILCNKU",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_308PAM8QHgTHvLr1j3PwrILCNKU"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
