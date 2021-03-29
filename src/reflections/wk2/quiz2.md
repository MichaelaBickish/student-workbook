# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
var, let and const
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
a block of code designed to perform a particular task
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
concepts of clean coding, object-oriented
architecture, and design patterns--
1 The Single Responsibility Principle
2 The Open-Closed Principle
3 The Liskov Substitution Principle
4 The Interface Segregation Principle
5 The Dependency Inversion Principle
```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
pineapple is at index 2 because arrays are z-indexes that start at 0.
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below -->
```
you.friends.push(them)
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
(num % 2 == 0) ? "true" : "false"
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
the incrementer. i++
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
Document object model. Html doc is accessed first.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
Primitives: String, number, symbol, boolean, undefined, bigInt.
Structural: object, function.
Structural root primitive: null.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters go inside the parenthesis & used when defining a function. Whereas arguments are the values the function receives from each parameter when the function is executed.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive values are data that are stored on the stack.
Reference values are objects that are stored in the heap. Reference value stored in the variable location is a pointer to a location in memory where the object is stored.
```