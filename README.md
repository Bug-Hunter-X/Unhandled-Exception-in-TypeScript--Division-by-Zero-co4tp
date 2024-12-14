# Unhandled Exception in TypeScript: Division by Zero

This repository demonstrates a common error in TypeScript: failing to handle potential exceptions. The `divide` function throws an error if the divisor is zero; however, the calling code doesn't handle this, causing the program to crash. This example illustrates the importance of robust error handling for creating reliable applications.

## How to Reproduce

1. Clone this repository.
2. Run `tsc bug.ts` to compile the TypeScript code.
3. Run `node bug.js` to execute the compiled JavaScript code.  Observe the unhandled exception.
4. Refer to `bugSolution.ts` for a corrected implementation.