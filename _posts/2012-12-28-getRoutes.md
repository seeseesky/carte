---
category: Data
resturi: '/data/getRoutes'
title: 'Get full route information'
type: 'GET'

layout: null
---

This method allows users to retrieve full set of route information such as route name, seq, stations and intervals.

### Params

| Param Name        | Data Type    |  Mandatory?  |
| --------   | -----:   | :----: |
| route       | String      |   N    |
| seq        | Int      |   N    |

<br/>

### Response

```javascript
{
    "status": 200,
    "error": null,
    "response": [
        {
            "_id": "5c0679a9c21e0da4c76d8914",
            "route": "11",
            "seq": 1,
            "stationCount": 18,
            "active": true,
            "stations": [
              ...
            ],
            "intervals": [
              ...
            ]
        }
    ]
}
```
