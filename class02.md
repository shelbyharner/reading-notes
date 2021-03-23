# State and Props

## State and Lifecycle
  - To update the UI we use ReactDOM.render
  - State is similar to props, but is private and fully controlled by the component.
  - Convert a function to a class (ex. clock)

```` javascript

class Clock extends React.Component {
  render() {
    return (
      <div>
        <h1>Hello, world!</h1>
        <h2>It is {this.props.date.toLocaleTimeString()}.</h2>
      </div>
    );
  }
}
````

  - The render method will be called each time an update happens to the clock, but only a single instance of the clock class will be used.
  - To update from a class to a local state we change this.props to this.state

```` javascript

class Clock extends React.Component {
  constructor(props) {
    super(props);
    this.state = {date: new Date()};
  }

  render() {
    return (
      <div>
        <h1>Hello, world!</h1>
        <h2>It is {this.state.date.toLocaleTimeString()}.</h2>
      </div>
    );
  }
}
````

  - Class constructors should always call the base constructor with props
  - Mounting is when React "renders" a component for the first time and builds the DOM from the component instructions
  - componentDidMount() sets up a lifestyle method
  - componendWillUnmount() stops a lifestyle method

## Handling Events
  - React events are named using camelCase, rather than just lowercase
  - in JSX you pass a function as the event handler instead of a srting
  - You cannot return false in React to prevent default behavior, you must call preventDefalt explicitly
  - in React you don't need to call addEventListener, you can just add it in the element when it is initially rendered (this.handleClick)
  - You must bind events in React

## Conditional Rendering
  - 