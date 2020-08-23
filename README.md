# routerlist
router collection for automations

## Format router list

```json
{
  "routers": [
    {
      "producername": [
        {
          "modem": "modemname",
          "ip": "ip adress",
          "dns": "router dns",
          "username": "default username",
          "password": "default password"
        }
      ] 
    }
  ]
}
```

## Format port list

```json
{
  "portlist": [
    {
      "servicename": {
        "ports": ["80"],
        "description": "service description",
        "TCP": true,
        "UDP": true
      }
    }
  ]
}
```
