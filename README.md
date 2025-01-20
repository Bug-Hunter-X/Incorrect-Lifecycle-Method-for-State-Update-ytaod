# React Lifecycle Method Bug

This repository demonstrates a common bug in React applications: using the deprecated `componentWillReceiveProps` lifecycle method to update state.  This can lead to infinite render loops and unexpected behavior.

The `BuggyComponent.jsx` file shows the incorrect implementation, while `FixedComponent.jsx` demonstrates the correct approach using `componentDidUpdate` or `useEffect`.

## How to reproduce

1. Clone the repository.
2. Run `npm install`.
3. Run `npm start`.
4. Observe the behavior of the buggy component, then compare it with the fixed version.