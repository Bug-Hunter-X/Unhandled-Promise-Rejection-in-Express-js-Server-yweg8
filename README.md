# Unhandled Promise Rejection in Express.js Server

This repository demonstrates a common error in Node.js applications: unhandled promise rejections in asynchronous code. The server might crash or produce unexpected results without proper error handling.

## Bug

The `bug.js` file contains an Express.js server that simulates an asynchronous operation that might throw an error.  If the random number generated is less than 0.5, an error is thrown, but it's not handled properly, leading to an unhandled promise rejection.

## Solution

The `bugSolution.js` file demonstrates how to properly handle this error using `try...catch` blocks and promises.