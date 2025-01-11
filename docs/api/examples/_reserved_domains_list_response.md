<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2rTjh1ah1I01PQ2QZcJFvmN74iC",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2rTjh1ah1I01PQ2QZcJFvmN74iC"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.3ttmwcszhscespbss.local-ngrok-cname.com",
			"created_at": "2025-01-11T10:07:54Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2rTjh783Sqr73uO4UHKppRCAKTt",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2rTjh783Sqr73uO4UHKppRCAKTt"
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
					"started_at": "2025-01-11T10:07:54Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.3ttmwcszhscespbss.local-ngrok-cname.com",
			"created_at": "2025-01-11T10:07:54Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2rTjh4R6Co4cLpZClV8QSqm7CqJ",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2rTjh4R6Co4cLpZClV8QSqm7CqJ"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
