# Unexpected String Concatenation in JavaScript

This example demonstrates a common issue in JavaScript caused by its loose typing system. When adding a number and a string, JavaScript performs string concatenation instead of numerical addition, leading to unexpected results.

## Bug

The `foo` function is intended to add two numbers. However, due to the loose typing, passing a number and a string results in string concatenation.

## Solution

To address this, ensure that both inputs are of the same type (numbers in this case) before performing the addition. Explicit type checking or conversion can prevent this error.  