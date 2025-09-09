

## 1) What is the difference between var, let, and const?

**Scope**:
- var is function-scoped. If declared inside a function, it only works inside that function.  
- let and const are block-scoped, which means they only work inside { } blocks.

**Hoisting**:
- var gets hoisted and becomes undefined at the start.  
- let and const also get hoisted but stay in the Temporal Dead Zone (TDZ). Using them before declaration gives an error.

**Re-declaration**:
- var can be declared again in the same scope.  
- let and const cannot be redeclared in the same scope.

**Re-assignment**:
- var and let values can be changed.  
- const values cannot be changed (constant).

**Use Cases**:
- var is mostly used in old (ES5) code.  
- let is used when you need to change the variable value later.  
- const is used when the value should not change.

---

## 2) What is the difference between map(), forEach(), and filter()?

**Purpose**:
- forEach() → Runs a function on each element, but does not return a new array.  
- map() → Runs a function on each element and returns a new array.  
- filter() → Selects elements based on a condition and returns a new array.

**Use Case**:
- forEach() → When you just need side effects (e.g., console.log, calculations).  
- map() → When you want to transform elements (e.g., multiply each by 2).  
- filter() → When you need only some elements based on a condition.


## 3) What are arrow functions in ES6?

**Definition**:
Arrow functions are a new syntax in ES6 (2015) for writing functions in a shorter and simpler way.


## 4) How does destructuring assignment work in ES6?

**Definition**:
Destructuring assignment is a feature in ES6 that allows us to easily extract values from arrays or objects into separate variables. It makes code shorter and easier to read.

## 5)Explain template literals in ES6. How are they different from string concatenation?

**Definition**: Template literals are a feature in ES6 that let us create strings using backticks (`). They allow writing multi-line strings and inserting variables or expressions inside ${ }.