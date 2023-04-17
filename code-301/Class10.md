# Class 10 In memory storage

#### Link to article: [Understanding the JavaScript Call Stack](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)
#### Link to article: [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

> 

***

## Understanding the JavaScript Call Stack

**What is a ‘call’?**
> A 'call' is a way to invoke a function with an explicit 'this' context and arguments.

**How many ‘calls’ can happen at once?**
> Only one 'call' can happen at a time on a single-threaded JavaScript runtime.

**What does LIFO mean?**
> LIFO stands for Last In, First Out, and is a principle used in data structures where the last element added is the first one to be removed.

**Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**
>
```function main() {
  console.log('main');
  functionA();
}

function functionA() {
  console.log('A');
  functionB();
}

function functionB() {
  console.log('B');
  functionC();
}

function functionC() {
  console.log('C');
}

main();
```
**What causes a Stack Overflow?**
> A stack overflow occurs when the call stack exceeds its maximum size due to an infinite or too deep recursion.


***


## JavaScript error messages

**What is a ‘reference error’?**
> A reference error occurs when a variable is referenced (used) before it has been declared or defined.

**What is a ‘syntax error’?**
> A syntax error occurs when code is not written in the correct syntax or format and cannot be executed.

**What is a ‘range error’?**
> A range error occurs when a value is not within the acceptable range of values as defined by the program.

**What is a ‘type error’?**
> A type error occurs when a value is not of the expected data type or cannot be coerced into the correct type.

**What is a breakpoint?**
> A breakpoint is a debugging tool that allows a programmer to pause the execution of code at a specific line for inspection.

