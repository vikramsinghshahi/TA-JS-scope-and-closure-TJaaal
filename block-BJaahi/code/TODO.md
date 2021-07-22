For the given code below:

- re-write the code in ways that system will understand

For Example:

1.

```js
var username = 'Arya';
let brothers = ['John', 'Ryan', 'Bran'];

console.log(username, brothers[0]);

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Declaration Phase
var username = undefined;
let brothers;

function sayHello(name) {
  return `Hello ${name}`;
}

let message;
var nextMessage = undefined;

// Execution Phase

username = 'Arya';
brothers = ['John', 'Ryan', 'Bran'];

console.log(username, brothers[0]);

message = sayHello(username);
nextMessage = sayHello('Test');
```

2.

```js
console.log(username, numbers);

var username = 'Arya';
let number = 21;

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->
```js

//Declaration phase
 
 username = undefined;
 number = ;

sayHello = function;

message =;
nextMessage= undefined;

// Execution Phase

console.log(username , numbers)//error- numbers not defined
```


3.

```js
console.log(username, numbers);
let username = 'Arya';
let number = 21;

let sayHello = function (name) {
  return `Hello ${name}`;
};

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
//declaration phase

username=;
number = ;

sayHello =;
message =;
nextMessage =undefined;

//exectuion phase

console.log(username, numbers)// error- username is not defined

```

4.

```js
let username = 'Arya';
console.log(username, numbers);

let number = 21;
let message = sayHello(username);

let sayHello = function (name) {
  return `Hello ${name}`;
};

var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
//declaration phase

username = ;

number = ;
message =;
sayHello =;

nextMessage = undefined;

//execution phase

username = "Arya";

console.log(username, numbers)//error- numbers is not defined
```

5.

```js
console.log(name);
console.log(age);
var name = 'Lydia';
let age = 21;
```

<!-- Answer -->

```js
//declaration phase

name = undefined;

age =;

//execution phase

console.log(name)//undefined;

console.log(age)//Error- age not defined
```

6.

```js
function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}

sayHi();
```

<!-- Answer -->

```js
//declaration phase

sayHi = function;

//execution phase

sayHi()

// sayHi function declaration

name = undefined;

age = ;

// sayHi function execution

console.log(name)// undefined
console.log(age)//Cannot access 'age' before initialization

```

7.

```js
sayHi();
function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}
```

<!-- Answer -->

```js
//declaration phase

sayHi = function;

//execution phase

sayHi()

// sayHi function declaration

name = undefined;

age = ;

// sayHi function execution

console.log(name)// undefined
console.log(age)//Cannot access 'age' before initialization

```

8.

```js
sayHi();
let sayHi = function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
};
```

<!-- Answer -->

```js
// Your code goes here
```

9.

```js
let num1 = 21;
console.log(sum);
var sum = num1 + num2;
let num2 = 30;
```

<!-- Answer -->

```js
// Your code goes here
```

10.

```js
var num1 = 21;

let sum2 = addAgain(num1, num2, 4, 5, 6);

let add = (a, b, c, d, e) => {
  return a + b + c + d + e;
};
function addAgian(a, b) {
  return a + b;
}
let num2 = 200;

let sum = add(num1, num2, 4, 5, 6);
```

<!-- Answer -->

```js
// Your code goes here
```

11.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

let add = (a, b) => {
  return a + b;
};
```

<!-- Answer -->

```js
// Your code goes here
```

12.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

function add(a, b) {
  return a + b;
}
```

<!-- Answer -->

```js
//decleration phase

test = function;

sum = ;

add = function;

//exectution phase

sum = test(100);//121

//test function

//declaration phase
a = undefined;

num1 = ;

//exection phase

a = 100;
num1 = 21;

//decleration phase

a = undefined;

b = undefined;

//executio phase

a= 100;

b = 21;

return a+b//121


```
