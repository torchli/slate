## POST /effects/:slug

> Example Request

```shell
curl -X "GET" "/effects/relaxed" \
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
    "effect": {
      "name": "Relaxed",
      "slug": "relaxed"
    }
  }
}
```

This endpoint retrieves an effect

### HTTP Request

`GET /effects/:slug`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Effect slug `relaxed`
