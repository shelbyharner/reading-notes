# Passing Functions as Props

## Lifting State Up
  - When several components need to reflect the same changing data, you can lift up the shared state to the closest common ancestor
  - Keeps components in sync with eachother
  - The component that owns the shared state becomes the "source of truth" for the inputs
  - Inputs stay in sync because their values are computed from the same state at the same time

## Lists and Keys
  - React can transform arrays into lists of elements
  - You can build collections of elements in JSX using curly braces {}
  - You can loop through an array using .map() and return an <li> element for each item
  - A "key" is a special string attribute used when creating lists of elements
  - Keys help React identify which items have changed, been added, or removed
  - Keys give the elements inside of an array a stable identity
  - Keys used within arrays should be unique from their siblings, but don't need to be globally unique

## Declaring a Winner
  - Mutating data is directly changing the data values
  - Replacing the data with a new copy using .slice()
  - Immutability makes complex features easier to implement
  - Avoiding direct data mutation allows for previous versions to be reused later
  - Immutability helps build pure components in React
  - Function components are a simple way to write components in React that only contain a render method and don't have their own state
  - These functions take props as an input
  - Less tedious to write than classes

## The Spread Operator
  - The spread operator is used in JS for: 
    - copying an array
    - concatenating or combining arrays
    - using math functions
    - using arrays as arguments
    - adding an item to a list
    - adding to state in React
    - combining objects
    - converting NodeList to an array
  - The spread operator syntax is "..."
  - Function.prototype.apply() is the old way/has same effect as the spread syntax
  - The spread operator creates a new reference to its primitive values and copies them
  - The spread operator is useful for working with arrays and objects in JS