# Current state of bus

TODO: stuff

**URL** : `/index/getStopsOnRoute`

**Method** : `POST`

**Data constraints**

```json
{
  "stopId": 158798
}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
  "lines": [
    {
      "id": 66,
      "name": "156",
      "number": "156",
      "routes": [
        {
          "direction": 1,
          "endName": "Zabrze Goethego",
          "id": 382,
          "routeNumber": "156005",
          "startName": "Gliwice Zajezdnia",
          "trips": [
            {
              "arrivalTime": -59260,
              "arrivalTimeUnix": 1604129540,
              "number": 101,
              "time": 19500,
              "timeUnix": 1604208300
            },
            {
              "arrivalTime": -61960,
              "arrivalTimeUnix": 1604126840,
              "number": 201,
              "time": 16800,
              "timeUnix": 1604205600
            }
          ]
        }
      ]
    },
    {
      "id": 109,
      "name": "194N",
      "number": "194N",
      "routes": [
        {
          "direction": 0,
          "endName": "Gliwice Zajezdnia",
          "id": 689,
          "routeNumber": "194N001",
          "startName": "Szczygłowice Centrum Przesiadkowe",
          "trips": [
            {
              "arrivalTime": -66280,
              "arrivalTimeUnix": 1604122520,
              "number": 702,
              "time": 12480,
              "timeUnix": 1604201280
            },
            {
              "arrivalTime": -75460,
              "arrivalTimeUnix": 1604113340,
              "number": 1002,
              "time": 3300,
              "timeUnix": 1604192100
            }
          ]
        }
      ]
    }
  ]
}
```
