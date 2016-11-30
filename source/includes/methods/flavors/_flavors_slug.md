## GET /flavors/:slug

> Example Request

```shell
curl -X "GET" "/flavors/indica" \
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
    "flavor": {
      "name": "Grape",
      "slug": "grape"
    }
  }
}
```

This endpoint retrieves a flavor

### HTTP Request

`GET /flavors/:slug`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Flavor slug `grape`
