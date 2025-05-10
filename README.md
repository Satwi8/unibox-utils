# unibox-utils

`unibox-utils` is a simple and universal utility library that works both on the frontend and backend. It provides basic utility functions, such as checking if a value is empty, that can be used in various JavaScript environments.

## Install

You can install the package from NPM:

```bash
npm install unibox-utils

Usage
Here's how you can use the isEmpty function to check if a value is empty.

Example 1: Checking an Empty Array
const { isEmpty } = require('unibox-utils');

console.log(isEmpty([])); // true
Example 2: Checking an Empty Object
const { isEmpty } = require('unibox-utils');

console.log(isEmpty({})); // true
Example 3: Checking a Non-Empty String
const { isEmpty } = require('unibox-utils');

console.log(isEmpty('Hello World')); // false
Functions
isEmpty(value)
Parameters:

value: Any type (string, array, object, etc.)

Returns: true if the value is empty; false otherwise.

Example Usage
const { isEmpty } = require('unibox-utils');

// Check if an array is empty
console.log(isEmpty([])); // true

// Check if an object is empty
console.log(isEmpty({})); // true

// Check if a non-empty string is empty
console.log(isEmpty('Some text')); // false
License
MIT License - [Satwi8] © 2025

Contributing
Feel free to fork the repository and submit pull requests for any improvements, bug fixes, or new features!

Repository
You can find the repository on GitHub:

https://github.com/Satwi8/unibox-utils
