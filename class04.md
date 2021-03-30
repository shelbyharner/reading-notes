# React and Forms

  - Form elements work differently than other DOM elements in React because form elements keep some internal state
  - Controlled components include: input, textarea, and select
    - maintain their own state based on user input
  - In React, mutable state is kept in the state property of components (updated with setState())
  - Can combine the two and the React state will be the single source of truth
    - React component that renders the form also controls what happens upon user input (controlled component)

```` javascript

class NameForm extends React.Component {
  constructor(props) {
    super(props);
    this.state = {value: ''};

    this.handleChange = this.handleChange.bind(this);
    this.handleSubmit = this.handleSubmit.bind(this);
  }

  handleChange(event) {
    this.setState({value: event.target.value});
  }

  handleSubmit(event) {
    alert('A name was submitted: ' + this.state.value);
    event.preventDefault();
  }

  render() {
    return (
      <form onSubmit={this.handleSubmit}>
        <label>
          Name:
          <input type="text" value={this.state.value} onChange={this.handleChange} />
        </label>
        <input type="submit" value="Submit" />
      </form>
    );
  }
}
````

  - The value element is set in the form so the displayed value will always be this.state.value
  - handleChange runs on every keystroke to update the React state
  - Controlled component input is always driven by the React state
    - Can now pass this value to other UI elements or reset from other event handlers
  - textarea uses a value that can be written as a single-line input (this.state.value)
  - select creates a dropdown, React uses a value attribute to indicate a root selection
  - To handle multiple input elements, you can add a name attribute to each element and let the handler choose what to do based on the value event.target.name
  - Can be tedious to use controlled components because you have to write an event handler for every way your data can change
    - Uncontrolled components can be an alternative technique for implementing forms