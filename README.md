# TypeScript Runtime Error Despite Static Typing

This repository demonstrates a common issue in TypeScript: runtime errors can still occur despite the use of static typing.  Type safety helps prevent many errors during development, but it does not guarantee the absence of all runtime errors.  Type coercion can lead to unexpected behavior.

The `bug.ts` file contains a simple example showcasing this issue.  The `bugSolution.ts` file offers a potential solution to address this specific problem.

## How to reproduce

1. Clone the repository.
2. Compile using `tsc bug.ts`.
3. Run the compiled JavaScript file.  Observe the runtime error.

## Solution

The provided solution in `bugSolution.ts` highlights how better type guarding or runtime checks can mitigate these issues.