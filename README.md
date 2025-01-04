# Stack Overflow in Recursive Factorial Function

This repository demonstrates a common error in recursive functions: stack overflow.  The `foo` function calculates the factorial recursively.  With large inputs, the recursive calls will exceed the maximum call stack depth, resulting in a stack overflow error.

The solution demonstrates how to avoid this issue using iteration instead of recursion.