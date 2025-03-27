Page-1 : Introduction to JavaScript
---------------------------------------------------------
JavaScript (JS) is a fundamental web technology, along with HTML and CSS. It allows developers to create interactive and dynamic web applications.

   JavaScript is a high-level, interprete programming language, meaning it does not need compilation before execution.  

  It is mainly used for client-side web development but can also run on servers using Node.js.  
   
Unlike HTML and CSS, JavaScript enables dynamic content updates, user interaction, and automation in web pages.  

   JavaScript can manipulate the DOM (Document Object Model) to change webpage structure and style dynamically.  
   
 It is supported by all modern web browsers without requiring additional plugins.  


Page-2 : Basics of JavaScrip
---------------------------------------------------------
   JavaScript code is embedded inside  HTML or written in separate js files. 

   Case-sensitive language myVariable and myvariable are different.  

   Unicode support: Allows variable names in various scripts but best practice is using English.  

   Commenting in JS:
     Single-line comments  //
     Multi-line comments use /* */ 

 Code executes done line by line (top-down approach)unless controlled by loops or functions.  

   Semicolons  optional but recommended for clarity in complex statements.  



Page-3 :Variables and Data Types
---------------------------------------------------------
Three ways to declare variables
   
     var (old, function-scoped, avoid using in modern JS).  
     let (block-scoped, can be reassigned).  
     const (block-scoped, cannot be reassigned).  


Dynamic typing: A variable can hold different data types at different times like string can later hold a number.  
   
      Primitive Data Types:  
        String → "Hello"  
        Number → 25, 3.14  
        Boolean → true, false  
        Undefined →variable declared but not assigned
        Null → Represents an intentional empty value 
        Symbol (used for unique identifiers, advanced use)  
        BigInt (used for very large numbers)  

    Reference Data Types:  
      Object → {name: "Alice", age: 25}  
      Array → ["apple", "banana", "cherry"]  
      Function → function greet() { return "Hello"; }  


Page-4 : Operators and Expressions
  
         Arithmetic Operators:
          + (Addition) → 5 + 3 = 8  
         - (Subtraction) → 10 - 4 = 6  
         * (Multiplication) → 7 * 2 = 14  
          / (Division) → 20 / 4 = 5  
          % (Modulus) → 10 % 3 = 1 (Returns remainder)  
          (Exponentiation) → 2 ** 3 = 8 (Power of)  

Assignment Operators: Used to assign values.  
 
     = (Assign) → let x = 10;  
     += (Add and assign) → x += 5; // x = x + 5  
     -= (Subtract and assign) → y -= 2; // y = y - 2  
   
Comparison Operators: Used for checking conditions. 


      == (Equal to, compares values but not types) → 5 == "5" (true)  

      === (Strictly equal, compares both value and type) → 5 === "5" (false)  

      != (Not equal) → 10 != 20 (true)  

      !== (Strict not equal, checks value and type) → 10 !== "10" (true)  

      > (Greater than), < (Less than), >= (Greater or equal), <= (Less or equal)  


Logical Operators: Used in conditional statements.  

        && (AND) → true && false (false)  
        || (OR) → true || false (true)  
         ! (NOT) → !true (false)

         

# How the Web Works
       HTTP/HTTPS Protocols: Browsers request web pages from servers using these protocols.
       DNS Resolution: Domain names are translated into IP addresses for locating servers.
       Web Servers: Deliver HTML, CSS, JavaScript, and other resources to browsers.
       Rendering Process: Browsers parse and render HTML, apply styles, and execute JavaScript to display web content.
       Web Standards: Ensure cross-platform compatibility and interoperability between devices.

# Web Standards Model
     Collaboration for Web Standards: W3C and IETF work together to create web standards.
    Importance of Web Standards: Ensure consistent, accessible, and usable web experiences across devices and browsers.
    Cross-Platform Compatibility: Standards promote interoperability, making sure the web functions similarly on all platforms.
    Future-Proofing: Standards are crucial for maintaining and evolving the web.
    
# How Browsers Load Websites  
     DNS Resolution: Browser translates domain names to IP addresses.
     Connecting to the Server: A connection is established with the server hosting the website.
     Sending HTTP Requests: The browser requests resources (HTML, CSS, JS) from the server.
     Processing Responses: The server responds with the requested resources.
     Rendering the Page: The browser renders HTML, applies CSS, and executes JavaScript to display the page.

# How JavaScript Adds Interactivity
JavaScript allows web pages to respond dynamically to user actions, making them interactive rather than static.
It enables real-time updates, such as showing or hiding elements, changing text, and adjusting styles based on user input.
Event Listeners and User Interaction
JavaScript can detect user actions, such as clicks, mouse movements, and key presses, and trigger specific responses.
Event listeners allow functions to run when a particular action occurs on an element.
This makes it possible to create interactive elements like buttons, menus, and forms that respond instantly.
# DOM Manipulation
JavaScript can dynamically change the content of a webpage without needing a full reload.
It allows adding, removing, or modifying text, images, and other elements in real-time.
Styles such as colors, font sizes, and layouts can also be adjusted based on user actions.
# Best Practices for Adding Interactivity
Keeping JavaScript separate from HTML improves organization and makes the code easier to maintain.
Using efficient methods for modifying the webpage ensures better performance and a smoother user experience.
Avoiding unnecessary changes to the page helps prevent slowdowns, especially for animations and frequent updates.

# Understanding Website Publishing
Publishing a website means making it accessible to users on the internet.
It involves selecting a web hosting service, uploading website files, and configuring settings for public access.
# Choosing a Hosting Service
Various web hosting services are available, including free and paid options.
Free hosting platforms like GitHub Pages and Netlify are great for small projects, while paid hosting offers more features and flexibility.
# Domain Names and URLs
A domain name provides a user-friendly address instead of an IP address.
Domain names can be purchased through registrars, or free subdomains may be available with some hosting services.
# Uploading Files to the Web
Files can be uploaded manually via hosting dashboards or using FTP (File Transfer Protocol) and other deployment tools.
Some platforms provide automated deployment options through version control systems like Git.
# Keeping Your Website Updated
Websites need regular updates for content changes, security patches, and performance improvements.
Version control systems help track changes and make updates easier to manage.

# The Role of JavaScript in Web Development

JavaScript is essential for adding interactivity and dynamic behavior to web pages.
It enables features like form validation, animations, and real-time updates.

# Client-Side vs. Server-Side Scripting

JavaScript primarily runs on the client side (in the browser), reducing server load.
Server-side scripting (e.g., with Node.js) allows JavaScript to handle backend processes.

# How Browsers Interpret JavaScript

Browsers download and execute JavaScript files.
The Document Object Model (DOM) allows scripts to modify page content dynamically.

# Progressive Enhancement & Unobtrusive JavaScript

Best practices suggest writing scripts that enhance, but do not break, core functionality.
JavaScript should work alongside HTML and CSS to create a seamless user experience.

# Security Considerations

JavaScript can introduce security risks (e.g., Cross-Site Scripting - XSS).
Proper validation and security measures are necessary when handling user input.

# JavaScript Grammar and Types

1. case-sensitive (myVar ≠ myvar).

2. Single-line: // comment

Multi-line: /* comment */

3. Variables ( var, let, or const.)
 must start with a letter, _, or $.

4. Data Types

Primitive:

String ('text', "text")

Number (42, 3.14)

Boolean (true, false)

Null (null – empty value)

Undefined (uninitialized variable)

Symbol (unique value, ES6+)

BigInt (large integers, ES11+)

Objects:
Collections of key-value pairs ( Array, Function, Date).

5. Type Conversions

console.log("5" + 5); // "55" (string)
console.log("5" - 1); // 4 (number)

6. Truthy & Falsy Values

Falsy: false, 0, "", null, undefined, NaN

Truthy: Anything not falsy (e.g., 42, {}, []).

7. Operators

Arithmetic: +, -, *, /, %, **

Comparison: == (loose), === (strict)

Logical: &&, ||, !

Example:

console.log(5 == "5");  // true (type coercion)
console.log(5 === "5"); // false (strict comparison)

# Control Flow & Error Handling

Code executes from top to bottom unless altered by control structures.

## Conditional Statements
if-else: Executes code based on conditions.
switch: Used for multiple conditions.
for: Repeats a block of code a fixed number of times.
while: Repeats as long as a condition is true.
do-while: Ensures the loop runs at least once.


 ## Error Handling
try-catch: Catches and handles errors to prevent crashes.
finally: Executes code regardless of an error.
Use throw to create custom errors.


Use if-else and switch for decision-making.

Use loops (for, while, do-while) for iteration.

Implement try-catch-finally for robust error handling.

Throw errors when necessary for better debugging.


# Loops and Iteration

## 1. Loop Types 
JavaScript provides multiple loops for iteration:
- **for** – Loops with a counter.
- **while** – Loops while a condition is true.
- **do...while** – Runs at least once, then checks the condition.
- **for...in** – Iterates over object properties.
- **for...of** – Iterates over iterable objects like arrays.

## 2. `for` Loop :Used when the number of iterations is known.

## 3. `while` Loop :Used when the number of iterations is unknown but based on a condition.

## 4. `do...while` Loop: Runs at least once before checking the condition.

## 5. `for...in` Loop :Iterates over properties of an object.

## 6. `for...of` Loop: Iterates over iterable objects like arrays.


## 7. Breaking and Continuing Loops
- **`break`** – Exits the loop completely.
- **`continue`** – Skips to the next iteration.

# JavaScript Functions

1. Function Declaration

Defined using the function keyword.

function greet(name) {
    return `Hello, ${name}!`;
}

2. Function Expressions

Functions assigned to variables (anonymous or named).

const greet = function(name) {
    return `Hello, ${name}!`;
};

3. Arrow Functions

Shorter syntax, does not bind this.

const greet = (name) => `Hello, ${name}!`;

4. Parameters & Arguments

Functions accept parameters and return values.

function sum(a, b) {
    return a + b;
}

5. Default Parameters

Set default values if arguments are missing.

function greet(name = "Guest") {
    return `Hello, ${name}!`;
}

6. Rest Parameters

Handles multiple arguments as an array.

function sum(...numbers) {
    return numbers.reduce((acc, num) => acc + num, 0);
}

7. Callback Functions

A function passed as an argument to another function.

function process(callback) {
    callback();
}

8. Anonymous & Immediately Invoked Function Expressions (IIFE)

Executed immediately after definition.

(function() {
    console.log("IIFE executed");
})();

9. Function Scope & Closures

Functions create their own scope, and closures retain access to their parent scope.

function outer() {
    let count = 0;
    return function inner() {
        count++;
        return count;
    };
}

10. Higher-Order Functions

Functions that take other functions as parameters or return functions.

function multiplyBy(factor) {
    return (num) => num * factor;
}



# Expressions in JavaScript
Expressions produce values and can be categorized into:
Arithmetic Expressions (5 + 3, x * y)
String Expressions ("Hello " + "World")
Logical Expressions (a && b, x || y)
Assignment Expressions (x = 10)


# Types of Operators

## Arithmetic Operators
Perform mathematical operations.

let sum = 10 + 5; // Addition
let product = 10 * 2; // Multiplication
let remainder = 10 % 3; // Modulus

## Comparison Operators
Compare values and return a Boolean.

console.log(5 == "5");  // true (loose equality)
console.log(5 === "5"); // false (strict equality)
console.log(10 > 5);    // true

## Logical Operators
Used to combine Boolean expressions.

console.log(true && false); // false
console.log(true || false); // true
console.log(!true);         // false

## Assignment Operators
Used to assign values.

let x = 10;
x += 5;  // Equivalent to x = x + 5;

## Bitwise Operators
Perform bit-level operations.

console.log(5 & 1); // Bitwise AND
console.log(5 | 1); // Bitwise OR

## Ternary Operator (? :) 
A shorthand for if-else conditions.

let age = 20;
let status = (age >= 18) ? "Adult" : "Minor";
console.log(status); // Adult

## Nullish Coalescing Operator (??)
Returns the right-hand operand if the left-hand operand is null or undefined.

let name = null;
let defaultName = name ?? "Guest";
console.log(defaultName); // Guest

## Optional Chaining Operator (?.)
Prevents errors when accessing properties of null or undefined.

let user = {};
console.log(user?.profile?.name); // undefined (instead of error)


#  Numbers and Strings


JavaScript has a single `Number` type (floating-point, 64-bit IEEE 754 format). 

### Basic Number Operations
```let sum = 10 + 5, product = 10 * 2, quotient = 10 / 2, remainder = 10 % 3;```

### Special Numeric Values
- `Infinity` and `-Infinity`
- `NaN` (Not a Number)
```
console.log(1 / 0); // Infinity
console.log("hello" * 2); // NaN
```

### Parsing Numbers
Convert strings to numbers.
```
console.log(parseInt("42")); // 42
console.log(parseFloat("3.14")); // 3.14
console.log(Number("99")); // 99
```

### Number Methods
```
let num = 5.6789;
console.log(num.toFixed(2)); // "5.68"
console.log(num.toPrecision(3)); // "5.68"
console.log(Number.isNaN(NaN)); // true
```

## 2.JavaScript Strings
Strings represent text and are enclosed in quotes (`'`, `"`, or backticks `` ` `` for template literals).

### String Concatenation & Template Literals
```
let name = "John";
console.log("Hello, " + name + "!"); // Concatenation
console.log(`Hello, ${name}!`); // Template literals
```

### String Methods
```
let str = "JavaScript";
console.log(str.length); // 10
console.log(str.toUpperCase()); // "JAVASCRIPT"
console.log(str.toLowerCase()); // "javascript"
console.log(str.includes("Script")); // true
console.log(str.indexOf("S")); // 4
console.log(str.slice(0, 4)); // "Java"
```

### Escaping Characters
Use `\` to escape special characters.
```
console.log("He said, \"Hello!\""); // "He said, "Hello!""
```

### Converting Between Numbers and Strings
```
let num = 100;
console.log(num.toString()); // "100"
console.log(String(123)); // "123"
console.log(Number("456")); // 456
```


#  Dates and Times

##Creating Dates in JavaScript
JavaScript provides the `Date` object to work with dates and times.
```
let now = new Date(); // Current date and time
let specificDate = new Date("2025-03-18"); // Specific date
let timestamp = new Date(1672531199000); // Using milliseconds since epoch
```

## Getting Date Components
Methods to extract date parts:
```
let date = new Date();
console.log(date.getFullYear()); // Year
console.log(date.getMonth()); // Month (0-based)
console.log(date.getDate()); // Day of the month
console.log(date.getDay()); // Day of the week (0 = Sunday)
console.log(date.getHours()); // Hours (0-23)
console.log(date.getMinutes()); // Minutes
console.log(date.getSeconds()); // Seconds
```

## Setting Date Components
Modify parts of a date:
```
let date = new Date();
date.setFullYear(2025);
date.setMonth(11); // December (0-based)
date.setDate(25); // 25th day
console.log(date);
```

## Formatting Dates
Convert dates to readable strings.
```
let date = new Date();
console.log(date.toDateString()); // "Tue Mar 18 2025"
console.log(date.toISOString()); // "2025-03-18T00:00:00.000Z"
console.log(date.toLocaleDateString()); // "3/18/2025" (varies by locale)
```

## Date Comparisons
Compare dates using timestamps.
```
let date1 = new Date("2025-01-01");
let date2 = new Date("2025-12-31");
console.log(date1 < date2); // true
```

## 6. **Working with Timestamps**
Get or set the number of milliseconds since January 1, 1970.
```
let now = Date.now(); // Current timestamp in milliseconds
console.log(new Date(now)); // Convert timestamp to date
```


# Regular Expressions

Regular expressions (RegEx) are patterns used to match character combinations in strings. They are commonly used for searching, replacing, and validating text.

## Creating Regular Expressions
There are two ways to create a regular expression in JavaScript:
```javascript
let regex1 = /pattern/; // Literal syntax
let regex2 = new RegExp("pattern"); // Constructor function
```

## Common RegEx Patterns
- `^` – Matches the start of a string
- `$` – Matches the end of a string
- `.` – Matches any character except a newline
- `*` – Matches zero or more occurrences
- `+` – Matches one or more occurrences
- `?` – Matches zero or one occurrence
- `{n,m}` – Matches between `n` and `m` occurrences
- `\d` – Matches any digit (`0-9`)
- `\w` – Matches any word character (letters, digits, underscore)
- `\s` – Matches any whitespace character
- `[^]` – Negates a set, matching anything except specified characters

## Regular Expressions
### Testing a Match
```
let regex = /hello/;
console.log(regex.test("hello world")); // true
```

### Matching Strings
```
let str = "The rain in Spain";
let result = str.match(/ain/g);
console.log(result); // ["ain", "ain"]
```

### Replacing Text
```
let text = "I love JavaScript!";
console.log(text.replace(/JavaScript/, "Regex")); // "I love Regex!"
```

### Extracting Matches
```
let email = "user@example.com";
let match = email.match(/\w+@\w+\.\w+/);
console.log(match[0]); // "user@example.com"
```

## Flags in Regular Expressions
- `g` – Global search (match all occurrences)
- `i` – Case-insensitive search
- `m` – Multi-line search
```
let str = "Hello hello HELLO";
console.log(str.match(/hello/gi)); // ["Hello", "hello", "HELLO"]
```

#  Indexed Collections
Indexed collections in JavaScript include **arrays** and **typed arrays**, which store multiple values in an ordered list.

## Arrays
Arrays store multiple values and can hold different data types.
```
let fruits = ["Apple", "Banana", "Cherry"];
console.log(fruits[0]); // Apple
```

### Common Array Method
- `push()` – Adds an element to the end
- `pop()` – Removes the last element
- `shift()` – Removes the first element
- `unshift()` – Adds an element to the beginning
- `slice()` – Returns a portion of an array
- `splice()` – Adds/removes elements in an array
- `indexOf()` – Finds the index of an element
- `includes()` – Checks if an element exists

```
let numbers = [10, 20, 30, 40];
numbers.push(50); // [10, 20, 30, 40, 50]
numbers.pop(); // [10, 20, 30, 40]
```

### Looping Through Arrays
```
let colors = ["Red", "Green", "Blue"];
colors.forEach(color => console.log(color));
```

### Mapping & Filtering
```
let nums = [1, 2, 3, 4];
let squared = nums.map(n => n * n); // [1, 4, 9, 16]
let evens = nums.filter(n => n % 2 === 0); // [2, 4]
```

## Typed Arrays
Typed arrays store binary data efficiently, useful for handling large numerical datasets.
```javascript
let intArray = new Int16Array([10, 20, 30]);
console.log(intArray[1]); // 20
```

#  Keyed Collections

Keyed collections in JavaScript include **Map** and **Set**, which store data using unique keys or values.

## Map
A `Map` is a collection of key-value pairs where keys can be any data type.
```javascript
let map = new Map();
map.set("name", "Alice");
map.set(1, "one");
console.log(map.get("name")); // Alice
console.log(map.has(1)); // true
```

### Common Map Methods
- `set(key, value)` – Adds a key-value pair
- `get(key)` – Retrieves a value
- `has(key)` – Checks if a key exists
- `delete(key)` – Removes a key-value pair
- `size` – Returns the number of entries
- `clear()` – Removes all entries

```
map.delete("name");
console.log(map.size); // 1
```

## JavaScript Set
A `Set` stores unique values, preventing duplicates.
```
let set = new Set([1, 2, 3, 3, 4]);
console.log(set); // Set {1, 2, 3, 4}
```

### Common Set Methods
- `add(value)` – Adds a value
- `has(value)` – Checks if a value exists
- `delete(value)` – Removes a value
- `size` – Returns the number of elements
- `clear()` – Removes all elements

```
set.add(5);
set.delete(2);
console.log(set.has(3)); // true
```


# Objects

Objects are collections of key-value pairs that store data and methods.
```
let person = {
  name: "Alice",
  age: 25,
  greet: function() {
    console.log("Hello!");
  }
};
console.log(person.name); // Alice
```


### Object Literals
```
let car = { brand: "Toyota", model: "Corolla" };
```

### Using `new Object()`
```
let obj = new Object();
obj.key = "value";
```

### Using Constructors
```
function Person(name, age) {
  this.name = name;
  this.age = age;
}
let user = new Person("Bob", 30);
console.log(user.name); // Bob
```

## Accessing and Modifying Properties
```
console.log(person["name"]); // Alice
person.age = 26;
delete person.greet;
```

## Object Methods
- `Object.keys(obj)` – Returns an array of keys
- `Object.values(obj)` – Returns an array of values
- `Object.entries(obj)` – Returns key-value pairs

```
console.log(Object.keys(person)); // ["name", "age"]
```

## Prototypes and Inheritance
Objects inherit properties from their prototype.
```
function Animal(name) {
  this.name = name;
}
Animal.prototype.speak = function() {
  console.log(this.name + " makes a sound");
};
let dog = new Animal("Dog");
dog.speak(); // Dog makes a sound
```

## `this` in Objects
The `this` keyword refers to the object it belongs to.
```
let user = {
  name: "Alice",
  greet() {
    console.log("Hello, " + this.name);
  }
};
user.greet(); // Hello, Alice
```
#  JavaScript Classes

Classes in JavaScript are a blueprint for creating objects with shared properties and methods.
Classes provide a structured way to create objects with reusable code. Features like inheritance, static methods, and private fields enhance JavaScript's object-oriented capabilities.


```
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
  greet() {
    console.log(`Hello, my name is ${this.name}`);
  }
}
let user = new Person("Alice", 25);
user.greet(); // Hello, my name is Alice
```
### Class Declaration

```
class Car {
  constructor(brand) {
    this.brand = brand;
  }
}
```

### Class Expression

```
const Animal = class {
  constructor(type) {
    this.type = type;
  }
};
```

## Class Methods

- Instance methods are defined inside the class.
- Static methods belong to the class itself and not to instances.

```
class MathHelper {
  static add(a, b) {
    return a + b;
  }
}
console.log(MathHelper.add(5, 3)); // 8
```

## Inheritance with 

Classes can inherit from other classes using `extends`.

```javascript
class Animal {
  constructor(name) {
    this.name = name;
  }
  speak() {
    console.log(`${this.name} makes a sound`);
  }
}
class Dog extends Animal {
  speak() {
    console.log(`${this.name} barks`);
  }
}
let dog = new Dog("Buddy");
dog.speak(); // Buddy barks
```

## Call Parent Methods

The `super` keyword allows calling the parent class constructor and methods.

```
class Parent {
  constructor() {
    console.log("Parent constructor");
  }
}
class Child extends Parent {
  constructor() {
    super();
    console.log("Child constructor");
  }
}
let obj = new Child();
// Parent constructor
// Child constructor
```

## Private and Public Fields

- `#privateField` is only accessible inside the class.

```javascript
class BankAccount {
  #balance = 1000; // Private field
  getBalance() {
    return this.#balance;
  }
}
let account = new BankAccount();
console.log(account.getBalance()); // 1000
```

#  Promises
A Promise in JavaScript represents a value that may be available now, later, or never. It helps manage asynchronous operations efficiently.
Promises simplify asynchronous programming in JavaScript, making it easier to handle operations like API calls, file reading, and database queries without callback hell.

## Creating a Promise
A Promise is an object representing an eventual completion (or failure) of an asynchronous operation. It takes a function as an argument with two parameters: `resolve` and `reject`.

```
let myPromise = new Promise((resolve, reject) => {
  let success = true;
  setTimeout(() => {  // Simulating an asynchronous operation
    if (success) {
      resolve("Operation successful");
    } else {
      reject("Operation failed");
    }
  }, 2000);
});
```
- `resolve(value)`: Marks the promise as fulfilled and returns a value.
- `reject(error)`: Marks the promise as rejected and returns an error.
- The promise remains in the `pending` state until it is either resolved or rejected.

## Promise States
- **Pending** – Initial state, not resolved or rejected.
- **Fulfilled** – The operation completed successfully.
- **Rejected** – The operation failed.

## Handling Promises
### `.then()` and `.catch()`
```
myPromise
  .then(result => console.log(result)) // Operation successful
  .catch(error => console.error(error));
```

###  `async/await` 
```javascript
async function fetchData() {
  try {
    let result = await myPromise;
    console.log(result);
  } catch (error) {
    console.error(error);
  }
}
fetchData();
```

## Chaining Promises
Promise chaining helps execute multiple asynchronous operations in sequence, where the output of one operation is passed as input to the next.

```
myPromise
  .then(result => {
    console.log(result); // Logs "Operation successful"
    return new Promise((resolve) => {
      setTimeout(() => resolve("Next step"), 1000);
    });
  })
  .then(step => {
    console.log(step); // Logs "Next step"
    return "Final step";
  })
  .then(final => console.log(final)) // Logs "Final step"
  .catch(error => console.error(error));
```
### Benefits of Chaining:
- Avoids callback hell
- Improves readability
- Ensures sequential execution

## Promise Methods
- `Promise.all([p1, p2])` – Resolves when all promises resolve.
- `Promise.race([p1, p2])` – Resolves when the first promise resolves.
- `Promise.allSettled([p1, p2])` – Waits for all promises to settle.
- `Promise.any([p1, p2])` – Resolves when any one promise resolves.

```
let p1 = Promise.resolve("First");
let p2 = new Promise((resolve) => setTimeout(() => resolve("Second"), 1000));
Promise.all([p1, p2]).then(console.log); // ["First", "Second"]
```

#  Typed Arrays
Typed Arrays in JavaScript allow handling binary data efficiently. They provide a way to work with raw memory buffers using various numeric types.
it provide high-performance binary data handling in JavaScript, making them useful for graphics, audio processing, and working with Web APIs.

## Creating a Typed Array
Typed arrays are built on `ArrayBuffer`, which represents a fixed-length binary buffer.
```
let buffer = new ArrayBuffer(16); // Creates a buffer of 16 bytes
```

###  `ArrayBuffer`
Views interpret the raw memory as specific data types.
```
let int32View = new Int32Array(buffer);
console.log(int32View.length); // 4 (each Int32 takes 4 bytes)
```

## Common Typed Array Types
| Typed Array | Size per Element |
|------------|----------------|
| `Int8Array` | 1 byte |
| `Uint8Array` | 1 byte |
| `Int16Array` | 2 bytes |
| `Uint16Array` | 2 bytes |
| `Int32Array` | 4 bytes |
| `Uint32Array` | 4 bytes |
| `Float32Array` | 4 bytes |
| `Float64Array` | 8 bytes |

## Reading and Writing Data
Typed arrays function similarly to regular arrays but operate on fixed-size binary data. You can read and modify data using index-based access.

### Reading Data
```
let uint8 = new Uint8Array([10, 20, 30]);
console.log(uint8[1]); // 20
```
- Accessing elements works like a normal array.
- Values are stored in binary but interpreted according to the array type.

### Writing Data
```
uint8[1] = 50;
console.log(uint8); // [10, 50, 30]
```
- Values are overwritten in place without changing array length.
- Typed arrays ensure efficient memory allocation, making them ideal for performance-sensitive applications.

### Iterating Through a Typed Array
```
let int16 = new Int16Array([100, 200, 300]);
for (let value of int16) {
  console.log(value);
}
```
- can use loops like `for...of` to iterate through elements.
- Supports methods like `.map()`, `.forEach()`, and `.reduce()` similar to regular arrays.

### Copying Data Between Typed Arrays
```
let source = new Uint8Array([1, 2, 3]);
let destination = new Uint8Array(3);
destination.set(source);
console.log(destination); // [1, 2, 3]
```
- `set()` allows copying values between different typed arrays.
- It automatically converts values based on the target array type.

##  DataViews for More Control
`DataView` allows setting/getting values with byte offsets and specific endianness.
```
let dataView = new DataView(buffer);
dataView.setInt16(0, 256, true); // Little-endian storage
console.log(dataView.getInt16(0, true)); // 256
```

## Working with Buffers and Views
Typed arrays do not resize dynamically; they are fixed in length.
```
let floatArray = new Float32Array(4);
floatArray[0] = 3.14;
console.log(floatArray.buffer.byteLength); // 16 (4 elements * 4 bytes)
```


#  Iterators and Generators
An iterator in JavaScript is an object that allows sequential access to elements of a collection. It follows the iterator protocol, which defines a `next()` method returning an object with `{ value, done }` properties.
Iterators and generators provide a powerful way to handle sequential data and asynchronous operations in JavaScript, making code more efficient and readable.


## Creating an Iterator
An iterator can be created manually using an object with a `next()` method.
```
function createIterator(arr) {
  let index = 0;
  return {
    next: function() {
      return index < arr.length
        ? { value: arr[index++], done: false }
        : { done: true };
    }
  };
}
const myIterator = createIterator([10, 20, 30]);
console.log(myIterator.next()); // { value: 10, done: false }
```

## Built-in Iterables
JavaScript provides built-in iterables such as:
- Arrays
- Strings
- Maps and Sets
- The `arguments` object

 can iterate through them using a `for...of` loop:
```
const array = [1, 2, 3];
for (let num of array) {
  console.log(num);
}
```

##  Generators
A generator function allows pausing and resuming execution using the `yield` keyword. It returns an iterator.
```
function* myGenerator() {
  yield 1;
  yield 2;
  yield 3;
}
const gen = myGenerator();
console.log(gen.next()); // { value: 1, done: false }
```

## Generator Function Syntax
- Defined using `function*` syntax.
- Uses `yield` to return values one at a time.
- Maintains state between function calls.
- Can be paused and resumed.

## Passing Arguments to Generators
```
function* greet(name) {
  yield `Hello, ${name}!`;
  yield "How are you?";
}
const g = greet("Alice");
console.log(g.next().value); // "Hello, Alice!"
```

## Generators for Infinite Sequences
Generators can create infinite sequences efficiently.
```
function* idGenerator() {
  let id = 1;
  while (true) {
    yield id++;
  }
}

const genId = idGenerator();
console.log(genId.next().value); // 1
```
#  Internationalization

## Internationalization (i18n)
Internationalization (i18n) in JavaScript refers to adapting applications to different languages, regions, and cultural conventions using built-in APIs.
The `Intl` API simplifies internationalization in JavaScript, allowing seamless formatting of numbers, dates, times, and strings based on user locale settings.

##  `Intl` Object
JavaScript provides the `Intl` object to support internationalization, including number formatting, date formatting, and string comparisons.

##  Numbers with `Intl.NumberFormat`**
`Intl.NumberFormat` allows formatting numbers based on locale.
``` 
const formatter = new Intl.NumberFormat('de-DE', { style: 'currency', currency: 'EUR' });
console.log(formatter.format(123456.78)); // "123.456,78 €"
```

### Options for `NumberFormat`
- `style`: `"decimal"`, `"currency"`, `"percent"`
- `currency`: Specifies the currency format
- `minimumFractionDigits`, `maximumFractionDigits`

## Formatting Dates and Times with `Intl.DateTimeFormat`
`Intl.DateTimeFormat` provides locale-aware date and time formatting.
``` 
const dateFormatter = new Intl.DateTimeFormat('en-GB', { dateStyle: 'full' });
console.log(dateFormatter.format(new Date())); // "Tuesday, 18 March 2025"
```

### `DateTimeFormat`
- `dateStyle`: `"short"`, `"medium"`, `"long"`, `"full"`
- `timeStyle`: `"short"`, `"medium"`, `"long"`, `"full"`
- `timeZone`: `"UTC"`, `"America/New_York"`, etc.

## Collation and String Comparison with `Intl.Collator`**
Used for locale-sensitive string comparison.
```
const collator = new Intl.Collator('fr', { sensitivity: 'base' });
console.log(collator.compare('école', 'ecole')); // 0 (equal in French collation rules)
```

## Pluralization with `Intl.PluralRules`**
Determines the correct plural category based on locale.
```
const pluralRules = new Intl.PluralRules('en-US');
console.log(pluralRules.select(1)); // "one"
console.log(pluralRules.select(2)); // "other"
```

## List Formatting with `Intl.ListFormat`
Formats lists in a locale-aware way.
```
const listFormatter = new Intl.ListFormat('en', { style: 'long', type: 'conjunction' });
console.log(listFormatter.format(['Apple', 'Banana', 'Cherry']));
// "Apple, Banana, and Cherry"
```


#  Meta-Programming

## What Is Meta-Programming?
Meta-programming is writing code that manipulates other code dynamically. JavaScript supports meta-programming using features like `Proxy`, `Reflect`, and `eval`.

##  `Proxy` for Object Interception 
The `Proxy` object allows intercepting and customizing operations on objects.
``` 
const handler = {
  get: (target, prop) => {
    return prop in target ? target[prop] : `Property '${prop}' not found`;
  }
};

const obj = new Proxy({ name: "Alice" }, handler);
console.log(obj.name); // "Alice"
console.log(obj.age);  // "Property 'age' not found"
```

### Common Proxy Traps:
- `get(target, prop)`: Intercepts property access.
- `set(target, prop, value)`: Intercepts property assignment.
- `has(target, prop)`: Intercepts the `in` operator.
- `deleteProperty(target, prop)`: Intercepts property deletion.

## `Reflect` for Object Operations 
The `Reflect` API provides methods to perform object operations in a controlled way.
```javascript
const obj = { name: "Bob" };
Reflect.set(obj, "age", 30);
console.log(Reflect.get(obj, "age")); // 30
```

### Common `Reflect` Methods:
- `Reflect.get(target, prop)`: Retrieves property value.
- `Reflect.set(target, prop, value)`: Sets property value.
- `Reflect.has(target, prop)`: Checks if a property exists.
- `Reflect.deleteProperty(target, prop)`: Deletes a property.

## Dynamic Code Execution with `eval` (Use with Caution!)     
The `eval` function allows executing strings as JavaScript code.
 `eval` can introduce security vulnerabilities and performance issues, so it should be avoided when possible.

``` 
eval("console.log('Hello from eval')");
```

## Modifying Object Behavior with `Object.defineProperty`
This method allows defining custom property behavior.
``` 
const person = {};
Object.defineProperty(person, "name", {
  value: "Charlie",
  writable: false
});
console.log(person.name); // "Charlie"
person.name = "David"; // Error in strict mode
```


#  Modules
Modules in JavaScript allow splitting code into reusable, maintainable files. They enable encapsulation and better dependency management.
it provide a clean, efficient way to structure applications, enabling better scalability and maintainability.

##  Exporting and Importing Modules 
Modules use `export` and `import` statements to share functionality across files.

### Exporting
``` 
// math.js
export function add(a, b) {
  return a + b;
}
export const PI = 3.1416;
```

### Importing
``` 
// main.js
import { add, PI } from './math.js';
console.log(add(2, 3)); // 5
console.log(PI); // 3.1416
```

##  Default Exports
A module can have a single default export.
``` 
// logger.js
export default function log(message) {
  console.log(message);
}
```

``` 
// main.js
import log from './logger.js';
log("Hello, Modules!");
```

## Dynamic Imports
JavaScript supports on-demand loading of modules using `import()`.
```javascript
import('./math.js').then(module => {
  console.log(module.add(5, 10)); // 15
});
```

##  Module Scope & Strict Mode
- Modules are in **strict mode** by default (`'use strict'`).
- Variables declared inside a module are **scoped** to that module.

##  Benefits of Using Modules
- Code reusability and maintainability.
- Avoids global namespace pollution.
- Supports asynchronous loading and optimization in modern frameworks.


#Advanced JavaScript Objects

## Prototypes and Inheritance
JavaScript uses prototypal inheritance, where objects inherit properties and methods from a prototype.
Advanced object concepts like prototypes, getters/setters, and `Object.defineProperty()` enhance JavaScript’s flexibility and power for building scalable applications.

```
function Person(name) {
  this.name = name;
}
Person.prototype.greet = function() {
  console.log(`Hello, my name is ${this.name}`);
};
const alice = new Person("Alice");
alice.greet(); // "Hello, my name is Alice"
```

## Object.create() for Prototype-based Inheritance
Allows creating an object with a specific prototype.
``` 
const personProto = {
  greet() {
    console.log("Hello!");
  }
};
const bob = Object.create(personProto);
bob.greet(); // "Hello!"
```

## Getters and Setters
Define custom behavior for property access.
```javascript
const user = {
  _name: "Charlie",
  get name() {
    return this._name.toUpperCase();
  },
  set name(newName) {
    this._name = newName;
  }
};
console.log(user.name); // "CHARLIE"
user.name = "David";
console.log(user.name); // "DAVID"
```

## `Object.defineProperty()`
Allows defining custom properties with specific behaviors.
```
const book = {};
Object.defineProperty(book, "title", {
  value: "JavaScript Guide",
  writable: false, // Read-only
  enumerable: true
});
console.log(book.title); // "JavaScript Guide"
book.title = "New Title"; // Error in strict mode
```

## `this` Keyword in Objects
- Refers to the object calling the method.
- Behavior depends on how a function is invoked.
```
const obj = {
  name: "Eve",
  greet() {
    console.log(this.name);
  }
};
obj.greet(); // "Eve"
```

#   JavaScript Object Prototypes

In JavaScript, every object has an internal link to another object called its prototype. Prototypes enable inheritance and shared properties.
Object prototypes provide a powerful way to implement inheritance and code reuse in JavaScript, forming the foundation of the language’s object model.

## Prototype Chain
When accessing a property, JavaScript first looks in the object itself. If not found, it searches in the prototype chain.
```
const obj = {};
console.log(obj.toString()); // Inherited from Object.prototype
```

## Creating and Using Prototypes
Objects can be linked to a prototype using `Object.create()`.
```
const personPrototype = {
  greet() {
    console.log("Hello!");
  }
};
const alice = Object.create(personPrototype);
alice.greet(); // "Hello!"
```

## Prototype Inheritance with Constructor Functions
```
function Person(name) {
  this.name = name;
}
Person.prototype.greet = function() {
  console.log(`Hi, I'm ${this.name}`);
};
const bob = new Person("Bob");
bob.greet(); // "Hi, I'm Bob"
```

## Modifying Built-in Prototypes (Use with Caution!)
You can add methods to built-in objects, but it's not recommended as it may cause conflicts.
```
Array.prototype.last = function() {
  return this[this.length - 1];
};
console.log([1, 2, 3].last()); // 3
```

## Checking Prototype Relationships
- `Object.getPrototypeOf(obj)`: Gets the prototype of an object.
- `instanceof`: Checks if an object is an instance of a constructor.
```javascript
console.log(Object.getPrototypeOf(bob) === Person.prototype); // true
console.log(bob instanceof Person); // true
```



# Object-Oriented Programming in JavaScript
OOP is a programming paradigm based on objects that contain both data (properties) and behavior (methods). JavaScript supports OOP through prototypal and class-based inheritance.
OOP in JavaScript enables modular, reusable, and maintainable code using concepts like classes, encapsulation, inheritance, and polymorphism.



## Creating Objects Using Classes
JavaScript introduced the `class` syntax to simplify object creation.
```
class Person {
  constructor(name, age) {
    this.name = name;
    this.age = age;
  }
  greet() {
    console.log(`Hi, I'm ${this.name}`);
  }
}
const alice = new Person("Alice", 25);
alice.greet(); // "Hi, I'm Alice"
```

## Encapsulation: Protecting Object Data
Encapsulation restricts direct access to object properties.
```
class User {
  #password;
  constructor(username, password) {
    this.username = username;
    this.#password = password;
  }
  checkPassword(input) {
    return input === this.#password;
  }
}
const user = new User("JohnDoe", "secret");
console.log(user.checkPassword("secret")); // true
```

## Inheritance: Reusing Code
Inheritance allows one class to derive from another.
```
class Animal {
  constructor(name) {
    this.name = name;
  }
  speak() {
    console.log(`${this.name} makes a noise.`);
  }
}
class Dog extends Animal {
  speak() {
    console.log(`${this.name} barks.`);
  }
}
const dog = new Dog("Buddy");
dog.speak(); // "Buddy barks."
```

## Polymorphism: Method Overriding
Polymorphism allows a subclass to provide a specific implementation of a method inherited from a parent class.
```javascript
class Shape {
  area() {
    return 0;
  }
}
class Circle extends Shape {
  constructor(radius) {
    super();
    this.radius = radius;
  }
  area() {
    return Math.PI * this.radius ** 2;
  }
}
const circle = new Circle(5);
console.log(circle.area()); // 78.54
```

## Composition vs. Inheritance
- Inheritance: When objects share behavior through class hierarchies.
- Composition: When objects get functionality by combining smaller, reusable components.
```
class Engine {
  start() {
    console.log("Engine started");
  }
}
class Car {
  constructor() {
    this.engine = new Engine();
  }
  drive() {
    this.engine.start();
    console.log("Car is moving");
  }
}
const car = new Car();
car.drive();
```


#  Classes in JavaScript

## What Are Classes in JavaScript?
JavaScript classes provide a structured way to create objects using a blueprint. They simplify object creation and organization by grouping properties and behaviors into reusable templates. The `class` keyword introduces a more readable syntax compared to prototype-based inheritance.

## Class Features and Structure
A class typically includes a constructor method, which initializes object properties when a new instance is created. Methods can be added to define behavior. Classes support inheritance, allowing one class to derive properties and methods from another.

## Encapsulation and Private Fields
Encapsulation restricts direct access to certain properties, ensuring data integrity. Private fields, introduced with `#`, prevent external modification and enforce controlled interactions with object data.

## Inheritance and Code Reusability
Using `extends`, a class can inherit methods and properties from another class. This promotes reusability and hierarchical structuring of code, reducing redundancy and improving maintainability.

## Static Methods and Utility Functions
Static methods belong to the class itself rather than instances. They are useful for utility functions that do not require individual object state, such as mathematical calculations or helper functions.

## Getters and Setters for Controlled Access
Getters and setters provide a controlled way to access and modify object properties. They help in implementing validation, computed properties, and encapsulation without exposing internal data directly.


# Object Building Practice in JavaScript

# Understanding Object Composition : 
Instead of relying solely on class-based inheritance, JavaScript encourages object composition, where objects are built by combining smaller, reusable parts. This approach improves modularity and flexibility in coding.
Object building in JavaScript is about balancing flexibility and maintainability. Using factory functions, prototypes, and mixins helps create efficient, scalable, and reusable objects while avoiding the pitfalls of deep inheritance chains.

# Factory Functions for Object Creation
Factory functions return objects with shared behavior without using classes. This is useful for creating multiple instances with similar properties and methods.

# Prototypes for Efficiency
Using Object.create() or setting up prototypes ensures that shared methods are not duplicated across instances, optimizing memory usage.

# Encapsulation for Data Protection
Encapsulation hides internal details of an object by using closures or private class fields (# syntax). This prevents accidental modifications and maintains data integrity.

# Mixins for Code Reusability
Mixins allow objects to share functionality without inheritance. Methods are copied into objects or prototypes, enabling flexible and reusable code structures.

# Best Practices in Object Design
Keep objects small and focused on a single responsibility.
Use composition over inheritance for greater modularity.
Apply encapsulation to protect object state.
Use prototypes to improve performance when sharing methods.









