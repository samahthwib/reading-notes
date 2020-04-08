

## call stack : 
### is a mechanism for an interpreter to keep track of its place in a script that calls multiple functions what function is currently being run and what functions are called from within that function.the. also call stack is synchronous and itis a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

1. When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
2. Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
3. When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
4. If the stack takes up more space than it had assigned to it, it results in a "stack overflow" error.

**JavaScript engine** is a single-threaded interpreter comprising of a heap and a single call stack. The browser provides web APIs like the DOM, AJAX, and Timers.

### In Asynchronous JavaScript, we have a callback function, an event loop, and a task queue. The callback function is acted upon by the call stack during execution after the call back function has been pushed to the stack by the event loop.

**Types of error messages** : 
* Reference errors
* Syntax errors
* Range errors
* 