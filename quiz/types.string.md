String
======

Explain the difference.
```JavaScript
''.charAt(0); //''
''[0]; //undefined
```

Explain the difference.
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

Why is slice better than substring?
```JavaScript
var str = 'JavaScript';
str.substring(5, -1); //'JavaS'
str.slice(5, -1); //'crip'
```

Explain the result.
```JavaScript
"" == "0" //false
+"" == +"0" //true
```

Specify true conditions.
```JavaScript
'а' < 'б'; //true
'Ёж' > 'Лиса'; //false
'ёж' > 'лиса'; //true
'5' > '25'; //true
5 > '25'; //false
```

How to compare internationalized string?
```JavaScript
'ёж'.localeCompare('лиса'); //-1
```

How to replace all dash to space?
```JavaScript
'no-boder-attribute'.replace(/-/g,' ');
```

Explain the result.
```JavaScript
var str = 'JavaScript';
str.prop = 5; //no errors
str.prop; //undefined
```

Explain the result.
```JavaScript
var s2 = new String('2 + 3');
eval(s2);  //'2+3'
eval(s2.valueOf()); //5
```

