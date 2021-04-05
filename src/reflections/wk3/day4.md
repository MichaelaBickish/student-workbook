# #4 | 4/1/21

Afternoon Project: https://github.com/MichaelaBickish/darryls-sporting-goods

Read Advancing with JS > The Observer Pattern and answer the following questions

## *What problems does the Observer Pattern seek to solve?*
Keeping multiple elements synced with the same data.

## *What are the three mechanisms of the observer pattern?*
The subscribe method: adds new observable events.

The unsubscribe method: removes observable events.

The broadcast method: executes all events with bound data.

### *Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.*
The template couples proxy objects and the observer pattern to manage and update the dom by keeping object's data synced.