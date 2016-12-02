## POST /effects/:slug/strains

> Example Request

```shell
curl -X "POST" "/effects/relaxed/strains" \
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
        "name": "Thai",
        "slug": "thai"
      },
      {
        "name": "Bubba Kush",
        "slug": "bubba-kush"
      },
      {
        "name": "Alien OG",
        "slug": "alien-og"
      }
    ]
  }
}
```

This endpoint retrieves all the strains associated to an effect

### HTTP Request

`POST /effects/:slug/strains`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Effect slug `relaxed`
