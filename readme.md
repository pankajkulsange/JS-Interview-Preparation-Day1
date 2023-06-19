# SECTION: Q1

difference between == and ===
both are comparision operator and return boolean
== equality operator
check value only
=== strictly equality operator
check value as well as datatype

# SECTION: Q2

difference between let, const and var

- var is a keyword to declare variable with functional scope
- var support redeclaration, reinitialization and reassigning
- support hoisiting
- use before es6

- let and const are keyword used to declare variable with with block scope
- temporal dead zone (let and const does not support hoisiting) (referance error)
- used after es6

- let support reassigning and not support redeclaration and reinitialization

- const does not support redeclaraion, reinitialization or reassigning.
  it is constant

# SECTION: BENIFIT OF HOISITING AND TEMPORAL DEADZONE

Temporal deadzone - improve code quality
find error which hoisiting igonores

# SECTION: FIRST CLASS FUNCTION

passing function as an argument to the higher order function

// higher order function:
get function as parameter

// call back function:
passing function as an argument with a return

// pure function:
return same result if the same argument pass in the function

# SECTION: Execution context

- Synchronous

1. Global execution context
2. Function execution context
3. Memory Allocation
4. Code Execution
5. Call stack

- Asynchronous

1. Event Loop
2. Callback Queue
3. Call Stack
