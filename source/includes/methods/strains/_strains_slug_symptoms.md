## GET /strains/:slug/symptoms

> Example Request

```shell
curl -X "GET" "/strains/durban-poison/symptoms" \
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
    "symptoms": [
      {
        "name": "Stress",
        "slug": "stress"
      },
      {
        "name": "Depression",
        "slug": "depression"
      },
      {
        "name": "Pain",
        "slug": "pain"
      },
      {
        "name": "Fatigue",
        "slug": "fatigue"
      },
      {
        "name": "Headaches",
        "slug": "headaches"
      }
    ]
  }
}
```

This endpoint retrieves the symptoms of a given strain

### HTTP Request

`GET /strains/:slug/symptoms`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Strain slug `durban-poison`
