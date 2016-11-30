## GET /categories/all

> Example Request

```shell
curl -X "GET" "/categories/all" \
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
    "categories": [
      {
        "name": "Sativa",
        "slug": "sativa"
      },
      {
        "name": "Indica",
        "slug": "indica"
      },
      {
        "name": "Hybrid",
        "slug": "hybrid"
      }
    ]
  }
}
```

This endpoint retrieves all the categories in the database

### HTTP Request

`GET /categories/all`