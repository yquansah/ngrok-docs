<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"reserved_domains": [
		{
			"id": "rd_2arwYiUeCgS3OgwMEccNvXZAP8c",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2arwYiUeCgS3OgwMEccNvXZAP8c",
			"created_at": "2024-01-12T20:07:34Z",
			"domain": "myapp.mydomain.com",
			"region": "",
			"cname_target": "2udamkamcl8pjmrff.3z4fzoxgapltuwtta.local-ngrok-cname.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"certificate": {
				"id": "cert_2arwYf0cqnJGX9y1yw4Ky2ZQRAe",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2arwYf0cqnJGX9y1yw4Ky2ZQRAe"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"acme_challenge_cname_target": null
		},
		{
			"id": "rd_2arwYf05elTYpTarRvGqxm0QUF6",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2arwYf05elTYpTarRvGqxm0QUF6",
			"created_at": "2024-01-12T20:07:34Z",
			"description": "Device 0001 Dashboard",
			"metadata": "{\"service\": \"dashboard\"}",
			"domain": "manage-0001.app.example.com",
			"region": "",
			"cname_target": "4mgkuazanf1yq46m3.3z4fzoxgapltuwtta.local-ngrok-cname.com",
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"renews_at": null,
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"started_at": "2024-01-12T20:07:34Z",
					"retries_at": null
				}
			},
			"acme_challenge_cname_target": null
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains",
	"next_page_uri": null
}
```
