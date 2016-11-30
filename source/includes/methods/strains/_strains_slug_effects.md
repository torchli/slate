## GET /strains/:slug/effects

> Example Request

```shell
curl -X "GET" "/strains/durban-poison/effects" \
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
        "name": "Uplifted",
        "slug": "uplifted"
      },
      {
        "name": "Energetic",
        "slug": "energetic"
      },
      {
        "name": "Happy",
        "slug": "happy"
      },
      {
        "name": "Euphoric",
        "slug": "euphoric"
      },
      {
        "name": "Creative",
        "slug": "creative"
      }
    ]
  }
}
```

This endpoint retrieves the effects of a given strain

### HTTP Request

`GET /strains/:slug/effects`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Strain slug `durban-poison`
