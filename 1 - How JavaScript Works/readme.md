# How JavaScript Works

## Fundamental:

- Excution Context:
  - Everything in javascript happens inside the excution context.
  - it can be visualized as a big box or container where JavaScript code is executed.

![images](executionContext.png)

- Assume the execution context to be a big box where everything takes place. It has 2 components in it:
  - Memory : The place where all the variables and functions are stored as (key: value) pairs. Memory component is also known as the variable environment.
  - Code : The place where code is executed one line at a time. Code component is also known as the Thread of Execution

#### JS is a synchronous single-threaded language.

- By single-threaded, we mean JS can only run 1 command at a time.
- By synchronous-single threaded, we mean it can run 1 command at a time, in a specific order.
