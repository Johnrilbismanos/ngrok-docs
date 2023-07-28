<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2TDPx2OA4pDbCugvD9FY9EHBMUJ","ipp_2TDPx0cdVUloRE0pGv6DEFKx8WZ"]}' \
https://api.ngrok.com/edges/https/edghts_2TDPwxZ4o9LQJqM75dBv44BimxP/routes/edghtsrt_2TDPx2lr4TMDUMrZeTpyCduzAGK/ip_restriction
