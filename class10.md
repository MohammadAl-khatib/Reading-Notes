# Debugging
It is common to make mistakes when writing code, in this text we will learn how to handle errors and what tools are there to help you trace and remove code mistakes (Debugging).

In order to be able to track down errors, the way JS runs the code must be understood, the code is either under global context or function context:

1. Global context: it is the default context in the page, every thing not inside a function is part of the global context.

2. Function context: the script that lies inside a function.

When the code is run, the general context will pile (stack) the code from inside any called function over the current task, it does the same when running a child function inside a parent function. Variables of parent function can be used in child function, but the opposit is not valid, anyway, variables of the glopal context can be called anywhere.

## Types of Errors

![errors](https://www.tutsmake.com/wp-content/uploads/2020/05/Types-of-Errors-In-JavaScript.jpeg)

the most common errors found when running code are:

Error | Description
------------ | -------------
error | general error
syntax error | error from typos usually
reference error | from not declared variable or functions
type error | not correct data type entered or used

## Debugging and Developer Tools
Removing the error (the bug in code) can take place when two questions are answered:

1. where is the problem?

2. what is the type of the problem?

To solve this, browsers can give great help with consoles, which you will call inside your script using `console.log()`

![console](https://intoli.com/blog/nightmare-console-errors/img/console-errors.png)

Every browser has its way to log console, info in console can be viewd as single data, table, and group.
