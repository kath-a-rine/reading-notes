# JS Debugging

Debugging is the process of finding errors in code. 

* Order of execution - the order in which statements are processed
* the Stack - when a statement needs data from another it stacks.

* Hoisting - allos functions to be used before they are declared [mdn - hoisting](https://developer.mozilla.org/en-US/docs/Glossary/Hoisting)

* Lexical scope - functions linked to the object they were defined in.

* error objects help find where errors are. They point to the line in code where it has come across an error.

* error handling code - statements to handle an error if one is anticipated

1. Debug script to fix errors
2. handle errors gracefully
    * `try` - try to execute code
    * `catch` - if exception, run this code
    * `finally` - runs regardless

## **Debugging Workflow**

1. look for error message
2. check how far script is running
3. use brakpoints where error is occurring

1. breakpoints help you identify if the code around it is working as expected. Do the variables have the values you expect?
2. test functionality on smaller parts of code
3. check parameters in a function or number of items in an array

## console methods

* console.log() - logs to console
* console.info() - for general info
* console.warn() - for warnings
* console.error() - to hold errors
* console.group() - group messages together. use console.groupEnd() to indicate end of the grouped messages
* console.table() - oputs table with objects and arrays within other objects or arrays
* console.assert() - test condition, writes to console if `false`

see pages 484 - 485 in Duckett's JavaScript and jQuery for debugging tips and common errors