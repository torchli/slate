## POST /negatives/:slug/strains

> Example Request

```shell
curl -X "POST" "/negatives/dry-eyes/strains" \
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
        "name": "Afghani",
        "slug": "afghani"
      },
      {
        "name": "Jedi Kush",
        "slug": "jedi-kush"
      }
    ]
  }
}
```

This endpoint retrieves the strains from a negative

### HTTP Request

`POST /negatives/:slug/strains`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Negative slug `dry-eyes`
