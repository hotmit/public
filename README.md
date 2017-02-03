# Public

---
### JU CDN
* All lib functions is imported into window._ju object
* CDN Link
	* https://github.com/hotmit/public/blob/master/js/gm-ju-v1.01.0.min.js

```javascript
// Usage: 
_ju.Str.trim('hello ');
```

---
### Activate gm-utils.js
```javascript
var _ju = {};

JU.publish(JU.__JU, false, false);
delete JU.__JU;
JU.activate(_ju);

// OR

// This will publish all the library to the window instance
JU.publish(JU.__JU, true, false);
delete JU.__JU;
```


### Plain HTML5 Skeleton
```html
<!DOCTYPE html>
<html>
<head>
	<meta charset=utf-8 />
	<title></title>
	<link rel="stylesheet" type="text/css" media="screen" href="css/master.css" />
	<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/1.3.2/jquery.min.js"></script>
	<!--[if IE]>
		<script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
	<![endif]-->
</head>
<body>
	
</body>
</html>
```
