## POST /flavors/all

> Example Request

```shell
curl -X "GET" "/flavors/all" \
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
        "name": "Sweet",
        "slug": "sweet"
      },
      {
        "name": "Grape",
        "slug": "grape"
      }
    ]
  }
}
```

This endpoint retrieves all the flavors in the database

### HTTP Request

`GET /flavors/all`