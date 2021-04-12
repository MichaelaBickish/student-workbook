# Week 4, Day 1 | 4/5/2021 | Daily Journal

Afternoon Project: https://github.com/MichaelaBickish/trivia

Read Asynchronous Code > Callback Hell and answer the following questions

## *What are some of the signs and causes of Callback Hell?*
Code that isn't shallow. Nested functions. 

## *What does the asynchronous mean and how are callbacks involved?*
Async means "takes some time/happens in the future/ not right now". Instead of immediately returning some result like most functions, functions that use callbacks don't return anything right away. You store the code that should run after something else runs.

## *Summarize the 3 ways to avoid / fix Callback Hell*
Keep your code shallow (don't nest functions). Create resusable functions and modularize- easier for other developers to understand. Handle every single error in every one of your callbacks.