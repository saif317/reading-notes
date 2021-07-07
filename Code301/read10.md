# **In memory storage**

<img src="https://reactjs.org/logo-og.png" width="200">

**Q: What is a ‘call’?**

**A:** a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

**Q: How many ‘calls’ can happen at once?**

**A:** only 1

**Q: What does LIFO mean?**

**A:** "Last In, First Out" it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

**Q: Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.**

**A:**

```Javascript
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
```

**Q: What causes a Stack Overflow?**

**A:** A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point

**Q: What is a ‘refrence error’?**

**A:** when you try to use a variable that is not yet declared,trying to change the value of a const variable

**Q: What is a ‘syntax error’?**

**A:** this occurs when you have something that cannot be parsed in terms of syntax

**Q: What is a ‘range error’?**

**A:** Try to manipulate an object with some kind of length and give it an invalid length

**Q: What is a ‘tyep error’?**

**A:** this types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible

**Q: What is a breakpoint?**

**A:** a point in the code for the debugger to stop at

**Q: What does the word ‘debugger’ do in your code?**

**A:** it pauses the program on set breakpoints so you can see the values at that breakpoint
