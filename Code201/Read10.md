Chapter 10 Error Handling & Debugging 
**JavaScript can be hard to learn and everyone makes mistakes when writing it. This chapter will help you learn how to find the errors in your code. It will also teach you how to write scripts that deal with potential errors gracefully.**
## ORDER OF EXECUTION 
+ To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run:
![Image](/Images201/aq8.png)
## EXECUT.ION CONTEXTS 
- The JavaScript interpreter uses the concept of **execution contexts.** There is one global execution context; plus, each function creates a new new execution context. They correspond to variable scope.
![Image](/Images201/aq9.png)
## EXECUTION CONTEXT & HOISTING 
+ Each time a script enters a new execution context, there are two phases of activity:
1. PREPARE
- The new scope is created
- Variables, functions, and arguments are created
- The value of the this keyword is determined
2. EXECUTE
- Now it can assign values to variables
- Reference functions and run their code
- Execute statements
## UNDERSTANDING SCOPE 
+ In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's v a ri ables object.
+ Functions in JavaScript are said to have lexical scope. They are linked to the object they were defined within. So, for each execution context, the scope is the current execution context's variables object, plus the variables object for each parent execution context.
+ Imagine that each function is a nesting doll. The children can ask the parents for information in their variables. But the parents cannot get variables from their children. Each child will get the same answer from the same parent.

## [Sorce](https://drive.google.com/file/d/1KFKjXZMEVY5OIxIUcUlCzCxCvZvr529K/view?usp=sharing)
