1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentages=function percentage(marks, total) {
  return (marks * 100) / total;
}

let percentages=function (marks, total) {
  return (marks * 100) / total;
}

let percentages= (marks, total)=> {
 return (marks * 100) / total;
}

let percentages= (marks, total)=> (marks * 100) / total;

```


2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
ans--function definition
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};


ans--function expression
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;

  ans--function expression
};
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

 ans--function expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;

ans--function expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.
```js
expression is that something result in value
//number,boolean,string,null, undefined and object




fucntion definition is a set of statements that performs a task 

function fullName(fisrtName,lastName){
  return `${firstName}+${lastName}`
}

function expression is a function that store in a variable

let name=function fullName(fisrtName,lastName){
  return `${firstName}+${lastName}`
}
```
4. Why is a function call an expression in JavaScript?

```js
function call always return the value

function call is excuate the function  when we the call the function .


function add(a,b){

  return a+b;
}
add(1,2)//3
function addAgain(a,b){


}
addAgain()//undefined
```
5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // valid 5
five = add; // valid
five = five(10, 11); // Valid 21
five = function () {
  return 'Hello';
}; // valid
```

6. What is the difference between function definition and function call? Explain with an example.
```js
function definition is a when you define a function

function definition is the set of definition that perfoem a task  and function call is the call the finction with the prenthesis

function percentage() {
  
}
  it is the function definition

percentage();
it is the function expression



```

7. What is the similarities between function definition and function call?
```js

ans- function definition is the expression (function is an object)
      function call is an expression (function can always return a value)

```


8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid 
```

9. What is higher order function explain with an example.
```js
//that accept a function definition 
//that return a function definition
function add(cb){//HOF

  cb()
}

function add(){//HOF
function main(){}
return main

}


ans-A higher order function  is a function that accepts functions as parameters and returns a function.

```
10. Explain what is callback function. Why you can pass a function inside a function?
```js

//Beacuse function is an expression in jS we can pass a function inside another function

ans- A callback is a function passed as an argument to another function

```