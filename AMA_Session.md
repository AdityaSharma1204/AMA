# AMA Session

### 1. What is a higher-order function?
A higher-order function is a function that takes another function as an argument or returns a function.
Examples: `map()`, `filter()`, and `reduce()`.

### 2. Explain the `find()` function.
`find()` returns the first element in an array that satisfies the given condition.
If no element matches, it returns `undefined`.

### 3. What is the return type of an asynchronous function?
An `async` function always returns a `Promise`.
The promise is fulfilled with the function's returned value or rejected if an error occurs.

### 4. What is array destructuring?
Array destructuring lets you extract values from an array and store them in variables easily.
Example: `const [a, b] = [10, 20];`.

### 5. What is a promise?
A Promise is an object that represents the eventual success or failure of an asynchronous operation.
It has three states: `pending`, `fulfilled`, and `rejected`.

### 6. How do you initialize a promise?
A Promise is initialized using the `Promise` constructor with an executor function.
Example: `const promise = new Promise((resolve, reject) => { ... });`.

### 7. Give an example of an asynchronous program.
`setTimeout(() => console.log("Hello"), 1000);` runs the callback after 1 second.
JavaScript can continue executing other code while waiting for the timer.

### 8. What is the difference between `null` and `undefined`?
`undefined` means a value has not been assigned, while `null` means an intentional empty value.
Example: `let a;` gives `undefined`, while `let b = null;` gives `null`.

### 9. What is the difference between `map()` and `filter()`?
`map()` transforms every element and returns an array of the same length.
`filter()` returns only the elements that satisfy a condition, so its length can change.

### 10. Explain promise chaining.
Promise chaining means using multiple `.then()` calls to execute asynchronous operations one after another.
The value returned from one `.then()` is passed to the next `.then()`.

### 11. What is the difference between `slice()` and `splice()`?
`slice()` returns a portion of an array without changing the original array.
`splice()` can add, remove, or replace elements and modifies the original array.

### 12. What is the `typeof` of an array?
The `typeof` of an array is `"object"` because arrays are objects in JavaScript.

### 13. How does `Promise.race()` work?
`Promise.race()` returns a promise that settles as soon as the first promise settles.
It can be fulfilled or rejected depending on which promise finishes first.
