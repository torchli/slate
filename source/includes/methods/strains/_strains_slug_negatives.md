## POST /strains/:slug/negatives

> Example Request

```shell
curl -X "POST" "/strains/durban-poison/negatives" \
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
    "negatives": [
      {
        "name": "Dry Mouth",
        "slug": "dry-mouth"
      },
      {
        "name": "Dry Eyes",
        "slug": "dry-eyes"
      },
      {
        "name": "Paranoid",
        "slug": "paranoid"
      },
      {
        "name": "Anxious",
        "slug": "anxious"
      },
      {
        "name": "Headache",
        "slug": "headache"
      }
    ]
  }
}
```

This endpoint retrieves the negatives of a given strain

### HTTP Request

`POST /strains/:slug/negatives`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Strain slug `durban-poison`
