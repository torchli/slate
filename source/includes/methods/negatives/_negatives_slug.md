## POST /negatives/:slug

> Example Request

```shell
curl -X "POST" "/negatives/dry-eyes" \
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
    "negative": {
      "name": "Dry Eyes",
      "slug": "dry-eyes"
    }
  }
}
```

This endpoint retrieves a negative

### HTTP Request

`POST /negatives/:slug`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Negative slug `dry-eyes`
