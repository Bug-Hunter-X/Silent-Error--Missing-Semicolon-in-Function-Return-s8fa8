# Silent Error: Missing Semicolon in Function Return

This repository demonstrates a subtle JavaScript error: a missing semicolon after a return statement within a function.  While this code might appear to work correctly in some cases due to JavaScript's automatic semicolon insertion (ASI), it's considered bad practice and can lead to unexpected behavior or errors in more complex scenarios.

The `bug.js` file contains the erroneous code. The `bugSolution.js` file provides the corrected version.

**Key takeaway:** Always include semicolons after return statements for readability, maintainability, and to avoid relying on the potentially unpredictable behavior of ASI.