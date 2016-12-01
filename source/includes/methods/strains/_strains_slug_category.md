## POST /strains/:slug/category

> Example Request

```shell
curl -X "GET" "http://localhost:3000/api/strains/durban-poison/category" \
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
    "category": {
      "name": "Sativa",
      "slug": "sativa"
    }
  }
}
```

This endpoint retrieves the category of a specific strain

### HTTP Request

`GET /strains/:slug/category`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Strain slug `durban-poison`
