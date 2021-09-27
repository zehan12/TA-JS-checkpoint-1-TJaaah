1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
In first , return the variable to the function.

In second , consle.log only display the sum and it give variable undeifined.


2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

first will give value which is from  addition because of return statement . second will give undefined value because there is no return statement.


3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

As per the above function we only add  two parameters a & b so it will take first two value only so the output is 36.

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

```js 
let add = function sum( a, b ){
  return sum;
} 
```

yes, it can be stored.


5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

```js

function sayHello(name){
return name ;
}

sayHello(`Hello Arya`)

```

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
Output will be `Hello, John`
it will return the message and userName is defined outside the function


7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // undefined

showMessage(); // 'Hello, John'

alert(userName); // undefined
```

8. What is a Anonymous Function give example of three functions.

```js

const square = function(num){
  return num * num ;
}

square();

const sum = function( a , b ){
  return a + b;
}

sum();

const fulName = function( firstName , lastName ){
  return firstName + lastName;
}

fulName();
```

9. Can function declaration be a Anonymous Function? Explain

No , function declaration can not be a Anonymous Function because Anonymous Function can omitted the function declaration to create a Anonymous Function.


10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```

```js

//1
function isGreater( numY , numZ ){
  if ( numY > numZ ){
    return `number Y is greater than number Z`
  } else if ( numY < numZ ){
    return `number Z is greater than number Y`
  }
}

//2
function square( num ){
  return num * num ;
}

square();

//3
function isInRange( l , u , n){
  return l < n && u > n ;
}

isInRange();

//4
function add( numA , numB , ){
  return numA + numB;
}

add();

//5
function checkType(dataType){
  return typeof dataType;
}

checkType();

