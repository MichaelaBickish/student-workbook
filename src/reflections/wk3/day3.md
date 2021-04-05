# #3 | 3/31/21 Journal

Afternoon Project: https://github.com/MichaelaBickish/spring21-gregslist

Read Advancing with JS > An Intro to Javascript Proxy Objects and answer the following questions

## *What are the two common operations that we will set in the handler?*
get and set

## *What do you have to make sure you are doing with every Get to insure the value does not become undefined?*
add 2 parameters. obj & prop. Since the default implementation of the get operator is to return the value stored in that key in the object. If you don't add the prop parameter, that's why it returns undefined.

## *What are some of the benefits of the proxy object that we are using in our structure for applications?*
If you want to keep some properties private, you can.
You can also add custom validations before even setting the value so if the value doesn't match the validation, you can have it throw an error. i.e. where only a string can be stored in a given object.