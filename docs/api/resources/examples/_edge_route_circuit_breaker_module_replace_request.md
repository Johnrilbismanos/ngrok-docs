<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"tripped_duration":120,"rolling_window":300,"num_buckets":5,"volume_threshold":20,"error_threshold_percentage":0.2}' \
https://api.ngrok.com/edges/https/edghts_2TDPx3ZTg535NnY67xOHJ1tCcRV/routes/edghtsrt_2TDPx3N84JrVBruGUPVICZbIiWM/circuit_breaker
