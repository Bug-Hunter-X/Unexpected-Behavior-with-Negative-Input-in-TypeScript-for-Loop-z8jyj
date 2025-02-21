# Unexpected Behavior with Negative Input in TypeScript

This repository demonstrates an uncommon bug in TypeScript related to the handling of negative input in a `for` loop. The function `printNumbers` is designed to print numbers from 1 to `n`. However, when a negative number is provided, it doesn't print anything instead of throwing an error or producing an unexpected output.  This is due to the loop condition `i <= n`. When n is negative, the condition `i <= n` is initially false for i=1 and never becomes true, resulting in zero iterations.

The `bug.ts` file contains the buggy code, and `bugSolution.ts` provides a corrected version.
