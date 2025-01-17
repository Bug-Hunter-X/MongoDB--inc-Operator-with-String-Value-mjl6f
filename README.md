# MongoDB $inc Operator with String Value

This repository demonstrates an uncommon error in MongoDB when using the `$inc` operator with a string value instead of a numeric value.

The error occurs when you try to increment a field with a string value.  The `$inc` operator expects a numeric value to increment the field. If you provide a string, MongoDB will treat it as a string and concatenate instead of incrementing the value.

This can lead to unexpected and difficult-to-debug behavior in your application.

## Bug
The `bug.js` file demonstrates the incorrect usage of the `$inc` operator.

## Solution
The `bugSolution.js` file shows the correct way to use the `$inc` operator with a numeric value.