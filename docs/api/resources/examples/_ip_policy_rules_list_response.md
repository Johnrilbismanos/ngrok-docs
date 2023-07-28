<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "ip_policy_rules": [
    {
      "id": "ipr_2TDPwgiDMeAMfyjDQGk6IgpWZ3B",
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2TDPwgiDMeAMfyjDQGk6IgpWZ3B",
      "created_at": "2023-07-28T20:08:37Z",
      "description": "sf office",
      "cidr": "132.2.19.0/24",
      "ip_policy": {
        "id": "ipp_2TDPwdnOj0kejreuV1XuUBpJP87",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2TDPwdnOj0kejreuV1XuUBpJP87"
      },
      "action": "allow"
    },
    {
      "id": "ipr_2TDPwfMeoy49dshTAuiYJTsGjih",
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2TDPwfMeoy49dshTAuiYJTsGjih",
      "created_at": "2023-07-28T20:08:37Z",
      "description": "nyc office",
      "cidr": "212.3.14.0/24",
      "ip_policy": {
        "id": "ipp_2TDPwdnOj0kejreuV1XuUBpJP87",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2TDPwdnOj0kejreuV1XuUBpJP87"
      },
      "action": "allow"
    },
    {
      "id": "ipr_2TDPwexVVzKfXhd9P4yFhGbYLOq",
      "uri": "https://api.ngrok.com/ip_policy_rules/ipr_2TDPwexVVzKfXhd9P4yFhGbYLOq",
      "created_at": "2023-07-28T20:08:37Z",
      "description": "alan laptop",
      "cidr": "2.2.2.2/32",
      "ip_policy": {
        "id": "ipp_2TDPwdnOj0kejreuV1XuUBpJP87",
        "uri": "https://api.ngrok.com/ip_policies/ipp_2TDPwdnOj0kejreuV1XuUBpJP87"
      },
      "action": "allow"
    }
  ],
  "uri": "https://api.ngrok.com/ip_policy_rules",
  "next_page_uri": null
}