## POST /symptoms/:slug

> Example Request

```shell
curl -X "GET" "/symptoms/stress" \
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
    "symptom": {
      "name": "Stress",
      "slug": "stress"
    }
  }
}
```

This endpoint retrieves a symptom

### HTTP Request

`GET /symptoms/:slug`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Symptom slug `stress`
