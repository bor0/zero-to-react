# Zero to React

```
npm install
npm start
```
Open `localhost:5000` in your browser.

## Rerender the UI

Convert state data to a concanenated HTML string.

Task: add a checkbox with `include_wordpressdotcom` flag:
```
suggestions( query );
suggestions( { query, include_wordpressdotcom: true });
```
Or use `quantity` or `include_dotblogsubdomain`.

## Rerender the UI (VDOM)

Only do partial re-renders by introducing VDOM and re-rendering only what's changed. Verify that it solves the focus problems.

## Update to React

Do the same thing, but with React elements. Code is much simpler.

## JSX Sugar

Understand that JSX is an optional (and popular) syntactic sugar over `React.createElement`.
Only here we start to need a build step.

## Local state

Rerender just parts of the tree. Maintain local private state of a component.

Task: Display the cost only after clicking "more". Hide it after clicking "less".

## HOCs and data binding

Advanced stuff: reacting to data from a stream, higher-order component abstraction
