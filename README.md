
# Simple JS Toolkit

A collection of simple and useful JavaScript utility functions.

## Installation

```bash
npm install @lohamsa/simple-js-toolkit
```

## Usage

```javascript
const toolkit = require("@lohamsa/simple-js-toolkit");

// Capitalize text
console.log(toolkit.capitalize("hello"));
// Hello

// Reverse a string
console.log(toolkit.reverseString("hello"));
// olleh

// Count words
console.log(toolkit.countWords("I love JavaScript"));
// 3

// Check palindrome
console.log(toolkit.isPalindrome("madam"));
// true
```

## Available Functions

| Function | Description |
|---|---|
| capitalize(text) | Capitalizes the first character |
| reverseString(text) | Reverses a string |
| countWords(text) | Counts words |
| isPalindrome(text) | Checks whether text is a palindrome |

## License

ISC
