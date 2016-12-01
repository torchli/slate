## POST /aromas/:slug

> Example Request

```shell
curl -X "GET" "/aromas/berries" \
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
    "aroma": {
      "name": "Berries",
      "slug": "berries"
    }
  }
}
```

This endpoint retrieves a category

### HTTP Request

`GET /aromas/:slug`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Aroma slug `berries`
