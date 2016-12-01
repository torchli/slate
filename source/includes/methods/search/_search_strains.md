## POST /strains/search

> Example Request

```shell
curl -X "POST" "/strains/search" \
     -H "Token: torchli_" \
     -H "Accept: application/vnd.torchli.v1" \
     -H "Content-Type: application/json; charset=utf-8" \
     -d "{
          'keyword': 'berry',
          'categories': [
            'indica'
          ]
        }"

```

> The above command returns JSON structured like this:

```json
{
  "meta": {
    "code": 200,
    "pagination": {
      "total_pages": 2,
      "current_page": 1
    }
  },
  "data": {
    "search": [
      {
        "name": "Blackberry Kush",
        "slug": "blackberry-kush",
        "category": "Indica"
      },
      {
        "name": "Purple Berry",
        "slug": "purple-berry",
        "category": "Indica"
      },
      {
        "name": "Very Berry Haze",
        "slug": "very-berry-haze",
        "category": "Sativa"
      },
      {
        "name": "Hawaiian Snow",
        "slug": "hawaiian-snow",
        "category": "Sativa"
      }
    ]
  }
}
```

This endpoint searches all strains with the provided parameters.

### HTTP Request

`POST /strains/search`

### Query Parameters

Parameter | Description
--------- | -----------
keyword | Search key `berry`
categories | array* What categories to search in
effects | array* What effects to search in
flavors | array* What flavors to search in
aromas | array* What aromas to search in
symptoms | array* What symptoms to search in
negatives | array* What symptoms to search in
