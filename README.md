# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment a numerical value in a document. However, if a string value is provided, it leads to unexpected behavior and may cause the update to fail.

## Bug

The bug arises from providing a string value ('1') instead of a numerical value (1) to the `$inc` operator.

## Solution

The solution involves ensuring that the value being incremented is a number.
