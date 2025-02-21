<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2tLYyQEl9hamPpqAjiwLDpwn0x1",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2tLYyQEl9hamPpqAjiwLDpwn0x1"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.exuggug9pp2pftsg.local-ngrok-cname.com",
			"created_at": "2025-02-21T10:17:55Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tLYyQ6zXhDA5GcQ1Srplnn9V5D",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tLYyQ6zXhDA5GcQ1Srplnn9V5D"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2025-02-21T10:17:55Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.exuggug9pp2pftsg.local-ngrok-cname.com",
			"created_at": "2025-02-21T10:17:55Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2tLYyNxRzd0bcbiG44u8iS99JET",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2tLYyNxRzd0bcbiG44u8iS99JET"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
