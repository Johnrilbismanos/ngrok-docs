<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "ingresses": [
    {
      "id": "agin_2TDPwnlo4b6JJ4nDlNpzrb3k364",
      "uri": "https://api.ngrok.com/agent_ingresses/agin_2TDPwnlo4b6JJ4nDlNpzrb3k364",
      "description": "acme devices",
      "domain": "connect.acme.com",
      "ns_targets": [
        "1.kube-dns.kube-system.svc.cluster.local.",
        "2.kube-dns.kube-system.svc.cluster.local.",
        "3.kube-dns.kube-system.svc.cluster.local.",
        "4.kube-dns.kube-system.svc.cluster.local."
      ],
      "region_domains": [
        "tunnel.us.connect.acme.com"
      ],
      "created_at": "2023-07-28T20:08:38Z"
    }
  ],
  "uri": "https://api.ngrok.com/agent_ingresses",
  "next_page_uri": null
}