## GET /effects/all

> Example Request

```shell
curl -X "GET" "/effects/all" \
     -H "Token: torchli_" \
     -H "Accept: application/vnd.torchli.v1"
```

> The above command returns JSON structured like this:

```json
{
  "meta": {
    "code": 200
  },
  "data": {
    "effects": [
      {
        "name": "Relaxed",
        "slug": "relaxed"
      },
      {
        "name": "Sleepy",
        "slug": "sleepy"
      },
      {
        "name": "Happy",
        "slug": "happy"
      },
      {
        "name": "Hungry",
        "slug": "hungry"
      },
      {
        "name": "Euphoric",
        "slug": "euphoric"
      },
      {
        "name": "Tingly",
        "slug": "tingly"
      },
      {
        "name": "Energetic",
        "slug": "energetic"
      }
    ]
  }
}
```

This endpoint retrieves all the effects in the database

### HTTP Request

`GET /effects/all`