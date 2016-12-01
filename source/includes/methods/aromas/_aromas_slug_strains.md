## POST /aromas/:slug/strains

> Example Request

```shell
curl -X "GET" "/aromas/berries/strains" \
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
        "name": "Purple Trainwreck",
        "slug": "purple-trainwreck"
      },
      {
        "name": "Glass Slipper",
        "slug": "glass-slipper"
      }
    ]
  }
}
```

This endpoint retrieves the strains from a category

### HTTP Request

`GET /aromas/:slug/strains`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Aroma slug `berries`
