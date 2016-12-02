## POST /aromas/all

> Example Request

```shell
curl -X "POST" "/aromas/all" \
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
    "aromas": [
      {
        "name": "Berries",
        "slug": "berries"
      },
      {
        "name": "Earthy",
        "slug": "earthy"
      }
    ]
  }
}
```

This endpoint retrieves all the aromas in the database

### HTTP Request

`POST /aromas/all`