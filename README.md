# TypeScript Type Error Bug
This repository demonstrates a common type error in TypeScript: passing an array to a function that expects a string.

## Bug Description
The `greeter` function is defined to accept a single string argument. However, an array of strings is passed to it, resulting in a type error.

## Solution
The solution involves either modifying the `greeter` function to accept an array or modifying the argument passed to the function to be a single string.