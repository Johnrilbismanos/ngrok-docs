<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"description":"acme weighted","metadata":"{\"environment\": \"staging\"}","backends":{"bkdhr_2TDPwuGuHWhCurX1csQZjUDZ6GC":0,"bkdhr_2TDPwwwJxHUI4oRV9d56MVSedXl":1}}' \
https://api.ngrok.com/backends/weighted
