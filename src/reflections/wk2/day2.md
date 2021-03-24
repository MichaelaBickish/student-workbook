# 2 | 3/23/2021 Journal

Afternoon Project: https://github.com/MichaelaBickish/js-tests-loops-and-arrays

## *What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?*
**1** function declaration: can be used before it's defined because the function definition is hoisted.

    function name() {
        //statements
    }

**2** function expression: these aren't hoisted so can't be used before they're defined.

    let name = function(parameters) {
        // statements
    }


**3** arrow function expression: a shorter syntax for writing function expressions.

    let name = (parameters) => {
    // statements
    }

## *What is the difference between Parameters and Arguments?*
**Parameters** go inside the parenthesis. They're used when defining a function. They're the names created in the function definition.

**Arguments** are the values the function receives from each parameter when the function is executed.


## *What are higher order functions? Can you provide an example?*
When a function accepts another function as a parameter.

*example:* 
        
        array.prototype.map