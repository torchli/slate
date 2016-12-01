## POST /symptoms/:slug/strains

> Example Request

```shell
curl -X "GET" "/symptoms/stress/strains" \
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
        "slug": "purple-kush"
      },
      {
        "name": "8 Ball Kush",
        "slug": "8-ball-kush"
      }
    ]
  }
}
```

This endpoint retrieves the strains from a symptom

### HTTP Request

`GET /symptoms/:slug/strains`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Symptom slug `stress`
