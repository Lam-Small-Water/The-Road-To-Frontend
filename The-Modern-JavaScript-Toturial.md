# Chapter: An introduction

## For The First Coding & Code Structure
### **We can use a `<script>` tag to add JavaScript code to a page.**
### **The `type` and language `attributes` are not required.**
### **A script in an exteranl file can be inserted with `<script src='path/to/script.js'></script>`.**


# Chapter: JavaScript Fundamentals
## Variables
### **We can declare variables to store data by using the `var`, `let`, `const` keywords.**
> **`let` -is a modern variable declaration.**

> **`var` -is an old-school variable declaration.**

> **`const` -is like let, but the value of the variable can't be changed.**
### **Variables should be named in a way that allows us to easily understand what's inside them.**

## Data Types
### **There are 8 basic data types in JavaScript.**

> **Seven primitive data types:**

>> **`number` -for numbers of any kind: integer or floating-point, integers are limited by ±(2^53-1).**

>> **`bigint` -for integer numbers of arbitrary length.**

>> **`string` -for string. A string may have zero or more characters, there's no separate single-character type.**

>> **`boolean` -for `true`/`false`.**

>> **`null` -for unknow values -a standalone type that has a single value `null`.**

>> **`undefined` -for unassigned values -a standalone type that has a single value `undefined`.**

>> **`symbool` -for unique indentifiers.**

> **And one non-primitive data type:**

>> **`object` -for more complex data structures.**

### **The `typeof` operator allows us to see which type is stored in a variable.**

> **Usually used as `typeof x`, but `typeof(x)` is also possible.**

> **Returns a string with the name of the type, like `string`.**

> **For null returns 'object' -this is an error in the language, it's not actually an object.**