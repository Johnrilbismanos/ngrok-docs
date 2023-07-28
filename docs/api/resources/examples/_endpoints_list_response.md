<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "endpoints": [
    {
      "id": "ep_2TDPwYYFD9QsxPRVThOLacbR2bT",
      "created_at": "2023-07-28T20:08:36Z",
      "updated_at": "2023-07-28T20:08:36Z",
      "public_url": "tls://endpoint-example.com",
      "proto": "tls",
      "hostport": "endpoint-example.com:443",
      "type": "edge",
      "domain": {
        "id": "rd_2TDPwTnZ9Y7F7HQZ12ABIfZR0KM",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2TDPwTnZ9Y7F7HQZ12ABIfZR0KM"
      },
      "edge": {
        "id": "edgtls_2TDPwU2ZgWSPARuElPANJx0mQzX",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2TDPwU2ZgWSPARuElPANJx0mQzX"
      }
    },
    {
      "id": "ep_2TDPwUUaxxEwWgYrD9Md0NRi1g8",
      "created_at": "2023-07-28T20:08:36Z",
      "updated_at": "2023-07-28T20:08:36Z",
      "public_url": "https://624257ba1d75.ngrok.paid",
      "proto": "https",
      "hostport": "624257ba1d75.ngrok.paid:443",
      "type": "ephemeral",
      "tunnel": {
        "id": "tn_2TDPwUUaxxEwWgYrD9Md0NRi1g8",
        "uri": "https://api.ngrok.com/tunnels/tn_2TDPwUUaxxEwWgYrD9Md0NRi1g8"
      }
    }
  ],
  "uri": "https://api.ngrok.com/endpoints",
  "next_page_uri": null
}