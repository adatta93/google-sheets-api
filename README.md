# google-sheets-api
A JavaScript code to query google sheet page within fixed range

<h3>Missing files</h3>
(not added in Github due to Security)

<h4>credentials.json </h4>
<br />
```yaml
{  
	"web":{  
		"client_id":"<google_client_id>",  
		"project_id":"<project>",  
		"auth_uri":"https://accounts.google.com/o/oauth2/auth",  
		"token_uri":"https://oauth2.googleapis.com/token",  
		"auth_provider_x509_cert_url":"https://www.googleapis.com/oauth2/v1/certs",  
		"client_secret":"<google_client_secret>",  
		"redirect_uris":["http://localhost:3000/auth/google/secrets"],  
		"javascript_origins":["http://localhost:3000"]  
	}
}
```
<br/>
<h4>token.json</h4>
<br/>
```yaml
{  
  "access_token":"<token>",  
  "refresh_token":"<refresh_token>",  
  "scope":"https://www.googleapis.com/auth/spreadsheets.readonly",  
  "token_type":"Bearer",  
  "expiry_date":1597486538327  
}
```
