# React 2
- Conditional rendering in React allows components to render different content based on certain conditions or states.
- Common techniques for conditional rendering include the use of conditional statements (if/else), the ternary operator, and logical && operator.
- Conditional rendering is crucial for creating dynamic and interactive user interfaces.

# Reading Notes on React - Lists & Keys

## React - Lists & Keys
- In React, rendering lists of data is a common task.
- When rendering lists, each item should have a unique "key" prop to help React efficiently update and re-render elements.
- Using the `.map()` function to iterate over arrays and create React elements for each item is a common approach.

# Reading Notes on React - Forms

## React - Forms
- React allows developers to build controlled and uncontrolled forms.
- Controlled forms are managed by React state, providing real-time data validation and control over form input elements.
- Handling form submission typically involves preventing the default behavior of the browser and sending data to a server or performing client-side actions.

# Reading Notes on React - Lifting State

## React - Lifting State
- "Lifting state up" is a React pattern where state that is shared between components is moved to a common ancestor component.
- This pattern promotes data sharing and synchronization between components that need access to the same data.
- Parent components pass down state and callback functions as props to child components, enabling them to interact with the shared data.

# Reading Notes on React - Composition vs Inheritance

## React - Composition vs Inheritance
- React favors composition over inheritance when it comes to building component hierarchies.
- Composition involves creating components that reuse other components by rendering them or wrapping them in different ways.
- Inheritance can lead to tight coupling and inflexible component hierarchies, while composition encourages flexibility and reusability.

# Reading Notes on Thinking in React

## Thinking in React
- "Thinking in React" is a design approach to building React applications.
- It involves breaking down the user interface into a hierarchy of components, starting with a single root component.
- Key steps in thinking in React include identifying the component hierarchy, determining the state and props needed, and sketching a static version of the UI.

These reading notes cover various aspects of React, from conditional rendering and working with lists to handling forms, lifting state, and understanding the principles of composition versus inheritance. Additionally, "Thinking in React" is an essential concept that guides the design and organization of React applications.