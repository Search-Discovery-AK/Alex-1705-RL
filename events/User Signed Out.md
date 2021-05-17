# User Signed Out

## Javascript Code
```js
window.appEventData1705RL = window.appEventData1705RL || [];
appEventData1705RL.push({
  "event": "User Signed Out",
    "user": {
        "system": "<system>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|system|string|Describes the system that the user is logged into.  (rarely used). |admin, shop, member|||||||
|userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||
