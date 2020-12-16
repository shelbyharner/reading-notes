# Read8 Operators and Loops

## Comparison Operators - Evaluating Conditions
  - == is equal to: compares two values to see if they are the same
  - === is strict equal to: compares two value types to make sure the data type and value are the same
  - != is not equal to: compares two values to make sure they are NOT the same
  - !== is strict not equal to: compares two value types to make sure the data type and value are NOT the same
  - ">" greater than: number on the left of symbol is greater than the other
  - "<" less than: number on the left of the symbol is less than the other
  - ">=" greater than or equal to
  - "<=" less than or equal to

## Logical Operators
Comparison operators usually compare single values of true/false (boolean), but logical operators compare the results of more than one comparison operator.
  - && is logical and: operator tests more than one condition
  - || is logical or: operator tests at least one condition
  - ! is logical not: operator takes a single boolean value and inverts it

## Loops/Loop Counters
Loops check a condition. As long as it is true, the code block will run. If it returns true again, the code will run again over and over until the condition returns false and then will stop.

  - "For" loop: for running code in a loop a certain number of times, the condition is usually the counter
  - "While" loop: when the number of times the code should run is unknown, you can use a while loop to make the condition something other than a counter. This code will run as long as the condition is true. 
  - "Do While" loop: very similar to the "while" loop, this loop will always run the statements inside the curly braces at least once even if the condition returns false
  - Initialization: var i = 0, create a variable and set it to 0 which will then act as the counter
  - Condition: i < 10, makes a loop run until the counter reaches the indicated equation total
  - Update: i++, makes the counter add 1 every time the loop statement is run 