# Basics:

## 1. What are the primitive data types in JavaScript?

- 7 data types
- holds single value
- immutable (existing value can not be changed)
- Types
  1. Number
  2. String
  3. Boolean
  4. Undefined - declared but not assigned
  5. Null - intentional absence of value
  6. Symbol - Unique identifier - purpose to create unique property keys that are guarteed not to clash with keys from other code.
  7. bigint - represent integers with arbitary magnitude.

## 2. Explain the difference between `null` and `undefined`.

- `null`
  - Intentionally absence of value
  - explicitly assigned nothing value
  - place holder to denote that it does not have meaningful value
  - it is falsy value - after evaluation returns false

```js
// Example
let value = null;
console.log(value); // null
console.log(typeof value); // "object"
console.log(Boolean(value)); // false
```

- `Undefined`

  - Denotes variable or object property has been declared but not initialized
  - unintentional absence of value or an error condition
  - funtion return 'undefined' by default if no return has been specified
  - it is falsy value - after evaluation returns false

  ```js
  let value;
  console.log(value); // undefined
  console.log(typeof value); // "undefined"
  console.log(Boolean(value)); // false
  ```

## 3. What is the difference between `==` and `===` operators?

- `==` (Equality Operator)
  - Checks for equality of values after performing type conversion
  - different types compared by attemoting to convert one or both values to a common type
- `===` (Strict Equality Operator)
  - checks values without performing type convert
  - No type conversion

```js
console.log(100 == "100"); // true (equality with type coercion)
console.log(100 === "100"); // false (strict equality without type coercion)
console.log(1 == true); // true (true coerces to 1)
console.log(1 === true); // false (number is not strictly equal to boolean)
```

## 4. Describe hoisting in JavaScript.

## 5. Explain the concept of scope in JavaScript.

## 6. How do you declare variables in JavaScript? What are the differences between `var`, `let`, and `const`?

## 7. Describe the difference between an array and an object in JavaScript.

## 8. How do you access properties of an object in JavaScript?

## 9. Explain the concept of truthy and falsy values in JavaScript.

## 10. What is a closure in JavaScript? Provide an example.

## 11. Explain the difference between function declaration and function expression.

## 12. Describe the use of the `this` keyword in JavaScript functions.

## 13. What is the purpose of the `arguments` object in JavaScript functions?

## 14. Explain the difference between `forEach`, `map`, `filter`, and `reduce` array methods.

## 15. How do you add/remove elements from an array in JavaScript?

## 16. What is the purpose of the `splice` method in JavaScript arrays?

## 17. Describe the difference between `for...in` and `for...of` loops.

## 18. What is asynchronous programming in JavaScript?

## 19. Describe the event loop in JavaScript.

## 20. Explain the purpose of callbacks, promises, and async/await in JavaScript.

## 21. How do you handle errors in asynchronous JavaScript code?

## 22. Explain the purpose of the Document Object Model (DOM) in web development.

## 23. How do you select elements in the DOM using JavaScript?

## 24. Describe the difference between `innerHTML` and `textContent`.

## 25. How do you add event listeners to DOM elements?

## 26. Describe some features introduced in ES6 (ECMAScript 2015).

## 27. Explain the purpose of arrow functions and template literals.

## 28. What are destructuring assignment and spread/rest operators?

## 29. Describe the `class` syntax for defining objects in JavaScript.

## 30. How do you handle errors in JavaScript?

## 31. Explain the purpose of the `try...catch` statement.

## 32. Describe the `throw` statement and when it is used.

## 33. What are some best practices for error handling in JavaScript?

## 34. What is JSON and how is it used in JavaScript?

## 35. Explain the concept of event delegation in JavaScript.

## 36. Describe the difference between synchronous and asynchronous code execution.

## 37. How do you debug JavaScript code?

# Advance

## 1. Explain the prototype chain in JavaScript inheritance.

## 2. How do you create inheritance in JavaScript using prototypes?

## 3. Describe the difference between prototypal inheritance and classical inheritance.

## 4. Discuss the concept of mixins and how they are implemented in JavaScript.

## 5. What is a closure and how does it work in JavaScript?

## 6. Explain the concept of lexical scope and how it relates to closures.

## 7. How are closures useful in JavaScript programming?

## 8. Discuss memory management considerations when using closures.

## 9. What is asynchronous programming in JavaScript?

## 10. Describe the event loop and how it facilitates asynchronous programming.

## 11. Explain the difference between callbacks, promises, and async/await.

## 12. How do you handle errors in asynchronous JavaScript code?

## 13. What is functional programming, and how does it relate to JavaScript?

## 14. Describe higher##order functions and provide examples.

## 15. Explain the principles of immutability and pure functions in functional programming.

## 16. Discuss the benefits of using functional programming techniques in JavaScript.

## 17. Explain the purpose of arrow functions and provide examples of their use.

## 18. Describe the `let`, `const`, and `class` keywords introduced in ES6.

## 19. Discuss the features of ES6 modules and how they differ from CommonJS modules.

## 20. Explain destructuring assignment and how it is used in JavaScript.

## 21. Explain the concept of promises and how they handle asynchronous operations.

## 22. Describe how you can chain promises together using `.then()` and `.catch()`.

## 23. Discuss the async/await syntax and how it simplifies asynchronous code.

## 24. Explain how error handling works with async/await.

## 25. What are generators in JavaScript, and how are they different from regular functions?

## 26. Describe the `yield` keyword and how it is used in generators.

## 27. Explain how generators can be used to create iterable objects.

## 28. Discuss use cases for generators in JavaScript programming.

## 29. Describe the module system introduced in ES6 and how it improves code organization.

## 30. Explain the difference between named exports and default exports.

## 31. Discuss the role of module bundlers like Webpack and Rollup in JavaScript development.

## 32. How do you handle dependencies between modules in a large JavaScript project?

## 33. Describe common JavaScript error types and how to handle them.

## 34. Explain how you can use `try...catch` blocks for error handling in JavaScript.

## 35. Discuss techniques for debugging JavaScript code in the browser and Node.js environments.

## 36. How do you handle errors in asynchronous code?

## 37. Discuss strategies for optimizing JavaScript performance in web applications.

## 38. Explain techniques for minimizing render ##blocking and improving page load times.

## 39. Describe the importance of code splitting and lazy loading in optimizing JavaScript bundles.

## 40. Discuss tools and techniques for profiling and diagnosing performance issues in JavaScript code.

## 41. Explain the event loop in the context of JavaScript runtime environments.

## 42. Describe the differences between the call stack, callback queue, and event loop.

## 43. Discuss the concept of concurrency in JavaScript and how it is managed by the event loop.

## 44. How does the event loop handle tasks with different priorities (e.g., microtasks vs macrotasks)?

## 45. What is memoization, and how can it be used to optimize function performance?

## 46. Explain the concept of memoization in the context of caching function results.

## 47. Describe techniques for optimizing JavaScript code for better performance.

## 48. Discuss common bottlenecks in JavaScript applications and how to address them.

## 49. Describe the Document Object Model (DOM) and its relationship with JavaScript.

## 50. Explain the purpose of various Web APIs (e.g., Fetch API, Web Storage API, Web Workers).

## 51. Discuss the role of the browser in rendering web pages and executing JavaScript code.

## 52. How does JavaScript interact with browser events, such as mouse clicks and keyboard input?

## 53. What is CORS, and why is it important in web development?

## 54. Explain how CORS works and the mechanisms it uses to enforce security.

## 55. Discuss techniques for bypassing CORS restrictions in client##side and server##side JavaScript code.

## 56. How do you mitigate security vulnerabilities such as Cross##Site Scripting (XSS) and Cross##Site Request Forgery (CSRF) in JavaScript applications?

## 57. Discuss the principles of immutability and how they relate to functional programming.

## 58. Explain currying and partial application in the context of functional programming.

## 59. Describe the concept of monads and their role in functional programming.

## 60. How does functional programming promote code reusability and maintainability?

## 61. Describe common design patterns used in JavaScript applications (e.g., Singleton, Observer, Factory).

## 62. Discuss the benefits and drawbacks of using design patterns in JavaScript development.

## 63. Explain architectural principles such as Separation of Concerns (SoC) and Don't Repeat Yourself (DRY).

## 64. How do you apply design patterns and architectural principles to create scalable and maintainable JavaScript applications?

## 65. What is TypeScript, and how does it extend JavaScript?

## 66. Explain the benefits of static typing in TypeScript compared to JavaScript.

## 67. Describe the key features of TypeScript (e.g., interfaces, generics, decorators).

## 68. Discuss how TypeScript improves code quality and developer productivity in large##scale projects.

## 69. Discuss strategies for effective error handling in JavaScript applications.

## 70. Explain how you would log errors and debug information in a production JavaScript environment.

## 71. Describe techniques for capturing and reporting errors in client##side and server##side JavaScript code.

## 72. How do you handle and recover from critical errors in long##running JavaScript applications?

## 73. Describe tools and techniques for monitoring and profiling JavaScript performance.

## 74. Explain how you would identify and optimize performance bottlenecks in JavaScript code.

## 75. Discuss strategies for minimizing network latency and optimizing client##side rendering in web applications.

## 76. How do you measure and improve the Time to First Byte (TTFB) and Time to Interactive (TTI) of a web page?

## 77. Discuss advanced browser features such as WebRTC, WebAssembly, and WebRTC.

## 76. Explain how you would use Service Workers and Progressive Web Apps (PWAs) to enhance web application performance and offline capabilities.

## 77. Describe the role of browser dev tools (e.g., Chrome DevTools) in debugging and profiling JavaScript code.

## 78. How do you leverage modern CSS features (e.g., Flexbox, Grid, CSS Variables) to create responsive and visually appealing web designs?

## 79. Explain how memory management works in JavaScript.

## 80. Describe the role of garbage collection in JavaScript and how it helps manage memory.

## 81. Discuss memory leaks in JavaScript applications and how to detect and prevent them.

## 82. How do you optimize memory usage in JavaScript applications to minimize memory overhead?

## 83. Describe the challenges of cross##browser compatibility in JavaScript development.

## 84. Explain the purpose of polyfills and how they address browser compatibility issues.

## 85. Discuss strategies for testing and ensuring cross##browser compatibility in JavaScript applications.

## 86. How do you handle legacy browser support while leveraging modern JavaScript features?

## 87. Discuss techniques for optimizing web performance, including minimizing render##blocking resources and reducing time to first paint (TTFP).

## 88. Explain how lazy loading, code splitting, and tree shaking can improve page load times and resource utilization.

## 89. Describe the importance of caching strategies (e.g., HTTP caching, service workers) in improving web performance.

## 90. How do you measure and analyze web performance metrics using tools like Lighthouse and WebPageTest?

## 91. Explain the event##driven architecture of Node.js and how it differs from traditional server architectures.

## 92. Discuss common security vulnerabilities in Node.js applications and how to mitigate them.

## 93. Describe strategies for optimizing the performance of Node.js applications, including clustering, load balancing, and caching.

## 94. How do you handle memory management and resource consumption in long##running Node.js processes?

## 95. Describe the principles of continuous integration (CI) and continuous deployment (CD) in software development.

## 96. Explain how you would set up a CI/CD pipeline for a JavaScript project using tools like Jenkins, Travis CI, or GitHub Actions.

## 97. Discuss best practices for automating code quality checks, testing, and deployment in a CI/CD pipeline.

## 98. How do you handle rollbacks and versioning in a CI/CD environment to ensure robust and reliable releases?

## 99. Discuss common security threats in web applications and how to prevent them (e.g., XSS, CSRF, SQL injection).

## 100. Explain the principles of secure authentication and authorization in web applications.

## 101. Describe best practices for implementing user authentication mechanisms (e.g., JWT, OAuth) in JavaScript applications.

## 102. How do you ensure secure communication between client and server using encryption and HTTPS?

## 103. Explain how JavaScript can be used for machine learning and data visualization tasks.

## 104. Discuss libraries and frameworks like TensorFlow.js and D3.js for machine learning and data visualization in JavaScript.

## 105. Describe use cases for machine learning and data visualization in web applications and data analysis.

## 106. How do you handle large datasets and optimize performance when visualizing data in JavaScript applications?

## 107. Explain the importance of accessibility in web development and the principles of inclusive design.

## 108. Describe techniques for improving accessibility in JavaScript applications, including ARIA attributes and keyboard navigation.

## 109. Discuss tools and resources for testing and auditing the accessibility of JavaScript applications.

## 110. How do you ensure that your JavaScript code complies with accessibility standards and guidelines?

## 111. Explain the role of WebSockets in enabling real##time communication between client and server.

## 112. Discuss libraries and frameworks like Socket.io for implementing real##time features in JavaScript applications.

## 113. Describe use cases for real##time communication in web applications (e.g., chat applications, live updates).

## 114. How do you handle scalability and performance challenges when implementing real##time features in JavaScript applications?

## 115. Explain the concept of progressive enhancement and how it promotes resilience in web design.

## 116. Discuss techniques for building resilient JavaScript applications that degrade gracefully in older browsers.

## 117. Describe strategies for implementing feature detection and conditional loading to enhance user experience in JavaScript applications.

## 118. How do you balance modern web development practices with the need for backward compatibility and accessibility?

1. What is javaScript ?
   - high level
   - interpreted programming language
   - commonly used as client side scripting lanugae
2. What is the key difference between null and undefined?
   1. Null - null represents intentional absence of value
   2. Undefined - represents declared but not defined
3. What is difference between == and === in javascript?
   - == : equality operator
     - comparing values with type conversion
   - === : strict equality operator
     - comparing values without type conversion
4. What is hoisting in javaScript ? (Used)

   - declaration moved to the top of their containing scope during the compilation phase.
   - allows function and variables to be used before declaration
   - let, const and class declaration are not hoisted

5. What are closures in javascript ? (Access)

   - closure = function + lexical environment
   - allowing functions to retain access to their surrounding context
   - the ability to remember its lexical scope

   ```js
   function outerFunction() {
     let outerVariable = "I am from outerFunction";

     function innerFunction() {
       console.log(outerVariable); // Inner function has access to outerVariable
     }

     return innerFunction;
   }

   const closure = outerFunction(); // Call outerFunction and assign the returned inner function to 'closure'
   closure(); // Invoke the inner function, which still has access to outerVariable
   ```

   - used for
     1. Encapsulation
     2. Data privacy
     3. Creating modules or factor purposes

6. Explain the event bubbling and event capturing in JavaScript
7. What is prototype chain in JS?
   - mechanism for inheritance in JS
   - object inherit properties and functions from there prototype object.
   - each object have internal reference to its prototype

```js
// Define a constructor function
function Person(name) {
  this.name = name;
}

// Add a method to the prototype of Person
Person.prototype.sayHello = function () {
  console.log("Hello, my name is " + this.name);
};

// Create a new object using the Person constructor
let person = new Person("John");

// Access the sayHello method on the person object
person.sayHello(); // Output: Hello, my name is John

// The person object inherits the sayHello method from the Person.prototype object
// and ultimately from Object.prototype
```

8. What are arrow functions in JavaScript ?
   - concise way to write functions
   - shorter syntax
   - inherit this from surrounding environment.
9. Explain the difference between let, const, and var in javascript.

   - var : function scoped, allows redecoration and reassignment
   - let : block-scoped cannot be declared with in the same scope
   - const : block scoped, cannot be redeclared or reassigned once initialised

10. What are promises in JS ?
    - object representing the eventual completion or failure of asynchronous operation.

- Alternative to callbacks

11. What is lexical scope in javaScript ?
    - how variables and functions are scoped and accessed within the code
    -
