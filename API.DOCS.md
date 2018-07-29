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

### Response:
```json
[
{
"status": true,
"message": "",
"total": 5
},
{
"plugins": [
{
"name": "Entity Limit",
"author": "PaiN",
"version": "0.6.3",
"file": "EntityLimit.cs"
},
{
"name": "FriendlyFire",
"author": "playrust.io / dcode",
"version": "1.6.0",
"file": "FriendlyFire.cs"
},
{
"name": "Gather Manager",
"author": "Mughisi",
"version": "2.2.6",
"file": "GatherManager.cs"
},
{
"name": "GUIAnnouncements",
"author": "JoeSheep",
"version": "1.23.83",
"file": "GUIAnnouncements.cs"
},
{
"name": "Heli Ride",
"author": "ColonBlow",
"version": "1.1.13",
"file": "HeliRide.cs"
}
]
}
]
```
