<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "reserved_domains": [
    {
      "id": "rd_2TDPvrNdT94AIswhblRe3QvZng5",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2TDPvrNdT94AIswhblRe3QvZng5",
      "created_at": "2023-07-28T20:08:31Z",
      "domain": "myapp.mydomain.com",
      "region": "us",
      "cname_target": "g5ugxhpf.cname.us.ngrok.io",
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "certificate": {
        "id": "cert_2TDPvqOaiO1UQ1RyX5krmTfDnsd",
        "uri": "https://api.ngrok.com/tls_certificates/cert_2TDPvqOaiO1UQ1RyX5krmTfDnsd"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "acme_challenge_cname_target": null
    },
    {
      "id": "rd_2TDPvqUSK1WH7aDmEND577N08F3",
      "uri": "https://api.ngrok.com/reserved_domains/rd_2TDPvqUSK1WH7aDmEND577N08F3",
      "created_at": "2023-07-28T20:08:31Z",
      "description": "Device 0001 Dashboard",
      "metadata": "{\"service\": \"dashboard\"}",
      "domain": "manage-0001.app.example.com",
      "region": "us",
      "cname_target": "qabrdjqf.cname.us.ngrok.io",
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "renews_at": null,
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "started_at": "2023-07-28T20:08:31Z",
          "retries_at": null
        }
      },
      "acme_challenge_cname_target": null
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains",
  "next_page_uri": null
}