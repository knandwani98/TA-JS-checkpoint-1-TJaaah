1. Using loops take 10 inputs from user and find the average of all the numbers.

```js
let sum = 0;
for (let i = 1; i <= 10; i++) {
  let n = +prompt(`Enter a number`);
  sum += n;
}
let average = sum / 10;
console.log (average);

```
2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
// undefined, println doesnot defined
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.

```js
function getEvenSum (max = 10) {
  let sum = 0;
  for(let i = 1; i <= max; i++) {
    if (i % 2 === 0) {
      sum += i;
    }
  }
  return sum;
}

```
4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.

``` js
function getOddSum (max = 10) {
  let sum = 0;
  for(let i = 1; i <= max; i++) {
    if (i % 2 !== 0) {
      sum += i;
    }
  }
  return sum;
}

```
5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.

``` js
function getProductOfDigits(num){  
  let product = 1;
    while(num > 0){
      let remainder = (num % 10)
      num = num - remainder;
      product = product * remainder;
      num = num / 10;
    }
    return product;
    if(num < 0){
      return `Enter valid input`;
    }
  }
  
  ```

6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // 'Bigger than 5'
check(1); // 'Smaller than 5'
check(5); // 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // 'You are arya'
getOutput('John'); // 'You are john'
getOutput(); // 'Who are you'


Because we have use if conditions
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // It will log 'You are arya' but output will be 'Who are you'.
getOutput('John'); // It will log 'You are john' but output will be 'Who are you'.
getOutput(); // 'Who are you'



// Because log only logs it in browser console but return gives result in function case.
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
```js

Yes, we do have multiple return statements while using conditions like if else or switch.
for example : 
function isGreater (num1,num2) {
  if (num1 > num2) {
    return `${num1} is greater than ${num2}`;
  } else {
    return `${num2} is greater than ${num1}`;
  }
}
```


10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.

```js
for loop consist of both start end point of loop whereas while loop takes place when we dont know about the exact iterations like a book of pages in file.
```