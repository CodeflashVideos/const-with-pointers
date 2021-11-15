# Using `const` with Pointers in C

- There are three ways of using the `const` keyword with pointers.

- Read the example code from right to left.

| Pointer type                   | Example               | Pointed value | Pointed address |
| ------------------------------ | --------------------- | ------------- | --------------- |
| Constant pointer               | `int * const p`       | Mutable       | Immutable       |
| Pointer to a constant          | `const int * p`       | Immutable     | Mutable         |
| Constant pointer to a constant | `const int * const p` | Immutable     | Immutable       |
