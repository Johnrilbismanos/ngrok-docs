<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2TDPxYyFrYs9FuMSFNbVrUHLb3y"]}' \
https://api.ngrok.com/edges/tcp/edgtcp_2TDPxUSx7vWtB0aNX5ObKqunZbr/ip_restriction
