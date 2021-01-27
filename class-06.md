# Read 06 - JS Object Literals; The DOM

*Chapter 3*

  - Object: grouping of variables and functions to make a model. 
    - The group of variables become a property.
    - The group of functions become a method.
  - Example: create an object to check hotel room availability or calendar meeting time availability.

*Chapter 5*

  - DOM: Document Object Model, specifies how browsers create an HTML model and how JS can access/update the contents of the page in the browser window
  - DOM Tree - model of the webpage
  - DOM Node - all attributes and elements of the HTML/page
  - DOM query - returns an element or a NodeList/collection of nodes

  - Individual element selectors:
    - getElementById() - quickest way to access a single element, no two can have the same value/ID
    - querySelector() - not supported by older browsers as it is a new HTML addition, flexible as it is a CSS selector
  
  - Multiple element selectors: 
    - getElementsByTagName(): h1
    - getElementsByTagName(): li
    - getElementsByClassName(): hot-class name
    - querySelectorAll(): li, id
  
  - textContent and innerHTML (DOM manipulation) allows access to an element node and the ability to update it's properties
  - An element node can contain multiple text nodes and child elements that are siblings of each other
  - Viewing the DOM tree: right click, inspect > click element > pick properties