## POST /categories/:slug/strains

> Example Request

```shell
curl -X "GET" "/categories/indica/strains" \
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
    "strains": [
      {
        "name": "Purple Kush",
        "slug": "purple-kush",
        "category": "Indica"
      },
      {
        "name": "Afghan Purple Kush",
        "slug": "afghan-purple-kush",
        "category": "Indica"
      }
    ]
  }
}
```

This endpoint retrieves the strains from a category

### HTTP Request

`GET /categories/:slug/strains`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Category slug `indica`
