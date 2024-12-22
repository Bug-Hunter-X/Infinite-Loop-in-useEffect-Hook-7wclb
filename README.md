# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React applications: an infinite loop caused by incorrect usage of the `useEffect` hook.

The `bug.js` file contains the buggy code, where the `useEffect` hook updates the `count` state, causing the component to re-render infinitely. The `bugSolution.js` file provides a corrected version with explanations.