# Unnecessary Re-renders in React useEffect Hook

This repository demonstrates a common issue in React applications where the `useEffect` hook causes unnecessary re-renders.  The `useEffect` hook in `bug.js` runs after every render, leading to performance issues and excessive console logging.

The solution in `bugSolution.js` demonstrates how to use the optional dependency array to optimize the effect's execution. 