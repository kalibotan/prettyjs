Number (IEEE 754-1985)
======================

Select the correct variants.
```JavaScript
123.toString(); //SyntaxError: identifier starts immediately after numeric literal
123..toString(); //"123"
123.4.toString(); //"123.4"
123.4..toString(); //SyntaxError: missing name after . operator
```

Explain the result.
```JavaScript
123.4535.toFixed(3); //123.454
123.5235.toFixed(3); //123.523
```

Specify true conditions.
```JavaScript
NaN == NaN; //false
NaN === NaN; //false
isNaN(0/0); //true
```

Select the variants with number result.
```JavaScript
+'3'; //3
+'3pt'; //NaN
parseInt('3'); //3
parseInt('3px'); //3
```

Explain the difference
```JavaScript
3.5^0; //3
3.5.toFixed(); //4
Math.round(3.5); //4
Math.floor(3.5); //3
Math.ceil(3.5); //4
```

Is loop infinite?
```JavaScript
var i = 0;
while (i != 10) {
  i += 0.2;
}
```

Write the function isNaN.
```JavaScript
function isNaN(num){
  return num != num;
}
```

How to compare 0 and -0?
```JavaScript
1/0 !== 1/-0; //true
```

