# Introduction to React and Components

## ‘Passing Data Through Props’
  - React: a JS library for creading UIs using components. 
  - React has a few types of coponents, but we begin with React.Component: this is a sub-class in JS.
  - Components take in parameters which define the properties (props)
  - Props use the render method to return a React Element (lightweight description of what to render)
  - Render method returns a description of what you want to see on the screen.
  - JSX is a special React syntax and comes with the full power of JS
  - You can put any JS expression inside of JSX braces. 

## Hello World
  - JSX is a syntax extension of JS that creates React Elements
  - The pieces of React apps: elements and components
  - No more console.log(), this is a new proof of life

```` javascript

ReactDOM.render(
  <h1>Hello, world!</h1>,
  document.getElementById('root')
);
````

## Introducing JSX
  - JSX uses components that contain markup and logic statements
  - Valid JS can be placed inside of curly braces within the JSX
  - JSX produces React "elements"
  - JSX can be helpful when needing a visual when working with a UI inside of JS
  - JSX allows React to show/utilize more useful error and warning messages
  - JSX is itself an expression and can be used to call functions and objects
  - JSX can contain children such as li and ul
  - Using React.createElement(), you can represent objects in JSX.

## Rendering Elements
  - An element describes what you want to see on the screen. 
  - React elements are plain objects.
  - A "root" DOM node is managed by React DOM.
  - Applications built with just React only use a single DOM root node. 
  - If you are integrating React into an existing application, you may have many root DOM nodes as needed.

  ````javascript
const element = <h1>Greetings, Earthlings!</h1>;
ReactDOM.render(element, document.getElementById('root'));
````
  - You cannot change elements once they are created.
    - If you need to update, you must create new elements and pass them in.