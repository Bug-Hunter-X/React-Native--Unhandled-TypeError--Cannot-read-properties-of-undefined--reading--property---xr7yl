# React Native: Handling Unexpected null or undefined values

This repository demonstrates a common error in React Native applications: attempting to access properties of objects that are null or undefined.  The `bug.js` file shows the problematic code, and `bugSolution.js` presents a solution using optional chaining and nullish coalescing.

The error typically manifests as a `TypeError: Cannot read properties of undefined (reading 'property')` and arises from asynchronous operations or state updates.  This example shows how to proactively handle such situations.

## How to Reproduce

1. Clone this repository.
2. Navigate to the directory.
3. Run `npx react-native run-android` (or `npx react-native run-ios`).
4. Observe the error in the console and the corrected behavior after implementing the solution.