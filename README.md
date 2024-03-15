# JavaScript Fundamentals

# What is JavaScript?
JavaScript is a high-level, interpreted programming language that is primarily used for adding interactivity to web pages. It allows you to dynamically manipulate website content, respond to user actions, and create interactive web applications.

# Getting started
To begin writing JavaScript code, all you need is a text editor and a web browser. You can write JavaScript directly within an HTML file using <script> tags or in a separate .js file and link it to your HTML file using the <script src="filename.js"></script> tag.


# Variables
Variables are containers for storing data values. In JavaScript, you can declare variables using the var, let, or const keywords.

```javascript
var x = 5;
let y = 10;
const z = 15;
```

```
console.log(x + y);  // Output: 15
```

`var` is function-scoped, `let` is block-scoped, and `const` is block-scoped and its value cannot be reassigned.

# Data Types
JavaScript has several data types including `String`, `Number`, `Boolean`, `Object`, `Array`, `null`, and `undefined`.

```javascript
var name = "John";
var age = 30;
var isStudent = true;
var person = { name: "Alice", age: 25 };
var colors = ["red", "green", "blue"];
var emptyValue = null;
var undefinedValue = undefined;
```

# Operators
JavaScript supports various operators such as arithmetic, assignment, comparison, logical, and more.

```javascript
var a = 5;
var b = 2;
```

```
console.log(a + b); // Addition
console.log(a - b); // Subtraction
console.log(a * b); // Multiplication
console.log(a / b); // Division
console.log(a % b); // Modulus
console.log(a ** b); // Exponentiation
console.log(a === b); // Equality
console.log(a !== b); // Inequality
console.log(a > b); // Greater than
console.log(a < b); // Less than
console.log(a && b); // Logical AND
console.log(a || b); // Logical OR
console.log(!a); // Logical NOT
```


# Control Flow
JavaScript provides control flow statements such as `if`, `else`, `switch`, `while`, `do-while`, `for`, etc., for executing code conditionally or repeatedly.

```javascript
var hour = 10;

if (hour < 12) {
  console.log("Good morning!");
} else if (hour >= 12 && hour < 18) {
  console.log("Good afternoon!");
} else {
  console.log("Good evening!");
}
```


# Functions
Functions are reusable blocks of code that perform a specific task. They can take parameters as inputs and return values.

```javascript
function greet(name) {
  return "Hello, " + name + "!";
}

```

```
console.log(greet("John")); // Output: Hello, John!
```

# Objects
Objects are collections of key-value pairs. Keys are strings, and values can be of any data type, including other objects or functions.


```javascript
var person = {
  name: "John",
  age: 30,
  isStudent: false,
  greet: function() {
    return "Hello, my name is " + this.name + ".";
  }
};
```

```
console.log(person.name); // Accessing property
console.log(person["age"]); // Another way to access property
console.log(person.greet()); // Invoking method
```

# Arrays
Arrays are ordered collections of values. They can contain elements of any data type and can be dynamically resized.

```javascript
var fruits = ["apple", "banana", "orange"];
```

```
console.log(fruits[0]); // Accessing element
console.log(fruits.length); // Length of array
fruits.push("grape"); // Adding element to end
fruits.pop(); // Removing element from end
console.log(fruits); // Output: ["apple", "banana", "orange"]
```


This should give you a solid foundation in JavaScript.
