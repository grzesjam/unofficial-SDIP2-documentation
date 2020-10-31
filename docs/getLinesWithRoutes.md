# Current state of bus

TODO: what dose it even do?

**URL** : `/index/getLinesWithRoutes`

**Method** : `GET`

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
  "lines": [
    {
      "endName": "Katowice Plac Wolności",
      "endPlatf": "1t",
      "id": 1,
      "lineKind": 0,
      "lineName": "0",
      "lineNumber": 10000,
      "lineNumberText": "T0",
      "routes": [
        {
          "direction": 1,
          "endName": "Chorzów Stadion Śląski Pętla Zach.",
          "id": 1,
          "name": "T0002",
          "platf": "1t"
        },
        {
          "direction": 0,
          "endName": "Katowice Plac Wolności",
          "id": 2,
          "name": "T0001",
          "platf": "1t"
        }
      ],
      "startName": "Chorzów Stadion Śląski Pętla Zach.",
      "startPlatf": "1t"
    }
  ]
}
```

