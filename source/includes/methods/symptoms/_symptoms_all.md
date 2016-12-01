## POST /symptoms/all

> Example Request

```shell
curl -X "GET" "/symptoms/all" \
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
        "name": "Insomnia",
        "slug": "insomnia"
      },
      {
        "name": "Depression",
        "slug": "depression"
      },
      {
        "name": "Lack of Appetite",
        "slug": "lack-of-appetite"
      }
    ]
  }
}
```

This endpoint retrieves all the symptoms in the database

### HTTP Request

`GET /symptoms/all`