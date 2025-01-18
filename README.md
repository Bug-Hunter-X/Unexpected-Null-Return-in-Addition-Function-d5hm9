# Unexpected Null Return in Addition Function

This repository demonstrates a common error in JavaScript related to unexpected null return values.  The `foo` function is designed to add two numbers, but it unexpectedly returns `null` when both inputs are `null`.  This might lead to unexpected behavior in other parts of the code. The solution shows how to improve the code's handling of null values.

## Bug
The bug lies in how the function handles null input.  Returning `null` when both inputs are `null` is unexpected and may not be the desired behavior.