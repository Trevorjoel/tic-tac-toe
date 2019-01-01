This is a React Tutorial

Study Notes:

A component takes in parameters, called props (short for “properties”), and returns a hierarchy of views to display via the render method.

The render method returns a description of what you want to see on the screen. React takes the description and displays the result. In particular,
render returns a React element, which is a lightweight description of what to render.

You can put any JavaScript expressions within braces inside JSX. Each React element is a JavaScript object that you can store in a variable or pass around in your program.

React components can have state by setting this.state in their constructors. this.state should be considered as private to a React component that it’s defined in.

State is considered to be private to a component that defines it.

To collect data from multiple children, or to have two child components communicate with each other, you need to declare the shared state in their parent component instead.

The parent component can pass the state back down to the children by using props; this keeps the child components in sync with each other and with the parent component.

 Function components are a simpler way to write components that only contain a render method and don’t have their own state.