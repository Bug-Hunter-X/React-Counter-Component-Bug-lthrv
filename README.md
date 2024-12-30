# React Counter Component Bug
This repository demonstrates a common bug in React components involving the use of the `useState` hook for managing state. The component includes an increment and a decrement function, but the decrement function contains an error that leads to unexpected behavior.

## Bug Description
The `decrement` function subtracts 2 instead of 1 from the counter. This is a simple but easily missed mistake that can be hard to debug without careful inspection.

## Solution
The solution simply corrects the `decrement` function to subtract 1 instead of 2.  This ensures the counter behaves as expected.