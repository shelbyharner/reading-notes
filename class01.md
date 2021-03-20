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
  - 