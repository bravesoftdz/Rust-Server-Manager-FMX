# RSM API Docs
Following is the API Documentation for RSM

## Request Format:
Please follow the following format when using the API. All responses are in json format.
```html
POST/GET http://<IP>:<PORT>/<PATH>
```

## GetServerConfig
Returns the server config in json format.
```HTML
GET http://<IP>:<PORT>/GetServerConfig
```

| Name  | Description |
| ------------- | ------------- |
| key  | API Key configured in RSM (Required)  |

## GetPlugins
Returns a list of plugins in json format.
```HTML
GET http://<IP>:<PORT>/GetPlugins
```

| Name  | Description |
| ------------- | ------------- |
| key  | API Key configured in RSM (Required)  |
