# Week 4, day 2 | 4/6/2021 | Daily Journal

Afternoon Project: https://github.com/MichaelaBickish/spring21-gregslist-revisited

Read Asynchronous Code > JavaScript Promises and answer the following questions

## *What are the three states of a Promise?*
Pending: Initial State, before it succeeds or fails
Resolved: Completed Promise
Rejected: Failed Promise

## *How do promises seek to resolve the issues of "callback hell"?*
Multiple callbacks can be chained one after another. if a callback is resolved, then() we can go on to the next one. This order resolved callback hell.

## *What is the difference between .then() and .catch()?*
If the Promise gets resolved then() something will happen next. The then() method is called after the Promise is resolved. 

If the promise gets rejected, it will jump to the catch() method
