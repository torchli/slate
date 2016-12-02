## POST /flavors/:slug/strains

> Example Request

```shell
curl -X "POST" "/flavors/grape/strains" \
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
        "name": "Kurple Fantasy",
        "slug": "kurple-fantasy"
      }
    ]
  }
}
```

This endpoint retrieves the strains from a flavor

### HTTP Request

`POST /flavors/:slug/strains`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Flavor slug `grape`
