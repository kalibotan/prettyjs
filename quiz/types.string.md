String
======

Explain the difference
```JavaScript
''.charAt(0); //''
''[0]; //undefined
```

```JavaScript
if (str.indexOf('Java') > -1) ...
if (~str.indexOf('Java')) ...
```

How can you get substring?
```JavaScript
var str = 'JavaScript';

str.substring(1, 2); //'a'
str.substring(4); //'Script'
str.slice(4, 10); //'Script'
str.substr(4, 6); //'Script'
str.substr(-6); //'Script'
```

```JavaScript
var str = 'JavaScript';

str.substring(5, -1); //'JavaS'
str.slice(5, -1); //'crip'
```

