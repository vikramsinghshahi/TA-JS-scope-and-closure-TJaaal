1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let percentage = fuction(marks, total){
  return (marks * 100) / total;
}

let percentage = (marks, total)=>{
  return (marks * 100) / total;
}

```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer 
Function Declaration 
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

Function Expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

Function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

Function Expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;

Function Expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
because function is an object in javascript and we can store the vlaue of on funaction defenation inside a variable.
example- let percentage = (marks, total) => (marks * 100) / total;

4. Why is a function call an expression in JavaScript?
because function is an object in javascript and we can store the vlaue of on funaction defenation inside a variable.
example- let percentage = (marks, total) => (marks * 100) / total;


5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid
five = add; // valid
five = five(10, 11); // valid
five = function () {
  return 'Hello';
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.
function sum(){}// function defination is defining a function with function key word

sum()// function call is calling a function with paranteses



7. What is the similarities between function definition and function call? 
function defination is an expression
function call is also an expression


8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid 
```

9. What is higher order function explain with an example.
A “higher-order function” is a function that accepts functions as parameters and/or returns a function.

const isEven = (n) => {
  return n % 2 == 0;
}
 
let printMsg = (evenFunc, num) => {
  const isNumEven = evenFunc(num);
  console.log(`The number ${num} is an even number: ${isNumEven}.`)
}


10. Explain what is callback function. Why you can pass a function inside a function?
In JavaScript, a callback function is a function that is passed into another function as an argument. This function can then be invoked during the execution of that higher order function (that it is an argument of).

Since, in JavaScript, functions are objects, functions can be passed as arguments.


