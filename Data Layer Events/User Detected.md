# User Detected

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "detect_user",
  "detailed_event": "User Detected",
    "user_data": {
        "affiliate_customer_id": "<affiliate_customer_id>",
        "anonymous_user_id": "<anonymous_user_id>",
        "employee_id": "<employee_id>",
        "user_id": "<user_id>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user_data.affiliate_customer_id|string|The user ID of user who arrived at the website via a third party partner.||||||||
|user_data.anonymous_user_id|string|When a user is not logged in, this captures an anonymous user ID.||||||||
|user_data.employee_id|string|Captures the employee ID associated with website or mobile app traffic.|Gold, Bronze, Platinum, Diamond, Silver|||||||
|user_data.user_id|string|Captures the loyalty ID associated with each user.|abc1234, def876, 87987659|||||||




