
## Error Handling & Debugging

JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully. When you are writing JavaScript, do not expect to write it perfectly the first time.
Programming is like problem solving: you are given a puzzle and not only do you have to solve it, but you also need to create the instructions that allow the  computer to solve it. too. When writing a long script, nobody gets everything right in their first attempt. The error messages that a browser gives look cryptic at first, but they can help you determine what went wrong in your JavaScript and how to fix it.

#### ORDER OF EXECUTION
To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run.

#### EXECUT.ION CONTEXTS
The JavaScript interpreter uses the concept of execution contexts. There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.

#### EXECUTION CONTEXT & HOISTING
Each time a script enters a new execution context, there are two phases of activity:
1: PREPARE
• The new scope is created
• Variables, functions, and arguments are created
• The value of the this keyword is determined

2: EXECUTE
• Now it can assign values to variables
• Reference functions and run their code
• Execute statements.

##### UNDERSTANDING SCOPE
In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object.

##### UNDERSTANDING ERRORS
If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code

##### ERROR OBJECTS
Error objects can help you find where your mistakes are and browsers have tools to help you read them.

##### ERROR OBJECTS CONTINUED
Please note that these error messages are from the Chrome browser. Other browsers' error messages may vary.


