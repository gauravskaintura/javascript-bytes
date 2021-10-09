
# Hoisting in JavaScript

When you execute a piece of JavaScript code, the JavaScript engine creates the global execution context.

The global execution context has two phases: creation and execution.

During the creation phase, the JavaScript engine moves the variable and function declarations to the top of your code. This feature is known as hoisting in JavaScript.

For Example,

    console.log(name); // undefined
    var name = John;
- This will produce *undefined* on the console output screen instead of *not defined* as the declaration for the variable *name* has been moved to the top of the code
- While in the case of below snippet of the code, the output will be *not defined* as the keyword *item* has not been declared anywhere in the code

        console.log(item); // not defined

- Same thing happens with the functions declarations (check ref.)
## References
- https://www.javascripttutorial.net/javascript-hoisting/