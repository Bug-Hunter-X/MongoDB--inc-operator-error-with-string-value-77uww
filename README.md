# MongoDB $inc operator error with string value
This repository demonstrates an error that occurs when using the `$inc` operator in a MongoDB update query with a non-numeric value.
The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides the corrected code.
The error arises from attempting to increment a field with a string value, which is not supported by the `$inc` operator. The `$inc` operator expects a numerical value to increment or decrement a field's value.