---
category: Data
resturi: '/data/getStations'
title: 'Get all route stations'
type: 'GET'

layout: null
---

This method allows users to retrieve full set of route stations.

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
        ...station objects
    ]
}
```
