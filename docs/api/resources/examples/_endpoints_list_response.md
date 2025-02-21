<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-02-21T10:18:16Z",
			"description": "sample cloud endpoint",
			"domain": {
				"id": "rd_2tLZ0LV17ABaz2Pn1sWjuyy0icS",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tLZ0LV17ABaz2Pn1sWjuyy0icS"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tLZ180InglUeMUPCjZP29Hvgv7",
			"metadata": "{\"environment\": \"staging\"}",
			"pooling_enabled": false,
			"proto": "https",
			"public_url": "https://endpoint-example2.com",
			"traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
			"type": "cloud",
			"updated_at": "2025-02-21T10:18:16Z",
			"uri": "https://api.ngrok.com/endpoints/ep_2tLZ180InglUeMUPCjZP29Hvgv7",
			"url": "https://endpoint-example2.com"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-21T10:18:14Z",
			"hostport": "85e0341ba5ea.ngrok.paid:443",
			"id": "ep_2tLZ0kscbGPxBuDSg2MqBflE3eW",
			"name": "command_line",
			"pooling_enabled": false,
			"principal": {
				"id": "usr_2tLYyLkYyS0MNNBzj2ap6TxHvdi",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://85e0341ba5ea.ngrok.paid",
			"tunnel": {
				"id": "tn_2tLZ0kscbGPxBuDSg2MqBflE3eW",
				"uri": "https://api.ngrok.com/tunnels/tn_2tLZ0kscbGPxBuDSg2MqBflE3eW"
			},
			"tunnel_session": {
				"id": "ts_2tLZ0ms6sHRmMR1z6iWnOEhcO5E",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2tLZ0ms6sHRmMR1z6iWnOEhcO5E"
			},
			"type": "ephemeral",
			"updated_at": "2025-02-21T10:18:14Z",
			"upstream_url": "http://localhost:80",
			"url": "https://85e0341ba5ea.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-02-21T10:18:12Z",
			"domain": {
				"id": "rd_2tLZ0LV17ABaz2Pn1sWjuyy0icS",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2tLZ0LV17ABaz2Pn1sWjuyy0icS"
			},
			"edge": {
				"id": "edgtls_2tLZ0MGJEyKElWjhs3nOyfjZWH1",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2tLZ0MGJEyKElWjhs3nOyfjZWH1"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2tLZ0LZJpTCZhCr6XJhdGKNwHn8",
			"pooling_enabled": false,
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-02-21T10:18:12Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
