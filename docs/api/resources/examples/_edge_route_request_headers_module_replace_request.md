<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"add":{"x-frontend":"ngrok"},"remove":["cache-control"]}' \
https://api.ngrok.com/edges/https/edghts_2TDPxALI1O6A2S8kObh8iYGCuZf/routes/edghtsrt_2TDPxBQoQY38xTvERa7Qc54sUxq/request_headers
