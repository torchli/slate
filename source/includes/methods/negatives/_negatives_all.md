## POST /negatives/all

> Example Request

```shell
curl -X "POST" "/negatives/all" \
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
        "name": "Paranoid",
        "slug": "paranoid"
      },
      {
        "name": "Headache",
        "slug": "headache"
      }
    ]
  }
}
```

This endpoint retrieves all the negatives in the database

### HTTP Request

`POST /negatives/all`