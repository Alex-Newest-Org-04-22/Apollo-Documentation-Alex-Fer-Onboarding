# Order Confirmation Interaction Occurred

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Order Confirmation Interaction Occurred",
    "orderConfirmationInteraction": {
        "interactionDetail": "<interactionDetail>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|orderConfirmationInteraction.interactionDetail|string|Captures additional detail for the type of click event engaged with by the user on the order confirmaton page.||||||||




