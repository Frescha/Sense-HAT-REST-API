# Environmental sensors - Humidity

Gets the percentage of relative humidity from the humidity sensor.

**URL** : `/api/v1/humidity`

**Method** : `GET`

**Auth required** : Yes

**Data constraints**

```json
{
    "date": "[timestring]",
    "explanation": "[password in plain text]",
    "unit": "[ ]"
    "data": "[Returned type: string]"
}
```

**Data example**

```json
{
  "data": "1.0",
  "date": "2017-12-29 22:38",
  "explanation": "Gerneral Information: API Version v1.0",
  "unit": "None"
}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
  "data": "1.0",
  "date": "2017-12-29 22:38",
  "explanation": "Gerneral Information: API Version v1.0",
  "unit": "None"
}
```

## Error Response

**Condition** : TODO

**Code** : `400 BAD REQUEST`

**Content** :

```json
{
    "non_field_errors": [
        "TODO"
    ]
}
```