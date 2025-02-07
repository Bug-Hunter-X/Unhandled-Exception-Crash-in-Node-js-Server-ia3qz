# Unhandled Exception in Node.js Server

This repository demonstrates a common error in Node.js applications: unhandled exceptions leading to server crashes.  The `bug.js` file contains a server that, when accessing the `/error` route, throws an unhandled exception causing the server to terminate abruptly.  The `bugSolution.js` file presents a corrected version with proper error handling to gracefully manage unexpected errors.

## Steps to Reproduce

1. Clone the repository.
2. Navigate to the repository's directory.
3. Run `node bug.js`.
4. Access `http://localhost:3000/error` in your browser.
5. Observe the server crashing.
6. Run `node bugSolution.js`.
7. Access `http://localhost:3000/error` again.
8. Observe the graceful error handling.