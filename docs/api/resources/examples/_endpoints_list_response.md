<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-20T10:08:06Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_308PALfwUcKOYtemskBUqd5HRqV",
        "uri": "https://api.ngrok.com/reserved_domains/rd_308PALfwUcKOYtemskBUqd5HRqV"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_308PAzblwpcyOrtZmS1GKPjcowm",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-07-20T10:08:06Z",
      "uri": "https://api.ngrok.com/endpoints/ep_308PAzblwpcyOrtZmS1GKPjcowm",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-20T10:08:04Z",
      "hostport": "37b1bbfbd699.ngrok.paid:443",
      "id": "ep_308PAeE0HViWJtxCEFgwOconfGb",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_308P4BeRH6uG9CO2nngHqS576NU",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://37b1bbfbd699.ngrok.paid",
      "tunnel": {
        "id": "tn_308PAeE0HViWJtxCEFgwOconfGb",
        "uri": "https://api.ngrok.com/tunnels/tn_308PAeE0HViWJtxCEFgwOconfGb"
      },
      "tunnel_session": {
        "id": "ts_308PAg6PCCa8TtrHtJwKaXffvDh",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_308PAg6PCCa8TtrHtJwKaXffvDh"
      },
      "type": "ephemeral",
      "updated_at": "2025-07-20T10:08:04Z",
      "upstream_url": "http://localhost:80",
      "url": "https://37b1bbfbd699.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-07-20T10:08:01Z",
      "domain": {
        "id": "rd_308PALfwUcKOYtemskBUqd5HRqV",
        "uri": "https://api.ngrok.com/reserved_domains/rd_308PALfwUcKOYtemskBUqd5HRqV"
      },
      "edge": {
        "id": "edgtls_308PAM8QHgTHvLr1j3PwrILCNKU",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_308PAM8QHgTHvLr1j3PwrILCNKU"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_308PAIkY5wRw1pHlFORCfAyzj8i",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-07-20T10:08:01Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
