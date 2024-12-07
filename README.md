# Unhandled Division by Zero Error in TypeScript

This repository demonstrates an example of an unhandled division by zero error in TypeScript. The `bug.ts` file contains the buggy code, which throws an error when attempting to divide by zero. The `bugSolution.ts` file provides a solution by handling the potential error using a `try...catch` block.

## Bug Description

The `divide` function correctly throws an error if the divisor is zero. However, the calling code doesn't handle the error, causing the program to crash. This is a common issue and can lead to unexpected program termination.

## Solution

The solution involves using a `try...catch` block to gracefully handle the error. The `try` block attempts to execute the potentially error-prone code, while the `catch` block handles the error if it occurs. This allows the program to continue running even if an error happens.