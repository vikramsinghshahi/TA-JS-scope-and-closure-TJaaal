1. What does thread of execution means in JavaScript?
it is the working of javascript engine whenever we write a code snippet  in javascript

2. Where the JavaScript code gets executed?
in jvascripts engine

3. What does context means in Global Execution Context?
context means the environment wher the code is being executied

4. When do you create a global execution context.
whenever we write a cdode the javascripts engine create the global execution context.


5. Execution context consists of what all things?
execution context consist of two section one where all the data get stores and the other where all the execution will happen

6. What are the different types of execution context?
global and function execution context

7. When global and function execution context gets created?
when ever we write any code snippet the gloabl execution context gets created and hwen ever we dec;are the function in the code the function execution context gets created.

8. Function execution gets created during function execution or while declaring a function.
Function execution gets created during function execution


9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)