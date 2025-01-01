# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical field by a specified value.  However, if you provide a string value instead of a number, the operation will fail.

## Bug Description:
The provided code incorrectly attempts to increment a field using a string instead of a number.  This results in a MongoDB error.

## Solution:
The solution involves providing a numeric value to the `$inc` operator.