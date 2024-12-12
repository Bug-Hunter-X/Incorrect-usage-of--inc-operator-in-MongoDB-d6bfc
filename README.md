# Incorrect Usage of $inc Operator in MongoDB
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB, leading to an error. The `$inc` operator is used to increment or decrement a numeric field.  Attempting to use it with a string value will throw an error.  The solution shows the correct implementation using a numeric value.

## Bug
The bug lies in the incorrect data type provided to the `$inc` operator.  The correct way to use the `$inc` operator is with a numeric value.