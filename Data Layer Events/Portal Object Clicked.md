# Portal Object Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Portal Object Clicked",
    "portalObjectClicked": {
        "portalObject": [
            {
                "portalObjectId": "<portalObjectId>"
            }
        ]
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|portalObjectClicked.portalObject[n].portalObjectId|string|Unique identifier of a portal object|My Accounts, Transactions, Messages, My Reports|||||||




