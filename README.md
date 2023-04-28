# React-Review-

#### What is a "data model", and how does it relate to the DOM in a front-end application?

The data model and the DOM are related in that the data model often serves as the source of data for the web application, and the DOM is the visual representation of that data on the web page. 

#### What is a "framework?" And how does it differ from a "library?"

A framework is a pre-written code that provides a structure or a set of guidelines for developers to build upon. It's like a skeleton or a foundation that provides a basic structure for an application or a software system. A library is a collection of pre-written code that provides specific functionality that developers can use in their applications. Unlike a framework, a library doesn't provide a structure or a set of guidelines for building an application; it's usually a set of functions or classes that developers can use to perform specific tasks in their applications.

#### Why should we consider using a framework over vanilla JS like you have been doing in mods 1 and 2?

Frameworks provide a set of pre-built components, functions, and tools that developers can use to build their applications quickly and easily. This can save time and increase productivity. Frameworks enforce a set of standards and best practices that ensure code consistency across an application. This can lead to cleaner, more maintainable code and make it easier for other developers to understand and work on the codebase. Frameworks are designed to handle complex applications with ease. They provide a structure that can accommodate changes and additions as the application grows over time.

#### What is a "component" in React? Why is it useful to have components?

In React, a component is a modular and reusable piece of code that encapsulates a specific functionality or feature of a user interface. A component can be thought of as a building block of a React application, and it can be composed of other components to create more complex and sophisticated user interfaces.

#### What is JSX?

JSX is a syntax extension for JavaScript that allows developers to write HTML-like code in their JavaScript code. It's often used in conjunction with React to describe the user interface of a component.

#### What are React "props?"

Props are a mechanism for passing data and configuration to a component. They are essentially arguments that are passed to a component when it is created and determine the behavior and appearance of that component.

#### What is React "state?"

A React "state" is a JavaScript object that holds data that can change over time and affects the rendering of a component. A component's state can be thought of as its internal memory or representation of its current state or condition.

Unlike props, which are passed down from a parent component and are read-only, state is managed within a component and can be updated using the setState method provided by React. When a component's state changes, React automatically re-renders the component to reflect the new state.

#### What does "data down, actions up" mean in React?

A parent component passes data down to its child components via props, and the child components communicate with the parent component by invoking callbacks that are passed down as props.
