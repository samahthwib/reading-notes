### **Errors Handeling & Debugging**

To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex; some tasks
cannot complete until another statement or function has been run

*execution contexts* according to JavaScript interpreter uses this concept.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.

Each time a script enters a new execution context, there are two phases
of activity:
1. PREPARE  
2. EXECUTE

If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.

--------------------------------

**ERROR OBJECTS**
Error objects can help you find where your mistakes are and browsers have tools to help you read them.

Some of types of error objects
* Type Error  
* RangeError
* Error 
* NaN

--------------------------------

Debugging is about deduction: eliminating potential causes of an error.
You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time.

If you know your code might fail, use try, catch, and finally.
Each one is given its own code block.