# Learn Playwright

This repository contains small JavaScript examples used while learning the
fundamentals that support browser automation.

## Chapter 001: JavaScript basics

The [`Chapter001`](./Chapter001/) folder contains examples for:

- Printing values and performing arithmetic
- Declaring variables and inspecting value types
- Using a ternary operator to choose a value

### Ternary operator

The ternary operator evaluates a condition and returns one of two values:

![Ternary operator decision flow](./images/ternary-operator.svg)

In [`05_ternary_op.js`](./Chapter001/05_ternary_op.js), the condition is
`age > 18`. Since `age` is `15`, the expression evaluates to `false`.

Run an example with Node.js from the repository root:

```sh
node Chapter001/05_ternary_op.js
```
