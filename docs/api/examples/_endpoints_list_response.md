<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2025-01-11T10:08:13Z",
			"hostport": "9a2a8c16521b.ngrok.paid:443",
			"id": "ep_2rTjjPYudrqkMXpiKt9RvBY8skd",
			"name": "command_line",
			"principal": {
				"id": "usr_2rTjgvRa9go5nQdkfLO2jghhbYC",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://9a2a8c16521b.ngrok.paid",
			"tunnel": {
				"id": "tn_2rTjjPYudrqkMXpiKt9RvBY8skd",
				"uri": "https://api.ngrok.com/tunnels/tn_2rTjjPYudrqkMXpiKt9RvBY8skd"
			},
			"tunnel_session": {
				"id": "ts_2rTjjPIBn94TzxHqJFZHJ5RnUOS",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2rTjjPIBn94TzxHqJFZHJ5RnUOS"
			},
			"type": "ephemeral",
			"updated_at": "2025-01-11T10:08:13Z",
			"upstream_url": "http://localhost:80",
			"url": "https://9a2a8c16521b.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2025-01-11T10:08:11Z",
			"domain": {
				"id": "rd_2rTjj1Me6e4Wr54T3qKKWqklRjw",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2rTjj1Me6e4Wr54T3qKKWqklRjw"
			},
			"edge": {
				"id": "edgtls_2rTjj3YtFgwaGANvLKd7QnQblvE",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2rTjj3YtFgwaGANvLKd7QnQblvE"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2rTjj3BQr4ZGGbp61LwQf43VWa5",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2025-01-11T10:08:11Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
