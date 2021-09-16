1. Using loops take 10 inputs from user and find the average of all the numbers.

```js

let a = 0

for ( i = 0 ; i < 10 ; i = ++i ){
  let input = prompt(`Enter the the number :`);

  a = a + i;
}
let average = a / 10 ;

console.log(average);

```



2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```
this code will not pass, it throw an error println is not define.

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

```js
function getEvenSum(max = 10){

let c = 0;
 for ( i = 2 ; i <= max ; i += 1){

       if ( i %2 == 0 ){
         c = c + i ;
       }
    }
       return e ;
}
```


4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

```js
function getOddsum(max = 10)

let c = 0:
 for ( i = 1 ; i <= max ; i += 1 ){

   if ( i %2 != 0 ){
     c + c + i ;
   }
     return c ;
 }
```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

```js
function getProductofDigits( num ){

  if( num < 0 ){
    return `not a valid input`;
  } 
  if ( num == 0){
    return 0;
  }

  let c = 1;
  while ( num > 0 ){

    c = c * ( num % 10 );

    num = parseInt(num / 10);

      }     
      return c ;
}

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

6. What will be the output of the following code below in multiple conditions? Explain with reason?

``js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // `Bigger than 5`
check(1);  // `Smaller than 5`
check(5);  //   5 
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'you are arya`
getOutput('John'); // `you are john`
getOutput(); // `Who are you`
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // 'you are arya` - because if name === `Arya` then it console 'You are arya'
getOutput('John'); // `you are john` - because if name === `john` then it console 'You are john'
getOutput(); // `Who are you` - because getOutput() is empty it or anything else enter then it return 'Who are you`
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.

The function have multiple return statement it is poosible if  we apply condition inside the function statement.

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.

The difference between `for` loop and `while` loop : 
In `for` loop it will run for the number of iterations set in the initial condition.
In `while` loop it will run for condition set in the initial statement.

for ( initializer ; condition ; incremental/decremental )

while ( statement )