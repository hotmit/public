# Public

---
### Activate gm-utils.js
```javascript
var _ju = {};

JU.publish(JU.__JU, false, true);
delete JU.__JU;
JU.activate(_ju);

// OR

// This will publish all the library to the window instance
JU.publish(JU.__JU, true, true);
delete JU.__JU;
```


