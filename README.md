# Array-Destructuring, Object-Destructuring, Default-Values, Rest-Operator, Swapping-Values.

In JavaScript, destructuring is a powerful feature that allows you to extract values from arrays or properties from objects in a concise and convenient way. Here are examples of destructuring in JavaScript:

1. Array Destructuring:
const numbers = [1, 2, 3, 4, 5];

// Extracting values into individual variables
const [first, second, , fourth] = numbers;

console.log(first);  // 1
console.log(second); // 2
console.log(fourth); // 4

2. Object Destructuring:
const person = { name: 'John', age: 30, city: 'New York' };

// Extracting properties into individual variables
const { name, age } = person;

console.log(name); // 'John'
console.log(age);  // 30

3. Default Values:
You can also provide default values in case a value is undefined:

const numbers = [1];

const [first, second = 2] = numbers;

console.log(first);  // 1
console.log(second); // 2 (default value since the array has only one element)

4. Rest Operator:
The rest operator (...) can be used to collect the remaining elements into a new array:
const numbers = [1, 2, 3, 4, 5];

// Using the rest operator to collect the remaining elements
const [first, ...rest] = numbers;

console.log(first); // 1
console.log(rest);  // [2, 3, 4, 5]

5. Swapping Values:
Destructuring allows for a concise way to swap variable values:

let a = 1;
let b = 2;

// Swapping values using destructuring
[a, b] = [b, a];

console.log(a); // 2
console.log(b); // 1

These examples showcase the flexibility and convenience of destructuring in JavaScript, making code more readable and expressive. Destructuring is widely used in modern JavaScript development.

