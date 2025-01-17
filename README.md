# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field in a document. However, providing a string value instead of a number will not increment the field correctly and may result in errors.

## Bug
The `bug.js` file contains code that attempts to increment a field using the `$inc` operator with a string value. This results in an error because the `$inc` operator expects a numerical value.

## Solution
The `bugSolution.js` file provides the correct way to use the `$inc` operator to increment a field. The correct approach is to provide a numerical value to the `$inc` operator.
