# Application Architecture, MVC Design Pattern

**1.** What are the Pillars of Object Oriented Programming (`OOP`)?
<!-- enter you answer in the space below -->
```
Abstraction, Encapsulation, inheritance, polymorphism.
```
**2.** How would you access the `name` of the below object using the `property` variable?
```js
let staff = {
  name: "Tim",
  age: 26,
  job: "Code Monkey"
  }
let property = 'name'
```
<!-- enter you answer in the space below -->
```
return staff['property']
```
**3.** What is Encapsulation?
<!-- enter you answer in the space below -->
```
Breaking up code into smaller, well-organized, "like" files where some data may be private.
```
**4.** What does the S stand for in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
Single responsibility. Every module, class, or function should have responsibility over a single part of the functionality and it should encapsulate that part.
```
**5.** What the difference between a `class` and an instance of a `class`?
<!-- enter you answer in the space below -->
```
A class is the blueprint for something. An instance of a class is where something is actually being built or created using the class's blueprint.
```
**6.** What is a `Proxy` object?
<!-- enter you answer in the space below -->
```
To allow you to provide custom functionality to basic operation that can be performed on an object.
```

**7.** What is the purpose of the `MVC` pattern?
<!-- enter you answer in the space below -->
```
This design pattern is a structure for keeping display and data separate to allow each to change without affecting the other.
```
**8.** What is the job of the `Controller` in the `MVC` Pattern?
<!-- enter you answer in the space below -->
```
To be a courier of info. To process information received from the DOM, and tell service that some data needs to change i.e. request the change.
```

**9.** What is the job of the `Service` in `MVC`?
<!-- enter you answer in the space below -->
```
Takes the request from the controller & uses data from the state to do business logic to make the change happen.
```
**10.** What is the job of the `Model` in `MVC`?
<!-- enter you answer in the space below -->
```
Responsible for managing the data of the application.
```

