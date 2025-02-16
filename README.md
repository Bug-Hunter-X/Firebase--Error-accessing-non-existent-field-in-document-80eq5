# Firebase: Error accessing non-existent field in document
This repository contains a demonstration of an error that can occur when using the Firebase SDK to access fields in Firestore documents.  The error arises when attempting to access a field that does not exist in the document.  Two solutions are provided to handle this situation gracefully.

## Bug
The `bug.js` file demonstrates the error. Attempting to access the `city` field, which isn't present in the document, throws an error.

## Solution
The `bugSolution.js` file presents two solutions:
1. Check for field existence before accessing it.
2. Use optional chaining to prevent the error.

Choose the method most suitable for your project and coding style.