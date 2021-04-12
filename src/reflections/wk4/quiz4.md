# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
synchronous code is executed in sequence where each statement waits for the previous to finish. Async doesn't have to wait and the app can continue to run.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener watches a variable for change and upon change, executes a function. This is the observer pattern. Allowing you to update part of your app without reloading excessively.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
open closed principle- open for extension without breaking existing code
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
A function that may take some time to produce a result, but runs asynchronously within the program, not slowing it down for the user.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
a result that will be returned from an async function. We use the try/catch block where, if the code we want to execute has an error, the catch block will let us know exactly where the error originated from using console.error(error).
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
Get, post, put.
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
Application programming interface
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
Service. That info is then passed to app state.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
Bundling data to hide values or state of a structured data object inside a class, preventing direct access by clients.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
200 "ok" 
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A catch all response, indicates the server encountered an unexpected condition that prevented it from fullfilling the request.
```