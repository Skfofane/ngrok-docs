<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2025-01-11T10:08:21Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2rTjkU5No6RUwC16fLRj8pcvOPM",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2rTjkU5No6RUwC16fLRj8pcvOPM"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2rTjj4gOgUaotUEoBF6N3axLpjn",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2rTjj4gOgUaotUEoBF6N3axLpjn"
				},
				"enabled": true
			},
			"created_at": "2025-01-11T10:08:10Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2rTjj3YtFgwaGANvLKd7QnQblvE",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2rTjj3YtFgwaGANvLKd7QnQblvE"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
