# React.js
1 October 2024

React is build around the concept of components, which are the buidling blocks of react applications , these components allow you to break down the user interface into smaller , reusable pieces , that handle there own state and logic .

JSX(JavaScript XML) is the syntax used within REACT to describe what the UI should look like.

What is a component ?
components can be thought of as functions or classes that return a React element ,A component is also self-contained code that represents part of the UI(user interface).

There are two types of components : <b>Functional</b> or <b>class-based</b>

- Functional components: These are your normal JS functions that return JSX. they are used for stateless components.
- Class-based components : These are ES6 classes that extend React.Component and can hold state and lifecycle methods.

LIFECYLE METHODS 4 October 2024

Mounting - the component is being created 

Constructor - it is used for intializing state 

- A special function that will get called whenever a new component is created
  

updating - The component is being re-rendered due to changes in props or state.

Unmouting - The component is being removed from the DOM and cleaned up.
