# Ugletty JS

## Loops

```JavaScript
while (counter --> 0)
  some_action();
```

```JavaScript
for (;counter--;)
  some_action();
```

```JavaScript
for (
  ;counter--;
  some_action()
);
```

```JavaScript
for (var i=arr.length; i--;) 
  some_action();
```

## Conditional Statements

```JavaScript
switch (true) {
  case value > 2:
  case value === 0:
    some_action();
  case value > 10:
    other_action();
    break;
  default:
    another_action();
}
```

```JavaScript
  var valueMin, valueMax;
  ...
  flag ? (valueMax = 100) : (valueMin = -50);
```
