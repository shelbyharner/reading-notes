# In memory storage

## The JavaScript Call Stack - What It Is and Why It's Necessary
  - call stack: data structure that uses last in, first out principle to temporarily store and manage function calls.
  - function execution is done one at a time, top to bottom
  - stack frame: memory location in the stack
  - when a function is called, it's params and variables are pushed into a call stack which forms a stack frame
  - call stack maintains the record of the position of each stack frame and then knows which function to be executed next
  - example: grocery store checkout line - you can only be helped once the person in front of you is finished
  - stack overflow happens when a function calls itself without an exit point (will run over and over and over)
  - the call stack is single-threaded, can only do one thing at a time
  - code execution is synchronous, happens one after the other

## JavaScript error messages && debugging
  - unexpected feature = bug
  - reference error: using a variable that is not defined
  - syntax error: occurrs when you have something that cannot be parsed in terms of syntax
  - range error: trying to manipulate something and giving an invalid length
  - type error: happens when a data type that you are trying to use or access is undefined
  - any code afer an error will not be executed until the error is debugged
  - quokka: evaluates your code as you type
  - eslint: makes sure the code is styled consistently

Save for reference: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors 