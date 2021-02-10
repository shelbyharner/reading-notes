# Read 10 - JS Debugging

*Duckett JS Book*

Order of execution: the order in which statements are processed.
Debugging is the process of finding errors. Involves a process of deduction.
The console helps narrow down where (what line) the error is happening.

## Execution Context
  - Global context: code in the script but not in a specific function exclusively 
  - Function context: code being run within a function
  - Eval context: text executed like code within an internal function called eval()

## Variable Scope
  - Global scope: a variable called outside of a function and that can be used anywhere
  - Function-level scope: a variable declared within a function that can only be used within that function

## Errors
  - syntax error: incorrect use of the rules of the language
  - reference error: variable not declared or out of scope
  - eval error: incorrect use of eval()
  - URI error: incorrect use of URI functions
  - type error: trying to use an object or method that doesn't exist
  - range error: calling a function using numbers outside of its range
  - error: generic error object
  - NaN: not a number