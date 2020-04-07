#Programming with JavaScript

###Scripts
A **script** is a series of step-by-step instructions that a computer can follow to achieve a goal. Each time a script runs, it might only use a subset of all the instructions. To approach writing a script, break down your goal into a series of tasks and then work out each step needed to complete that task (a flowchart can help). 


## Expressions and Operators
An expression evaluates into (results in) a single value. There are two types of expressions.
1. Expressions that just assign a value to a variable. In order for a variable to be useful, it needs to be given a value. This is done using the assignment operator (the equals sign):
```var color - `beige`;```
The value of color is now beige. This expression is an example of an assignment operator.

1. Expressions that use two or more values to return a single value. 
You can perform operations on any number of individual values to determine a single value:
```var area = 3 * 2;```
The value of area is now 6. This expression is an example of an arithmetic operator. 

Expressions rely on things called operators, which allow programmers to create a single value from one or more values. 

#### Arithmetic Operators #### 
- Addition +
- Subtraction -
- Division /
- Multiplication *
- Increment ++ (adds 1 to the current number)
- Decrement -- (subtracts 1 from the current number)
- Modulus % (divides two values and returns the remainder)
Don’t forget order of operations! 

#### String Operators #### 
There is just one string operator, the plus symbol. It is used to join the strings on either side of it. 
Keep in mind:
- When you place quotes around a number, it is a string (not a numeric data type). 
- If you try to add a numeric data type to a string, then the number becomes part of the string. 
- If you try to use any of the other arithmetic operators on a string, then the value that results is usually a value called NaN (Not a Number). 

## Functions
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements). 

To create a function, you give it a name and then write the statements needed to achieve its task inside the curly braces. This is known as a function declaration. 

## Parameters
Sometimes a function needs specific information to perform its task. In such cases, when you declare the function you give it **parameters.** Inside the function, the parameters act like variables. 

