# MongoDB $inc Operator Error
This example demonstrates a common error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is used to increment a numerical field by a specified value.  However, if you provide a string value instead of a number, the update will fail.

## Bug
The provided `bug.js` demonstrates this error. It attempts to increment the 'field' by the string value '1'. This results in an error because the $inc operator expects a numerical value.

## Solution
The `bugSolution.js` demonstrates the correct usage. It increments the field by the numerical value 1. The solution ensures the update is successful.
