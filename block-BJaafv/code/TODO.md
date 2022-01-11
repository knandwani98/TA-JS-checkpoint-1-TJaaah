1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
// It must comes return in function

// second
function sum(a, b) {
  console.log(a + b);
}
// This will give output not return 
```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`. 
first // a + b.
second // undefined 

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
// It will take just first two input as a parameter and make the statement valid and the output will be 36.


4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?
// Yes we can store function to a variable name "add" and we can remove fuction name also still we can pass functions with parameters by calling variable name.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
// function sayHello(name) {
  return "Hello ${name}"
}

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
// "Hello, John"


7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // It will alert "John"

showMessage(); // It will return "Hello, John"

alert(userName); // It will alert "John"
```

8. What is a Anonymous Function give example of three functions. 


It will make function declaired by variable and in that condition we can also remove function name because it will call by the variable name so function is waste anyway. examples,


let add = function (4, 5) {
  return a + b;
}

let sub = function (5, 4) {
  return a - b;
}

let mul = function (5, 2) {
  return a * b;
}

9. Can function declaration be a Anonymous Function? Explain 
It will make function declaired by variable and in that condition we can also remove function name because it will call by the variable name so function is waste anyway.


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


// "add" - return a + b 
// "typeOf" - return type of 
// "getMin" - retyrn minimum number
// "oddOrEven" - get odd number
// "isLeapYear" - get is it Leap Year or not.
```
