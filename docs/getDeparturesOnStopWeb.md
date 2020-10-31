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
  "announcementHash": 2,
  "departures": [
    {
      "destinationName": "Łabędy Huta",
      "destinationStopId": 158820,
      "lineName": "126",
      "lineNumberText": "126",
      "plan": 80400,
      "platformNumber": "4",
      "provider": 0,
      "real": 333,
      "realTimePaired": 0,
      "routeNumber": "126005",
      "tripNumber": 119,
      "typeVehicle": 0,
      "vin": 0
    }  
  ],
  "stopId": 183172,
  "stopName": "Gliwice Żurawia",
  "stopPostNumber": "2"
}
```
