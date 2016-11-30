## GET /categories/:slug

> Example Request

```shell
curl -X "GET" "/categories/indica" \
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
      "name": "Indica",
      "slug": "indica"
    }
  }
}
```

This endpoint retrieves a category

### HTTP Request

`GET /categories/:slug`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Category slug `indica`
