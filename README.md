# Public

---
### Activate gm-utils.js
```javascript
var _ju = {};

JU.publish(global.JU.__JU, false, true);
delete global.JU.__JU;
JU.activate(_ju);

// OR

// This will publish all the library to the window instance
JU.publish(global.JU.__JU, true, true);
delete global.JU.__JU;
```
