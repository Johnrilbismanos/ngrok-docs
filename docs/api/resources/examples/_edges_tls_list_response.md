<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "tls_edges": [
    {
      "id": "edgtls_2TDPxREtxfP2hzBgVo2SBR6JkFX",
      "description": "acme tls edge",
      "metadata": "{\"environment\": \"staging\"}",
      "created_at": "2023-07-28T20:08:43Z",
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2TDPxREtxfP2hzBgVo2SBR6JkFX",
      "hostports": [
        "example.com:443"
      ],
      "backend": null,
      "ip_restriction": null,
      "mutual_tls": null,
      "tls_termination": null
    },
    {
      "id": "edgtls_2TDPwU2ZgWSPARuElPANJx0mQzX",
      "description": "acme tls edge",
      "created_at": "2023-07-28T20:08:36Z",
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2TDPwU2ZgWSPARuElPANJx0mQzX",
      "hostports": [
        "endpoint-example.com:443"
      ],
      "backend": {
        "enabled": true,
        "backend": {
          "id": "bkdhr_2TDPwSdJokBt2wRhGNZlPKsIiCm",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2TDPwSdJokBt2wRhGNZlPKsIiCm"
        }
      },
      "ip_restriction": null,
      "mutual_tls": null,
      "tls_termination": null
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls",
  "next_page_uri": null
}