Number (IEEE 754-1985)
======================

123.toString(); //SyntaxError: identifier starts immediately after numeric literal
123..toString(); //"123"
123.4.toString(); //"123.4"
123.4..toString(); //SyntaxError: missing name after . operator

123.4535.toFixed(3); //123.454
123.5235.toFixed(3); //123.523
