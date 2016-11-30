## GET /strains/:slug/flavors

> Example Request

```shell
curl -X "GET" "/strains/durban-poison/flavors" \
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
    "flavors": [
      {
        "name": "Earthy",
        "slug": "earthy"
      },
      {
        "name": "Pine",
        "slug": "pine"
      },
      {
        "name": "Sweet",
        "slug": "sweet"
      }
    ]
  }
}
```

This endpoint retrieves the flavors of a given strain

### HTTP Request

`GET /strains/:slug/flavors`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Strain slug `durban-poison`
