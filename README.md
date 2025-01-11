# Unhandled JavaScript Error in HTML

This repository demonstrates an uncommon HTML error related to unhandled JavaScript exceptions. The error arises from attempting to access a property of an undefined variable.  This kind of error can be difficult to debug because it often doesn't produce a clear error message but leads to unexpected application behavior.

## Bug Description
The `bug.html` file contains a JavaScript script that attempts to access the `myProperty` property of the `myVar` variable, which is never defined. This leads to a `TypeError` in the browser's console (depending on browser settings). The error is not explicitly handled, causing the script execution to continue, potentially with undesired results.

## Solution
The `bugSolution.html` file demonstrates the solution which includes proper error handling to prevent the unexpected behavior.  It first checks if the variable exists and is an object before attempting to access its properties. This prevents the `TypeError` and provides a more graceful way to handle the situation.  This can be adapted based on your code's context.