c
# Array Operations

A simple npm package for performing various operations on arrays.

## Installation

You can install this package via npm:

```bash
npm i day_3_hw_arrays_utilitys
```
Usage
To use the array operations functions, require the module in your JavaScript code:

```javascript
const arrayOperations = require('day_3_hw_arrays_utilitys');

const arr = [1, 2, 3, 4, 5];

// Example usage of functions
const sum = arrayOperations.sumofAllArray(arr);
console.log(`Sum of all elements in the array: ${sum}`);

const product = arrayOperations.productofAllArray(arr);
console.log(`Product of all elements in the array: ${product}`);

const average = arrayOperations.averageOfArray(arr);
console.log(`Average of all elements in the array: ${average}`);

const max = arrayOperations.findMaxInArray(arr);
console.log(`Maximum value in the array: ${max}`);

const min = arrayOperations.findMinInArray(arr);
console.log(`Minimum value in the array: ${min}`);

const reversedArray = arrayOperations.reverseArray(arr);
console.log(`Reversed array: ${reversedArray}`);

const countOfTwo = arrayOperations.countOccurrences(arr, 2);
console.log(`Number of occurrences of 2 in the array: ${countOfTwo}`);

const sorted = arrayOperations.isSorted(arr);
console.log(`Is the array sorted?: ${sorted}`);

const uniqueArray = arrayOperations.removeDuplicates(arr);
console.log(`Array with duplicates removed: ${uniqueArray}`);

```

Functions
sumofAllArray(arr)
Calculates the sum of all elements in an array.

productofAllArray(arr)
Calculates the product of all elements in an array.

averageOfArray(arr)
Calculates the average of all elements in an array.

findMaxInArray(arr)
Finds the maximum value in an array.

findMinInArray(arr)
Finds the minimum value in an array.

reverseArray(arr)
Reverses the elements of an array.

countOccurrences(arr, value)
Counts the number of occurrences of a value in an array.

isSorted(arr)
Checks if an array is sorted in ascending order.

removeDuplicates(arr)
Removes duplicate elements from an array.