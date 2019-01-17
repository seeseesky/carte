---
category: Data
resturi: '/data/getIntervals'
title: 'Get full route intervals'
type: 'GET'

layout: null
---

This method allows users to retrieve full set of route intervals.

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
        ...interval objects
    ]
}
```
