# Portal Objects Displayed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Portal Objects Displayed",
    "portalDisplayed": {
        "portalObject": [
            {
                "isDisplayed": <isDisplayed>,
                "portalObjectId": "<portalObjectId>"
            }
        ]
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|portalDisplayed.portalObject[n].isDisplayed|boolean|Helper node used by AA Product String Builder to set product scoped events|true|||||||
|portalDisplayed.portalObject[n].portalObjectId|string|Unique identifier of a portal object|My Accounts, Transactions, Messages, My Reports|||||||




