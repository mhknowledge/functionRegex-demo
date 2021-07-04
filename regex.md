# What is a Function?

In programming, code is used to carry out a task, often multiple times.  This can be cumbersome.  To avoid this we can group code together and link it with a task, from there we have the ability to use that code at any time to carry out the task over and over.  This is done by creating a FUNCTION.  A function serves as reusable code that combines statements to perform an intended task.

## Summary

In this regex we will briefly discuss the role of functions in JS.  Likewise we will cover different components of functions and provide examples of each.

## Table of Contents

- [Declarations](#declarations)
- [Calling a Function](#calling-a-function)
- [Parameters](#parameters)
- [Arguments](#arguments)
- [Default Parameters](#default-parameters)
- [Return](#return)

### Declarations
In JS, we can create a function multiple ways.  One of which is by using a declaration.  In a function, a declaration joins a function to a name or what's commonly referred to as an identifier.  Take a look at the structure of a function declaration below:

![image](https://user-images.githubusercontent.com/79174643/124395940-f6fec000-dcd4-11eb-8856-fb0edce4fa02.png)

A function declaration consists of:

The function keyword.
The name of the function, or its identifier, followed by parentheses.
A function body, or the block of statements required to perform a specific task, enclosed in the function’s curly brackets, { }.

### Calling a Function
In JS to call a function we have to type the function along with parentheses: helloWorld();
The function call executes the code that makes up the function's body, basically it runs the code between the curly braces:

![image](https://user-images.githubusercontent.com/79174643/124396123-cb300a00-dcd5-11eb-8276-d48d11653587.png)

All in all, we can use the same functon as many times as we see fit.

### Parameters
When declaring or setting a fucntion in place, we have the option of specifying the function's parameters or boundaries.  Parameters allow functions to accept input and complete the function's task using that input.  Parameters act as placeholders for information that will be passed/sent to the function when the function is called.  Here's an example of a function with parameters:

![image](https://user-images.githubusercontent.com/79174643/124396399-4645f000-dcd7-11eb-95af-a5fc0bac685b.png)

### Arguments
When calling a function that has parameters, we can provide values for those parameters.  Those values that will be passed through the function body and executed within the function statements are called arguments.  Arguments can be both value or variable.  Here are examples of each:
1.) parameters as values:
![image](https://user-images.githubusercontent.com/79174643/124396880-41367000-dcda-11eb-8e87-f65b4489e247.png)

2.) parameters as variables:
![image](https://user-images.githubusercontent.com/79174643/124396896-5ad7b780-dcda-11eb-8ced-66e75b8b5ce7.png)

The order in which arguments are passed and assigned follows the order that the parameters are declared.  Also one of the benefits of using parameters is that it allows the function to be resused for to carry out it's task upon any object that it's parameters apply to.

### Default Parameters
Default parameters allow parameters to have a predetermined value in case there is no argument passed through the function, or even if the arguemtn is undefinded when called.  See the following example:

![image](https://user-images.githubusercontent.com/79174643/124397050-7099ac80-dcdb-11eb-932c-d046066f3c9c.png)

By using a default parameter, we cover for situations when an argument isn't sent through a function that is expecting an argument to be sent/passed through.

