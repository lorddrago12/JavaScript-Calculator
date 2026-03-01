# JavaScript Calculator

A simple JavaScript calculator that performs basic arithmetic operations.

## Features

- Addition
- Subtraction
- Multiplication
- Division (with division by zero protection)
- Square
- Square Root

## Usage

```js
calculateSum(2, 5);           // 7
calculateDifference(22, 5);   // 17
calculateProduct(13, 5);      // 65
calculateQuotient(7, 11);     // 0.636...
calculateQuotient(3, 0);      // "Error: Division by zero"
calculateSquare(9);           // 81
calculateSquareRoot(25);      // 5
```

## Error Handling

Division by zero returns `"Error: Division by zero"` instead of throwing an error, keeping the calculator safe to use in any context.
