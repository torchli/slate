## POST /symptoms/:slug

> Example Request

```shell
curl -X "POST" "/symptoms/stress" \
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

`POST /symptoms/:slug`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Symptom slug `stress`
