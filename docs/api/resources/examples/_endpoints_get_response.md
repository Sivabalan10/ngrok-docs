<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
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
}
```
