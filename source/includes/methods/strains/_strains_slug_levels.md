## GET /strains/:slug/levels

> Example Request

```shell
curl -X "GET" "/strains/durban-poison/levels" \
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
    "levels": {
      "thc": "25.29%",
      "cbn": "1.2%",
      "cbd": "3.94%"
    }
  }
}
```

This endpoint retrieves the levels of a given strain

### HTTP Request

`GET /strains/:slug/levels`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Strain slug `durban-poison`
