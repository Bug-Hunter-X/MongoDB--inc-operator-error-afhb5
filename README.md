# MongoDB $inc Operator Error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment or decrement a numerical field in a document. However, providing a non-numeric value as an increment results in an error or unexpected behavior.

## Bug
The provided code snippet uses the `$inc` operator with a string value ('1') instead of a number (1). This will lead to an error. 

## Solution
The solution involves ensuring that the increment value provided to the `$inc` operator is a valid number.