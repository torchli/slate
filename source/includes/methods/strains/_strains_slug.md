## POST /strains/:slug

> Example Request

```shell
curl -X "POST" "/strains/durban-poison" \
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
    "strain": {
      "name": "Durban Poison",
      "slug": "durban-poison",
      "category": {
        "name": "Sativa",
        "slug": "sativa"
      },
      "levels": {
        "thc": "25.29%",
        "cbn": "1.2%",
        "cbd": "3.94%"
      },
      "flavors": [
        {
          "name": "Earthy",
          "slug": "earthy"
        }
      ],
      "aromas": [
        {
          "name": "Pine",
          "slug": "pine"
        }
      ],
      "effects": [
        {
          "name": "Happy",
          "slug": "happy"
        }
      ],
      "symptoms": [
        {
          "name": "Stress",
          "slug": "stress"
        }
      ],
      "negatives": [
        {
          "name": "Dry Mouth",
          "slug": "dry-mouth"
        }
      ]
    }
  }
}
```

This endpoint retrieves a specific strain.

<aside class="warning">
If the strain cant by found a status code of 404 will be returned.
</aside>

### HTTP Request

`POST /strains/:slug`

### URL Parameters

Parameter | Description
--------- | -----------
slug | Strain slug `durban-poison`
