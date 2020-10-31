# Current state of bus

TODO: stuff

**URL** : `/index/getStopsOnRoute`

**Method** : `POST`

**Data constraints**

```json
{
  "lineId": 377
}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
  "lineId": 377,
  "stops": {
    "backward": [
      {
        "direction": 0,
        "id": 158739,
        "name": "Gliwice Plac Piastów",
        "sequence": 1,
        "tariffNumber": 1
      },
      {
        "direction": 0,
        "id": 158798,
        "name": "Gliwice Zajezdnia",
        "sequence": 2,
        "tariffNumber": 2
      },
      {
        "direction": 0,
        "id": 161953,
        "name": "Zabrze Goethego",
        "sequence": 3,
        "tariffNumber": 3
      },
      {
        "direction": 0,
        "id": 159242,
        "name": "Katowice Mickiewicza",
        "sequence": 12,
        "tariffNumber": 12
      }
    ],
    "forward": [
      {
        "direction": 1,
        "id": 159242,
        "name": "Katowice Mickiewicza",
        "sequence": 1,
        "tariffNumber": 1
      },
      {
        "direction": 1,
        "id": 180198,
        "name": "Zabrze Goethego",
        "sequence": 8,
        "tariffNumber": 8
      },
      {
        "direction": 1,
        "id": 158800,
        "name": "Gliwice Zajezdnia",
        "sequence": 9,
        "tariffNumber": 9
      },
      {
        "direction": 1,
        "id": 158738,
        "name": "Gliwice Plac Piastów",
        "sequence": 10,
        "tariffNumber": 10
      }
    ]
  }
}
```
