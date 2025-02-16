# Incorrect Usage of $inc Operator in MongoDB

This repository demonstrates a common error when using the `$inc` operator in MongoDB. The error arises from incorrectly specifying the field to increment within the `$inc` operator, leading to unexpected behavior or errors.

## Bug
The provided code snippet uses the `$inc` operator incorrectly within the `updateOne` method. This results in unexpected behavior or a failure to update the counter value.

## Solution
The solution code provides the correct usage of the `$inc` operator within the `updateOne` method. It correctly specifies the field to be incremented, ensuring the counter value is updated as expected.