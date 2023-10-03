# ES6 Syntax and Feature Overview

ES6, also known as ECMAScript 2015, introduced key enhancements to JavaScript, including `let` and `const` for variable declarations, arrow functions, template literals, destructuring, spread/rest operators, classes, modules, promises, async/await, and data structures like Maps and Sets. These features modernized JavaScript, improving code readability and maintainability.

# React

## React - Hello World

React, a JavaScript library for building UIs, starts with a simple "Hello World" example. Set up React, create a component, and render it:

```jsx
import React from 'react';
import ReactDOM from 'react-dom';

function HelloWorld() {
  return <div>Hello World!</div>;
}

ReactDOM.render(<HelloWorld />, document.getElementById('root'));
```

## React - JSX

JSX in React lets you embed HTML-like code within JavaScript. It simplifies creating React elements:

```jsx
const element = <h1>Hello, JSX!</h1>;
```

JSX also allows embedding JavaScript expressions inside curly braces.

## React - Rendering Elements

React elements represent UI components. Use `ReactDOM.render()` to render elements into the DOM:

```jsx
const element = <h1>Hello, React!</h1>;
ReactDOM.render(element, document.getElementById('root'));
```

Elements are immutable; to update UI, create new elements and re-render.

## React - Components & Props

React components are reusable UI pieces. Props pass data from parent to child components:

```jsx
function Greeting(props) {
  return <h1>Hello, {props.name}!</h1>;
}

<Greeting name="John" />
```

## React - State & Lifecycle

State in React allows components to manage data. Use `setState()` to update it. Stateful components enable dynamic UI updates:

```jsx
class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }

  incrementCount() {
    this.setState({ count: this.state.count + 1 });
  }

  render() {
    return (
      <div>
        <p>Count: {this.state.count}</p>
        <button onClick={() => this.incrementCount()}>Increment</button>
      </div>
    );
  }
}
```

## React - Handling Events

React simplifies event handling:

```jsx
class Button extends React.Component {
  handleClick() {
    alert('Button clicked!');
  }

  render() {
    return <button onClick={() => this.handleClick()}>Click me</button>;
  }
}
```

# Tailwind CSS

## Utility First CSS

Tailwind CSS is a utility-first framework. Apply utility classes directly to HTML elements for rapid and consistent styling:

```html
<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
  Button
</button>
```

## Tailwind in 15 minutes

Quickly start with Tailwind CSS:

1. **Setup:** Install Tailwind and create an HTML file.
2. **HTML Structure:** Write your page structure.
3. **Add Classes:** Apply Tailwind CSS classes to style elements.
4. **Customization:** Tailwind is highly customizable.
5. **Build and Run:** Build CSS, include it, and view your styled page.

Tailwind CSS enables efficient web development with its utility-first approach.
