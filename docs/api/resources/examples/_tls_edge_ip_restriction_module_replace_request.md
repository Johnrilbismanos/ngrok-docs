<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2TDPxXuYnQvsphGjfpRF8PVKQWL","ipp_2TDPxWd6XF9fTjHNKsxL3uFXkYd"]}' \
https://api.ngrok.com/edges/tls/edgtls_2TDPxUqCc48fIkEFltMRlkNjq3x/ip_restriction
