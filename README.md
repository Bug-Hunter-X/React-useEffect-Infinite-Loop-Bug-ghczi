# React useEffect Infinite Loop Bug

This repository demonstrates a common error in React's `useEffect` hook: an infinite loop caused by a missing dependency in the dependency array. 

The `bug.js` file contains the buggy code, while `bugSolution.js` provides the corrected version. The issue arises when the `useEffect` hook's dependency array is missing or incorrect, leading to the effect running repeatedly and creating an infinite loop.