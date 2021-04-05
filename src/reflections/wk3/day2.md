# #2 | 3/30/21 Journal

Afternoon Project: https://github.com/MichaelaBickish/vendmachine 

Read Advancing with JS > Encapsulation in JavaScript and answer the following questions

## *What is the purpose of Encapsulation?*
Help prevent bugs, keep code clean and organized. Reduce spaghetti code, prevent reusing variable names that can lead to bugs/unpredictable behavior.

## *What were some of the problems with closures and the underscore prefix?*
The underscore has become a recognized convention & used as an internal property to denote 'private'. A large number of people may ignore the convention which leads to more breaking changes than necessary.

## *How do we create private variables in a ES6 Class? Why would you do this?*
Put a function inside another function. The inner function's enclosed variables are only in scope within the containing outer function. You can’t get at the data from an outside scope except through the object’s privileged methods. Used for data privacy.