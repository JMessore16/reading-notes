# Programming with JavaScript

## Functions
**Functions** are one of the fundamental building blocks of programming in JS.
A function should take an input and return an output where there is a defined relationship between the input and output.
### A function should be enclosed in `{...}` for example

function myFunc(theObject) {

  theObject.make = 'Toyota';
  
}

This is an example of a function calling to define the object, the object is set equal to 'toyota'. As you can see `theObject` is called twice first to specify and define what `theObject` is in a function and then to define what the object is.

function square(number) {

  return number * number;
  
}

In the example above `function` is set to define the square of (number), number will be input by the user or within the code to get an output or `return` of number * number which would define the square of the inout number.

## Control Flow
**Control Flow** is the order in which the computer executes statements in a script.

An example of control flow would be an if/else, if something happens then execute so and so or else execute something else.

if (field==empty) {

    promptUser();
    
} else {

    submitForm();
    
}

In the above example the script calls to see if the user of the site has filled in a form, if empty the user will be prompted to submit the form. A very simple script and a perfect example of if/else.
