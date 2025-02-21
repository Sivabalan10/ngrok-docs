<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-02-21T10:18:21Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2tLZ1dfwyy1o2i04yHPFGNnsDh6",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tLZ1dfwyy1o2i04yHPFGNnsDh6"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2tLZ0I8nP0fByEPFhbUzmhYnbj7",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2tLZ0I8nP0fByEPFhbUzmhYnbj7"
				},
				"enabled": true
			},
			"created_at": "2025-02-21T10:18:10Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2tLZ0MGJEyKElWjhs3nOyfjZWH1",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2tLZ0MGJEyKElWjhs3nOyfjZWH1"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
