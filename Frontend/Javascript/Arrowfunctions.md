# Breaking down arrow functions to the simplest form

### Arrow Functions

- Let compare the traditional function and arrow function
- Code sample: A function to add two numbers

```js
//Traditonalfunction
 function addNumber (a, b) {
    return a + b; 
 }
//Arrow function
 const addNumber2 = (a, b) => a + b;
```
## Key things to master about arrow functions:
```js
//single parameter - parentheses optional
const square = x = x * x;
const square = (x) = x * x;  both work
```
```js
//No parameter - parentheses required
const greet = () = "Hello!";
```
```js
// Multiple parameters - parentheses required
const add = (a, b) = a + b;
```
```js
// Multiline function - curly braces required
const calculate = (a, b) => {
    const sum = a + b;
    return sum * 2;
};
```