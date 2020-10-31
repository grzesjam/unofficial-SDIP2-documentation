# Current state of bus

TODO: stuff

**URL** : `/index/getStopLineSchedule`

**Method** : `POST`

**Data constraints**

```json
{
  "stopId": 158798,
  "lineId": 242
}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
  "trips": [
    {
      "number": 102,
      "time": 16740,
      "timeUnix": 1604119140
    },
    {
      "number": 104,
      "time": 28860,
      "timeUnix": 1604131260
    }
  ],
  "actualTime": 78740
}
```
