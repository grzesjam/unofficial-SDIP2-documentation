# Current state of bus

TODO: stuff

**URL** : `/index/getStopsOnRoute`

**Method** : `POST`

**Data constraints**

```json
{
   "lineId": 242
}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
  "lines": [
    {
      "endName": "Maciejów Kondratowicza",
      "id": 242,
      "lineKind": 3,
      "lineName": "6",
      "lineNumber": 6,
      "lineNumberText": "6",
      "routes": [
        {
          "direction": 1,
          "endName": "Gliwice Plac Piastów",
          "id": 1547,
          "name": "6013",
          "segments": [
            {
              "endLatitude": 5029479,
              "endLongitude": 1895315,
              "endPlatformID": 157939,
              "endPlatformName": "Chorzów Pałac Ślubów",
              "endStopID": 157939,
              "id": 888,
              "points": [
                {
                  "id": 3543,
                  "latitude": 5029002,
                  "longitude": 1896382,
                  "order": 1,
                  "segmentPointId": 1775,
                  "timeOnSegment": 0
                },
                {
                  "id": 1059,
                  "latitude": 5029479,
                  "longitude": 1895315,
                  "order": 52,
                  "segmentPointId": 1776,
                  "timeOnSegment": 180
                }
              ]
            }
          ]
        }
      ]
    }
  ]
}
```
