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
