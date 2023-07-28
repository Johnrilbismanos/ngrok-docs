<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"add":{"Content-Security-Policy":"script-src 'self'","X-Frame-Options":"DENY"}}' \
https://api.ngrok.com/edges/https/edghts_2TDPx8oosFWI7cz6o9dNyxa99uu/routes/edghtsrt_2TDPxDY97SsfuG4cjRjrpdC3UHd/response_headers
