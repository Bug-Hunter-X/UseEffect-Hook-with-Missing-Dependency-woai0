# React useEffect Hook Bug

This repository demonstrates a common bug related to the `useEffect` hook in React.  The bug involves a missing dependency, causing unintended re-renders.

## The Problem

The `useEffect` hook, when used without specifying dependencies, runs after every render, including the initial render. This is often unintended behavior leading to performance issues or unexpected side effects. 

The `bug.js` file contains the buggy code. 

## The Solution

The `bugSolution.js` file provides a corrected version with the correct dependency array, ensuring the effect runs only when necessary (in this case, only once on mount).
