
describe hoisting
describe closures
describe the event loop
describe lexical scope
describe some es6 features
  - arrow functions
  - modules (IIFE under the hood)

describe IEFEs
  - avoid polluting the namespace
  - clean code
  - async inside sync

differences between arrow functions and `function` functions
  - this binding
  - cleaner code
  - `arguments` object (`function` functions have it, arrow functions don't)

callbacks / promises 
- Callback functions in JavaScript are functions that can be passed to other functions as a parameter.
- They are also known as higher-order functions and are called (or executed) inside the function they were passed to. 
- Callbacks are need due to the non-blocking nature of JS.
- Nested callbacks -> callback hell / pyramid of doom.
- Promises hold the eventual result of an asynchronous operation. When an asynchronous operation completes, it can either result in a value or an error. 
- The three states a promise can hold are Pending, Fulfilled, or Rejected.
