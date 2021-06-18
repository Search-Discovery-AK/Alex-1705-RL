# Wishlist Shared

### 

## Javascript Code
```js
window.appEventData1705RL = window.appEventData1705RL || [];
appEventData1705RL.push({
  "event": "Wishlist Shared",
    "product": [
        {
            "price": {
                "priceType": "<priceType>",
                "sellingPrice": "<sellingPrice>"
            },
            "productInfo": {
                "productID": "<productID>"
            }
        }
    ],
    "wishlist": {
        "total": {
            "value": "<value>"
        }
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|priceType|string|Describes the type of price offered using commonly used terms. |1st mark, 2nd mark, 3rd mark, clearance, sale, doorbuster|||||||
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||
|sellingPrice|string|String representation of the price paid after coupons or discounts. Positive. Up to two decimal places for cents. No currency symbol.|200, 29.99, 50, 0|^[0-9]*(\.[0-9]{1,2})?$||||||
|value|string|String representation of the total value of all products in a wishlist. Positive. Up to two decimal places for cents. No currency symbol.|5, 20, 10.22|^[0-9]*(\.[0-9]{1,2})?$||||||
