

# React Multiple Choice Questions

<br/>

## Q. If you want to import just the Component from the React library, what syntax do you use?

- [ ] `import React.Component from 'react'`
- [ ] `import [ Component ] from 'react'`
- [ ] `import Component from 'react'`
- [x] `import { Component } from 'react'`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. If a function component should always render the same way given the same props, what is a simple performance optimization available for it?

- [x] Wrap it in the `React.memo` higher-order component.
- [ ] Implement the `useReducer` Hook.
- [ ] Implement the `useMemo` Hook.
- [ ] Implement the `shouldComponentUpdate` lifecycle method.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How do you fix the syntax error that results from running this code?

```javascript
const person =(firstName, lastName) =>
{
  first: firstName,
  last: lastName
}
console.log(person("Jill", "Wilson"))
```

- [x] Wrap the object in parentheses.
- [ ] Call the function from another file.
- [ ] Add a return statement before the first curly brace.
- [ ] Replace the object with an array.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. If you see the following import in a file, what is being used for state management in the component?

`import React, {useState} from 'react';`

- [x] React Hooks
- [ ] stateful components
- [ ] math
- [ ] class components

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Using object literal enhancement, you can put values back into an object. When you log person to the console, what is the output?

```javascript
const name = 'Rachel';
const age = 31;
const person = { name, age };
console.log(person);
```

- [ ] `{{name: "Rachel", age: 31}}`
- [x] `{name: "Rachel", age: 31}`
- [ ] `{person: "Rachel", person: 31}}`
- [ ] `{person: {name: "Rachel", age: 31}}`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the testing library most often associated with React?

- [ ] Mocha
- [ ] Chai
- [ ] Sinon
- [x] Jest

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. To get the first item from the array ("cooking") using array destructuring, how do you adjust this line?

```javascript
const topics = ['cooking', 'art', 'history'];
```

- [ ] `const first = ["cooking", "art", "history"]`
- [ ] `const [] = ["cooking", "art", "history"]`
- [ ] `const [, first]["cooking", "art", "history"]`
- [x] `const [first] = ["cooking", "art", "history"]`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How do you handle passing through the component tree without having to pass props down manually at every level?

- [ ] React Send
- [ ] React Pinpoint
- [ ] React Router
- [x] React Context

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What should the console read when the following code is run?

```javascript
const [, , animal] = ['Horse', 'Mouse', 'Cat'];
console.log(animal);
```

- [ ] Horse
- [x] Cat
- [ ] Mouse
- [ ] undefined

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the name of the tool used to take JSX and turn it into createElement calls?

- [ ] JSX Editor
- [ ] ReactDOM
- [ ] Browser Buddy
- [x] Babel

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Why might you use useReducer over useState in a React component?

- [ ] when you want to replace Redux
- [x] when you need to manage more complex state in an app
- [ ] when you want to improve performance
- [ ] when you want to break your production app

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which props from the props object is available to the component with the following syntax?

```javascript
<Message {...props} />
```

- [ ] any that have not changed
- [x] all of them
- [ ] child props
- [ ] any that have changed

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Consider the following code from React Router. What do you call :id in the path prop?

```javascript
<Route path="/:id" />
```

- [ ] This is a route modal
- [x] This is a route parameter
- [ ] This is a route splitter
- [ ] This is a route link

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. If you created a component called Dish and rendered it to the DOM, what type of element would be rendered?

```javascript
function Dish() {
  return <h1>Mac and Cheese</h1>;
}

ReactDOM.render(<Dish />, document.getElementById('root'));
```

- [ ] `div`
- [ ] section
- [ ] component
- [x] `h1`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What does this React element look like given the following function? (Alternative: Given the following code, what does this React element look like?)

```javascript
React.createElement('h1', null, "What's happening?");
```

- [ ] `<h1 props={null}>What's happening?</h1>`
- [x] `<h1>What's happening?</h1>`
- [ ] `<h1 id="component">What's happening?</h1>`
- [ ] `<h1 id="element">What's happening?</h1>`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What property do you need to add to the Suspense component in order to display a spinner or loading state?

```javascript
function MyComponent() {
  return (
    <Suspense>
      <div>
        <Message />
      </div>
    </Suspense>
  );
}
```

- [ ] lazy
- [ ] loading
- [x] fallback
- [ ] spinner

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What do you call the message wrapped in curly braces below?

```javascript
const message = 'Hi there';
const element = <p>{message}</p>;
```

- [ ] a JS function
- [ ] a JS element
- [x] a JS expression
- [ ] a JSX wrapper

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What can you use to handle code splitting?

- [ ] `React.memo`
- [ ] `React.split`
- [x] `React.lazy`
- [ ] `React.fallback`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. When do you use `useLayoutEffect`?

- [ ] to optimize for all devices
- [ ] to complete the update
- [ ] to change the layout of the screen
- [x] when you need the browser to paint before the effect runs

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

**Explanation:**
`useLayoutEffect` gets executed _before_ the `useEffect` hook without much concern for DOM mutation. Even though the React hook `useLayoutEffect` is set after the `useEffect` Hook, it gets triggered first!

## Q. What is the difference between the click behaviors of these two buttons (assuming that this.handleClick is bound correctly)?

```javascript
A. <button onClick={this.handleClick}>Click Me</button>
B. <button onClick={event => this.handleClick(event)}>Click Me</button>
```

- [ ] Button A will not have access to the event object on click of the button.
- [ ] Button B will not fire the handler this.handleClick successfully.
- [ ] Button A will not fire the handler this.handleClick successfully.
- [x] There is no difference.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How do you destructure the properties that are sent to the Dish component?

```javascript
function Dish(props) {
  return (
    <h1>
      {props.name} {props.cookingTime}
    </h1>
  );
}
```

- [ ] `function Dish([name, cookingTime]) { return <h1>{name} {cookingTime}</h1>; }`
- [x] `function Dish({name, cookingTime}) { return <h1>{name} {cookingTime}</h1>; }`
- [ ] `function Dish(props) { return <h1>{name} {cookingTime}</h1>; }`
- [ ] `function Dish(...props) { return <h1>{name} {cookingTime}</h1>; }`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. When might you use `React.PureComponent`?

- [ ] when you do not want your component to have props
- [ ] when you have sibling components that need to be compared
- [x] when you want a default implementation of `shouldComponentUpdate()`
- [ ] when you do not want your component to have state

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Why is it important to avoid copying the values of props into a component's state where possible?

- [ ] because you should never mutate state
- [ ] because `getDerivedStateFromProps()` is an unsafe method to use
- [x] because you want to allow a component to update in response to changes in the props
- [ ] because you want to allow data to flow back up to the parent

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the children prop?

- [ ] a property that adds child components to state
- [x] a special property that JSX creates on components that contain both an opening tag and a closing tag, referencing it's contents.
- [ ] a property that lets you set an array as a property
- [ ] a property that lets you pass data to child elements

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which attribute is React's replacement for using innerHTML in the browser DOM?

- [ ] injectHTML
- [x] dangerouslySetInnerHTML
- [ ] weirdSetInnerHTML
- [ ] strangeHTML

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which of these terms commonly describe React applications?

- [x] declarative
- [ ] integrated
- [ ] closed
- [ ] imperative

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. When using webpack, why would you need to use a loader?

- [ ] to put together physical file folders
- [x] to preprocess files
- [ ] to load external data
- [ ] to load the website into everyone's phone

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. A representation of a user interface that is kept in memory and is synced with the "real" DOM is called what?

- [x] virtual DOM
- [ ] DOM
- [ ] virtual elements
- [ ] shadow DOM

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. You have written the following code but nothing is rendering. How do you fix this problem?

```javascript
const Heading = () => {
  <h1>Hello!</h1>;
};
```

- [ ] Add a render function.
- [x] Change the curly braces to parentheses or add a return statement before the `h1` tag.
- [ ] Move the `h1` to another component.
- [ ] Surround the `h1` in a `div`.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. To create a constant in JavaScript, which keyword do you use?

- [x] const
- [ ] let
- [ ] constant
- [ ] var

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What do you call a React component that catches JavaScript errors anywhere in the child component tree?

- [ ] error bosses
- [ ] error catchers
- [ ] error helpers
- [x] error boundaries

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. In which lifecycle method do you make requests for data in a class component?

- [ ] constructor
- [x] componentDidMount
- [ ] componentWillReceiveProps
- [ ] componentWillMount

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. React components are composed to create a user interface. How are components composed?

- [ ] by putting them in the same file
- [x] by nesting components
- [ ] with webpack
- [ ] with code splitting

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. All React components must act like **\_** with respect to their props.

- [ ] monads
- [x] pure functions
- [ ] recursive functions
- [ ] higher-order functions

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is `[e.target.id]` called in this code snippet?

```javascript
const handleChange = (e) => {
  setState((prevState) => ({ ...prevState, [e.target.id]: e.target.value }));
};
```

- [ ] a computed property name
- [ ] a set value
- [x] a dynamic key
- [ ] a JSX code string

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the name of this component?

```javascript
class Clock extends React.Component {
  render() {
    return <h1>Look at the time: {time}</h1>;
  }
}
```

- [x] Clock
- [ ] It does not have a name prop.
- [ ] React.Component
- [ ] Component

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is sent to an `Array.map()` function?

- [x] a callback function that is called once for each element in the array
- [ ] the name of another array to iterate over
- [ ] the number of times you want to call the function
- [ ] a string describing what the function should do

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Why is it a good idea to pass a function to `setState` instead of an object?

- [ ] It provides better encapsulation.
- [ ] It makes sure that the object is not mutated.
- [ ] It automatically updates a component.
- [x] `setState` is asynchronous and might result in out of sync values.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

**Explanation:** Because `this.props` and `this.state` may be updated asynchronously, you should not rely on their values for calculating the next state.

## Q. What package contains the render() function that renders a React element tree to the DOM?

- [ ] `React`
- [x] `ReactDOM`
- [ ] `Render`
- [ ] `DOM`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How do you set a default value for an uncontrolled form field?

- [ ] Use the `value` property.
- [x] Use the `defaultValue` property.
- [ ] Use the `default` property.
- [ ] It assigns one automatically.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What do you need to change about this code to get it to run?

```js
const clock = (props) => {
  return <h1>Look at the time: {props.time}</h1>;
};
```

- [ ] Add quotes around the return value
- [ ] Remove `this`
- [ ] Remove the render method
- [x] Capitalize `clock`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

**Explanation:** In JSX, lower-case tag names are considered to be HTML tags.

## Q. Which Hook could be used to update the document's title?

- [x] `useEffect(function updateTitle() { document.title = name + ' ' + lastname; });`
- [ ] `useEffect(() => { title = name + ' ' + lastname; });`
- [ ] `useEffect(function updateTitle() { name + ' ' + lastname; });`
- [ ] `useEffect(function updateTitle() { title = name + ' ' + lastname; });`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which function from React can you use to wrap Component imports to load them lazily?

- [ ] `fallback`
- [ ] `split`
- [x] `lazy`
- [ ] `memo`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How do you invoke setDone only when component mounts, using hooks?

```javascript
function MyComponent(props) {
  const [done, setDone] = useState(false);

  return <h1>Done: {done}</h1>;
}
```

- [ ] `useEffect(() => { setDone(true); });`
- [x] `useEffect(() => { setDone(true); }, []);`
- [ ] `useEffect(() => { setDone(true); }, [setDone]);`
- [ ] `useEffect(() => { setDone(true); }, [done, setDone]);`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Currently, `handleClick` is being called instead of passed as a reference. How do you fix this?

```javascript
<button onClick={this.handleClick()}>Click this</button>
```

- [ ] `<button onClick={this.handleClick.bind(handleClick)}>Click this</button>`
- [ ] `<button onClick={handleClick()}>Click this</button>`
- [x] `<button onClick={this.handleClick}>Click this</button>`
- [ ] `<button onclick={this.handleClick}>Click this</button>`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which answer best describes a function component?

- [ ] A function component is the same as a class component.
- [x] A function component accepts a single props object and returns a React element.
- [ ] A function component is the only way to create a component.
- [ ] A function component is required to create a React component.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which library does the `fetch()` function come from?

- [ ] FetchJS
- [ ] ReactDOM
- [x] No library. `fetch()` is supported by most browsers.
- [ ] React

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What will happen when this useEffect Hook is executed, assuming name is not already equal to John?

```javascript
useEffect(() => {
  setName('John');
}, [name]);
```

- [ ] It will cause an error immediately.
- [ ] It will execute the code inside the function, but only after waiting to ensure that no other component is accessing the name variable.
- [x] It will update the value of name once and not run again until name is changed from the outside.
- [ ] It will cause an infinite loop.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which choice will not cause a React component to rerender?

- [ ] if the component calls `this.setState(...)`
- [ ] the value of one of the component's props changes
- [ ] if the component calls `this.forceUpdate()`
- [x] one of the component's siblings rerenders

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. You have created a new method in a class component called handleClick, but it is not working. Which code is missing?

```javascript
class Button extends React.Component{

  constructor(props) {
    super(props);
    // Missing line
  }

  handleClick() {...}
}
```

- [ ] `this.handleClick.bind(this);`
- [ ] `props.bind(handleClick);`
- [ ] `this.handleClick.bind();`
- [x] `this.handleClick = this.handleClick.bind(this);`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. React does not render two sibling elements unless they are wrapped in a fragment. Below is one way to render a fragment. What is the shorthand for this?

```javascript
<React.Fragment>
  <h1>Our Staff</h1>
  <p>Our staff is available 9-5 to answer your questions</p>
</React.Fragment>
```

- [ ] A

```javascript
<...>
  <h1>Our Staff</h1>
  <p>Our staff is available 9-5 to answer your questions</p>
</...>
```

- [ ] B

```javascript
<//>
  <h1>Our Staff</h1>
  <p>Our staff is available 9-5 to answer your questions</p>
<///>
```

- [x] C

```javascript
<>
  <h1>Our Staff</h1>
  <p>Our staff is available 9-5 to answer your questions</p>
</>
```

- [ ] D

```javascript
<Frag>
  <h1>Our Staff</h1>
  <p>Our staff is available 9-5 to answer your questions</p>
</Frag>
```

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. If you wanted to display the count state value in the component, what do you need to add to the curly braces in the `h1`?

```javascript
class Ticker extends React.component {
  constructor(props) {
    super(props);
    this.state = { count: 0 };
  }
  render() {
    return <h1>{}</h1>;
  }
}
```

- [x] this.state.count
- [ ] count
- [ ] state
- [ ] state.count

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Per the following code, when is the Hello component assigned to greeting?

```javascript
const greeting = isLoggedIn ? <Hello /> : null;
```

- [ ] never
- [x] when `isLoggedIn` is true
- [ ] when a user logs in
- [ ] when the Hello function is called

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. In the following code block, what type is orderNumber?

```javascript
ReactDOM.render(<Message orderNumber="16" />, document.getElementById('root'));
```

- [x] string
- [ ] boolean
- [ ] object
- [ ] number

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. You have added a style property to the `h1` but there is an unexpected token error when it runs. How do you fix this?

```javascript
const element = <h1 style={ backgroundColor: "blue" }>Hi</h1>;
```

- [ ] `const element = <h1 style="backgroundColor: "blue""}>Hi</h1>;`
- [x] `const element = <h1 style={{backgroundColor: "blue"}}>Hi</h1>;`
- [ ] `const element = <h1 style={blue}>Hi</h1>;`
- [ ] `const element = <h1 style="blue">Hi</h1>;`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which function is used to update state variables in a React class component?

- [ ] `replaceState`
- [ ] `refreshState`
- [ ] `updateState`
- [x] `setState`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Consider the following component. What is the default color for the star?

```javascript
const Star = ({ selected = false }) => <Icon color={selected ? 'red' : 'grey'} />;
```

- [ ] black
- [ ] red
- [x] grey
- [ ] white

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the difference between the click behaviors of these two buttons(assuming that this.handleClick is not bound correctly)

```javascript
  A. <button onClick=this.handleClick>Click Me</button>
  B. <button onClick={event => this.handleClick(event)}>Click Me</button>
```

- [ ] `Button A will not have access to the event object on click of the button`
- [x] `Button A will not fire the handler this.handleClick successfully`
- [ ] `There is no difference`
- [ ] `Button B will not fire the handler this.handleClick successfully`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How would you add to this code, from React Router, to display a component called About?

```javascript
<Route path="/:id" />
```

- [x] A

```javascript
<Route path="/:id">
  {' '}
  <About />
</Route>
```

- [ ] B

```javascript
<Route path="/tid" about={Component} />
```

- [ ] C

```javascript
<Route path="/:id" route={About} />
```

- [ ] D

```javascript
<Route>
  <About path="/:id" />
</Route>
```

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which class-based component is equivalent to this function component?

```javascript
const Greeting = ({ name }) => <h1>Hello {name}!</h1>;
```

- [ ] A

```javascript
class Greeting extends React.Component {
  constructor() {
    return <h1>Hello {this.props.name}!</h1>;
  }
}
```

- [ ] B

```javascript
class Greeting extends React.Component {
  <h1>Hello {this.props.name}!</h1>;
}
```

- [x] C

```javascript
class Greeting extends React.Component {
  render() {
    return <h1>Hello {this.props.name}!</h1>;
  }
}
```

- [ ] D

```javascript
class Greeting extends React.Component {
  render({ name }) {
    return <h1>Hello {name}!</h1>;
  }
}
```

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Give the code below, what does the second argument that is sent to the render function describe?

```javascript
ReactDOM.render(
  <h1>Hi<h1>,
    document.getElementById('root')
)
```

- [x] where the React element should be added to the DOM
- [ ] where to call the function
- [ ] where the root component is
- [ ] where to create a new JavaScript file

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Why should you use React Router's Link component instead of a basic `<a>` tag in React?

- [ ] The link component allows the user to use the browser's `Back` button.
- [ ] There is no difference--the `Link` component is just another name for the `<a>` tag.
- [ ] The `<a>` tag will cause an error when used in React.
- [x] The `<a>` tag triggers a full page reload, while the `Link` component does not.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the first argument, `x`, that is sent to the `createElement` function?

```javascript
React.createElement(x, y, z);
```

- [x] the element that should be created
- [ ] the order in which this element should be placed on the page
- [ ] the properties of the element
- [ ] data that should be displayed in the element

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which class-based lifecycle method would be called at the same time as this effect Hook?

```javascript
useEffect(() => {
  // do things
}, []);
```

- [ ] componentWillUnmount
- [x] componentDidMount
- [ ] render
- [ ] componentDidUpdate

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the name of the base component of this component?

```javascript
class Comp extends React.Component {
  render() {
    return <h1>Look at the time: {time}</h1>;
  }
}
```

- [ ] Comp
- [ ] h1
- [ ] React.Component
- [x] Component

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. When using a portal, what is the first argument?

```javascript
ReactDOM.createPortal(x, y);
```

- [ ] the current state
- [x] the element to render
- [ ] the App component
- [ ] the page

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is `setCount`?

```javascript
const [count, setCount] = useState(0);
```

- [ ] the initial state value
- [ ] a variable
- [ ] a state object
- [x] a function to update the state

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the use of map function below?

```javascript
const database = [{ data: 1 }, { data: 2 }, { data: 3 }];
database.map((user) => <h1>{user.data}</h1>);
```

- [ ] gives a map of all the entries in database
- [x] returns a heading tag for every entry in the database containing it's data
- [ ] returns one heading tag for all the entries in database
- [ ] checks which entry in the database is suitable for heading tag

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Describe what is happening in this code?

```javascript
const { name: firstName } = props;
```

- [ ] It is creating a new object that contains the same name property as the props object.
- [ ] It is assigning the value of the props object's firstName property to a constant called name.
- [ ] It is retrieving the value of props.name.firstName.
- [x] It is assigning the value of the props object's name property to a constant called firstName.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is wrong with this code?

```javascript
const MyComponent = ({ names }) => (
  <h1>Hello</h1>
  <p>Hello again</p>
);
```

- [ ] React components cannot be defined using functions.
- [x] React does not allow components to return more than one element.
- [ ] The component needs to use the return keyword.
- [ ] String literals must be surrounded by quotes.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. When using a portal, what is the second argument?

```javascript
ReactDOM.createPortal(x, y);
```

- [ ] the App component
- [ ] the page
- [ ] the current state
- [x] the DOM element that exists outside of the parent component

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Given this code, what will be printed in the `<div>` tag?

```javascript
const MyComponent = ({ children }) => (
  <div>{children.length}</div>
);
...
<MyComponent>
<p>
  Hello <span>World!</span>
</p>
<p>Goodbye</p>
</MyComponent>
```

- [ ] It will produce an error saying "cannot read property "length" of undefined."
- [ ] 1
- [ ] undefined
- [x] 2

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is this pattern called?

```javascript
const [count, setCount] = useState(0);
```

- [ ] object destructuring
- [x] array destructuring
- [ ] spread operating
- [ ] code pushing

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the first file loaded by the browser in a basic React project?

- [ ] src/App.js
- [ ] src/index.js
- [ ] public/manifest.json
- [x] public/index.html

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. The code below is rendering nothing and generate this error: "ReactDOM is not defined." How do you fix this issue?

```javascript
import React from 'react';
import { createRoot } from 'reactjs-dom';

const element = <h1>Hi</h1>;
// Note: error on the line below
const root = ReactDOM.createRoot(document.getElementById('root'));

root.render(element);
```

- [x] `createRoot(document.getElementById("root"));`
- [ ] `ReactDOM(element, document.getElementById("root"));`
- [ ] `renderDOM(element, document.getElementById("root"));`
- [ ] `DOM(element, document.getElementById("root"));`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. In this component, how do you display whether the user was logged in or not?

```javascript
render() {
  const isLoggedIn = this.state.isLoggedIn;
  return (
    <div>
      The user is:
    </div>
  );
}
```

- [ ] `The user is loggedIn ? logged in : not logged in.`
- [ ] Write a function to check the login status.
- [ ] `The user is {isLoggedIn = "no"}.`
- [x] `The user is {isLoggedIn ? "logged in." : "not logged in"}.`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. You are rendering a list with React when this warning appears in the console: "Warning: Each child in a list should have a unique 'key' prop." How do you fix this issue?

- [ ] Add a key prop with the same value to each item in the list
- [ ] Clear the console warnings
- [ ] Use the UseId hook to generate a unique key for each element in the list
- [x] When iterating over the list items, add a unique property to each list item.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How would you generate the boilerplate code for a new app that you are building to collect underpants?

- [ ] npm create-react-app collect-underpants
- [ ] npx start-app collect-underpants
- [ ] react new collect-underpants
- [x] npx create-react-app collect-underpants

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Add the code that will fire the photon torpedoes when the button is clicked.

```javascript
class StarTrekkin extends React.Component {
  firePhotonTorpedoes(e) {
    console.log('pew pew');
  }
  render() {
    return; // Missing code
  }
}
```

- [ ] `<button onClick={firePhotonTorpedoes()}>Pew Pew</button>`
- [ ] `<button onClick={firePhotonTorpedoes}>Pew Pew</button>`
- [ ] `<button onClick={this.firePhotonTorpedoes()}>Pew Pew</button>`
- [x] `<button onClick={this.firePhotonTorpedoes}>Pew Pew</button>`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the process of deciding whether an update is necessary?

- [ ] shadow DOM
- [ ] fiber
- [x] reconciliation
- [ ] setting state

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. React is an open-source project but is maintained by which company?

- [ ] Intuit
- [ ] Twitter
- [x] Facebook
- [ ] Snapchat

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What command can you use to generate a React project?

- [ ] react-starter
- [x] create-react-app
- [ ] react-gen
- [ ] react-start

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the browser extension called that React developers use to debug applications?

- [x] React Developer Tools
- [ ] React Tooling Add-on
- [ ] React Codewatch
- [ ] React Debug

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which tool is not part of Create React App?

- [ ] React
- [x] jQuery
- [ ] webpack
- [ ] ReactDOM

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the JavaScript syntax extension that is commonly used to create React elements?

- [ ] HTML
- [ ] JavaScriptX
- [x] JSX
- [ ] React JavaScript

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How might you check property types without using Flow or TypeScript?

- [ ] Check Manually.
- [ ] Use `prop-helper`.
- [x] use `prop-types`.
- [ ] user `checker-types`.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How do you add an id of heading to the following h1 element?

```javascript
let dish = <h1>Mac and Cheese</h1>;
```

- [ ] `let dish = <h1 id={heading}>Mac and Cheese</h1>;`
- [x] `let dish = <h1 id="heading">Mac and Cheese</h1>;`
- [ ] `let dish = <h1 id:"heading">Mac and Cheese</h1>;`
- [ ] `let dish = <h1 class="heading">Mac and Cheese</h1>;`

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What value of button will allow you to pass the name of the person to be hugged?

```javascript
class Huggable extends React.Component {
  hug(id) {
    console.log("hugging " + id);
  }
  render() {
    let name = "kitten";
    let button = // Missing code
    return button;
  }
}
```

- [ ] `<button onClick={(name) => this.hug(name)}>Hug Button</button>;`
- [ ] `<button onClick={this.hug(e, name)}>Hug Button</button>;`
- [ ] `<button onClick={(e) => hug(name, e)}>Hug Button</button>;`
- [x] `<button onClick={(e) => this.hug(name, e)}>Hug Button</button>;`

**Explanation:**
This question test knowledge of react class components. You need to use `this` in order to call methods declared inside class components.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What syntax do you use to create a component in React?

- [ ] a generator
- [x] a function or a class
- [ ] a service worker
- [ ] a tag

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

**Explanation:**
React Components are like functions that return HTML elements. Components are independent and reusable bits of code. They serve the same purpose as JavaScript functions, but work in isolation and return HTML. Components come in two types, Class components and Function components.

## Q. You want to disable a button so that it does not emit any events onClick. Which prop do you use to acomplish this?

- [ ] onBlur
- [ ] onPress
- [ ] defaultValue
- [x] disabled

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. In this function, which is the best way to describe the Dish component?

```javascript
function Dish() {
  return (
    <>
      <Ingredient />
      <Ingredient />
    </>
  );
}
```

- [ ] child component
- [x] parent component
- [ ] nested component
- [ ] sibling component

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. When does the componentDidMount function fire?

- [x] right after the component is added to the DOM
- [ ] before the component is added to the DOM
- [ ] right after the component is updated
- [ ] right after an API call

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What might you use webpack for in React development?

- [ ] to fetch remote dependencies used by your app
- [x] to split your app into smaller chunks that can be more easily loaded by the browser
- [ ] to format your code so that it is more readable
- [ ] to ensure your app is not vulnerable to code injection

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. When using the React Developer Tools Chrome extension, what does it mean if the React icon is red?

- [x] You are using the development build of React.
- [ ] You are using the production build of React.
- [ ] You are using webpack.
- [ ] You are using Create React App.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How would you modify the constructor to fix this error: "ReferenceError: Must call super constructor in derived class before accessing 'this'..."?

```javascript
class TransIsBeautiful extends React.Component {
  constructor(props){
  // Missing line
  console.log(this) ;
  }
  ...
}
```

- [ ] render(props);
- [x] super(props);
- [ ] super(this);
- [ ] this.super();

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which language can you not use with React?

- [x] Swift.
- [ ] JSX.
- [ ] Javascipt.
- [ ] TypeScript.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. This code is part of an app that collects Pokemon. How would you print the list of the ones collected so far?

```javascript
constructor(props) {
    super(props);
    this.state = {
        pokeDex: []
    };
}
```

- [ ] console.log(props.pokeDex);
- [ ] console.log(this.props.pokeDex);
- [ ] console.log(pokeDex);
- [x] console.log(this.state.pokeDex);

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What would be the result of running this code?

```javascript
function add(x = 1, y = 2) {
  return x + y;
}

add();
```

- [ ] null
- [x] 3
- [ ] 0
- [ ] undefined

![image](https://user-images.githubusercontent.com/62549240/160531605-bf8790d5-5eb9-4291-a9bd-4232f2fd7b6e.png?raw=png)

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Why might you use a React.ref?

- [ ] to refer to another JS file
- [ ] to bind the function
- [ ] to call a function
- [x] to directly access the DOM node

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What pattern is being used in this code block?

```javascript
const { tree, lake } = nature;
```

- [ ] function defaults
- [ ] array destructuring
- [ ] PRPL pattern
- [x] destructuring assignment

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. How would you correct this code block to make sure that the sent property is set to the Boolean value false?

```javascript
ReactDom.render(
  <Message sent=false />,
  document.getElementById("root")
);
```

- [x] A

```javascript
<Message sent={false} />,
```

- [ ] B

```javascript
ReactDom.render(<Message sent="false" />, document.getElementById('root'));
```

- [ ] C

```javascript
<Message sent="false" />,
```

- [ ] D

```javascript
ReactDom.render(<Message sent="false" />, document.getElementById('root'));
```

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. This code is part of an app that collects Pokemon. The useState hook below is a piece of state holding onto the names of the Pokemon collected so far. How would you access the collected Pokemon in state?

```javascript
const PokeDex = (props) => {
  const [pokeDex, setPokeDex] = useState([]);
  /// ...
};
```

- [ ] props.pokeDex
- [ ] this.props.pokeDex
- [ ] setPokeDex()
- [x] pokeDex

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. When using a portal, what is the second argument?

```javascript
ReactDOM.createPortal(x, y);
```

- [ ] the current state
- [ ] the rendered element
- [ ] the App component
- [x] the DOM element that exists outside of the parent component

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What would you pass to the onClick prop that wil allow you to pass the initName prop into the greeet handler?

```javascript
const Greeting = ({ initName }) => {
  const greet = (name) => console.log("Hello, " + name + "!");
  return <button onClick={ ... }>Greeting Button </button>
}
```

- [ ] hug
- [ ] this.hug(initName)
- [ ] (name) => this.hug(name)
- [x] () => hug(initName)

Explanation: Apparently the question misstyped `greet` as `hug`. Putting this aside, we can still learn from this question.

- In a function, the global object is the default binding for `this`. In a browser window the global object is [object Window].
  This is a functional Component, so `this` from `this.hug` actually refers to browser window.
  Since it is a functional component, we can directly refer to hug without using `this`.
- To pass a handler to onClick, we should always pass a function rather than execute a function. So we need to use callback here.
  `initName` is available in Greeting's function scope, so we can directly supply as an argument to hug().

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the name of the compiler used to transform JSX into JavaScript?

- [x] Babel
- [ ] JSX Editor
- [ ] Browser Buddy
- [ ] ReactDOM

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which hook is used to prevent a function from being recreated on every component render?

- [x] useCallback
- [ ] useMemo
- [ ] useRef
- [ ] useTransition

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Why might you use the `useRef` hook?

- [ ] To bind the function
- [ ] To call a function
- [x] To directly access a DOM
- [ ] To refer to another JS file

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which of the following is required to use React?

- [x] JavaScript
- [ ] React Router
- [ ] Redux
- [ ] Prop-Types

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the correct way to get a value from context?

- [ ] const value = useContext(MyContext.Consumer)
- [ ] const value = useContext(MyContext.Provider)
- [x] const value = useContext(MyContext)
- [ ] const value = useContext({value: "intiial value"})

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Why is ref used?

- [ ] to bind function
- [ ] to call function
- [x] to directly access DOM node
- [ ] to refer to another JS file

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Choose the method which should be overridden to stop the component from updating?

- [ ] componentDidMount
- [ ] componentDidUpdate
- [ ] willComponentUpdate
- [x] shouldComponentUpdate

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is the functionality of a “webpack” command?

- [x] Runs react local development server
- [ ] Transfers all JS files to down into one file
- [ ] A module builder
- [ ] None of the above

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Choose the method which is not a part of ReactDOM?

- [ ] ReactDOM.createPortal()
- [ ] ReactDOM.hydrate()
- [x] ReactDOM.destroy()
- [ ] ReactDOM.findDOMnode()

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. In react, the key should be?

- [x] Unique among his siblings
- [ ] Unique in DOM
- [ ] Does not requires to be unique
- [ ] all of the above

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Which company developed ReactJS?

- [ ] Google
- [x] Meta (ex Facebook)
- [ ] Apple
- [ ] Twitter

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Choose the library which is most often associated with react?

- [ ] Chai
- [ ] Sinon
- [x] Jest
- [ ] Mocha

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What of the following is used in React.js to increase performance?

- [ ] Original DOM
- [x] Virtual DOM
- [ ] Both of the above
- [ ] None of the above

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Among The following options, choose the one which helps react for keeping their data uni-directional?

- [ ] DOM
- [x] flux
- [ ] JSX
- [ ] Props

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. What is this pattern called?

```javascript
const [count, setCount] = useState(0);
```

- [ ] code pushing
- [ ] object destructuring
- [ ] spread operating
- [x] array destructuring

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. This code is part of an app that collects Pokemon. The useState hook below is a piece of state holding onto the names of the Pokemon collected so far. How would you access the collected Pokemon in state?

```javascript
const PokeDex = (props) => {
  const [pokeDex, setPokeDex] = useState([]);
  //...
};
```

- [x] pokeDex
- [ ] this.props.pokeDex
- [ ] setPokeDex()
- [ ] props.pokeDex

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>
