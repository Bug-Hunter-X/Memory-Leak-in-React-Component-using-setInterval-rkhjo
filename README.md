# React setInterval Memory Leak
This repository demonstrates a common bug in React applications involving the use of `setInterval` within a `useEffect` hook without proper cleanup.  This leads to a memory leak as the interval continues to run even after the component unmounts.
The `bug.js` file shows the erroneous code, while `bugSolution.js` provides the corrected implementation.