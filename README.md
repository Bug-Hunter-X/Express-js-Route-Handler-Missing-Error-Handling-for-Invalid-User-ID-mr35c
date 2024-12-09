# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers:  missing error handling for invalid input.  Specifically, the `/users/:id` route attempts to parse the `id` parameter as an integer without checking its validity.  This can lead to crashes or unexpected behavior if the `id` parameter is not a number.

The `bug.js` file contains the buggy code. The `bugSolution.js` file demonstrates the corrected code with proper error handling.