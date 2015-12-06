Date
====

Explain the result (Firefox).
```JavaScript
new Date(2015, 1, 1); //Date 2015-01-31T21:00:00.000Z
```

How to detect Invalid date
```JavaScript
var iDate = new Date('none');
isNaN(iDate.getTime()); //true
isFinite(iDate); //false
```

Explain the difference
```JavaScript
+new Date();
Date.now(); //faster
```
