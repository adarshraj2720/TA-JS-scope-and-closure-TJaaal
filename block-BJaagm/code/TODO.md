1. What does thread of execution means in JavaScript?
```js
ans- when we execute the piece of code javaScript engine takes that code execute  line by line that is called the  thread of execuation.
```
2. Where the JavaScript code gets executed?
```js
ans- javaScript code gets executes in the GEC(global execuation context)
```
3. What does context means in Global Execution Context?
```js
ans- context means in global execuation context is the run the code line by line.
```
4. When do you create a global execution context.
```js
  ans- when does javaScript code time run first time that create a global executaion context 
```
5. Execution context consists of what all things?
```js
ans- function execution and a value assign to the variable

```
6. What are the different types of execution context?
```js
ans- function execution and a value assign to the variable

```
7. When global and function execution context gets created?
```js
ans-when does code excute in the javascript then global and function execution context gets created
```
8. Function execution gets created during function execution or while declaring a function.
```js
    ans- function execution gets created during the function execution .
```

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