## POST /strains/:slug/aromas

> Example Request

```shell
curl -X "GET" "/strains/durban-poison/aromas" \
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
    "aromas": [
      {
        "name": "Earthy",
        "slug": "earthy"
      },
      {
        "name": "Pine",
        "slug": "pine"
      },
      {
        "name": "Pungent",
        "slug": "pungent"
      },
      {
        "name": "Spicy",
        "slug": "spicy"
      },
      {
        "name": "Sweet",
        "slug": "sweet"
      }
    ]
  }
}
```

This endpoint retrieves the aromas of a given strain

### HTTP Request

`GET /strains/:slug/aromas`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Strain slug `durban-poison`
