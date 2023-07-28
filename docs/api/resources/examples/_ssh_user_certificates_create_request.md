<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X POST \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"ssh_certificate_authority_id":"sshca_2TDPwkqav1M4FAxA1x0oaWOi9xM","public_key":"ecdsa-sha2-nistp256 AAAAE2VjZHNhLXNoYTItbmlzdHAyNTYAAAAIbmlzdHAyNTYAAABBBK58lFzmWlDimDtBz78wVT4oauA8PjY0CiXTCEIsBNC6UwOJvZ0jdSaYNhDaa7dRV84DfBb/gKzqlXC7cVMZjl0= alan@work-laptop","principals":["ec2-user","root"],"valid_until":"2023-10-26T20:08:38Z","description":"temporary access to staging machine"}' \
https://api.ngrok.com/ssh_user_certificates
