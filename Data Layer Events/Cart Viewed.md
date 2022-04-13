# Cart Viewed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Cart Viewed",
    "cart": {
        "cartID": "<cartID>",
        "item": [
            {
                "price": {
                    "isHidden": <isHidden>
                },
                "productInfo": {
                    "brand": "<brand>",
                    "isOutOfStock": <isOutOfStock>,
                    "productID": "<productID>"
                }
            }
        ]
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|cart.cartID|string|Back-end identifier for a shopping cart|12345, 435678, 34567, XCV456, XCV876|||||||
|cart.item[n].price.isHidden|integer|Count of times the price of a product was hidden in the cart due to MAP \(Minimum Advertised Pricing\) requirements.   Set in the product string for only those products where it is applicable, with a value of 1||||||||
|cart.item[n].productInfo.brand|string|Describes the brand of a product or offering.|Ford, Chevrolet, Dodge, Levis, Columbia, Patagonia|||||||
|cart.item[n].productInfo.isOutOfStock|integer|Count of times a product was out of stock at the time of cart view.||||||||
|cart.item[n].productInfo.productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||




