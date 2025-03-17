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



