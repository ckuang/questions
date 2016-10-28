# Computer Science Quiz
## Question 1
What does code below return?
```js
[3, 10, 12, 15, 18].filter(function(num) {
  return num % 2 === 1
})
```
Answer:
<br />
<br />

## Question 2
What does code below return?
```js
['a', 'b', 'c'].reduce((a, b) => {
a[b] = true;
return a;
}, {})
```
Answer:
<br />
<br />
## Question 3 - BigO Notation
Why is O(2n) equivalent to 0(n)?
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
## Question 4
What are the time complexities of the following code examples?

Example A
```js
let arr = [1, 2, 3]
arr[2]
```
Example B
```js
let myColors = ['blue', 'yellow', 'red']
let yourColors = ['purple', 'orange', 'green']
for(let x = 0; x < myColors.length; x++) {
  for(let y = 0; y < yourColors.length; y++ ) {
    console.log("NEWCOLOR: " myColors[x] + yourColors[y] )
  }
}
```

Example C
```js
let myColors = ['blue', 'yellow', 'red']
for(let x = 0; x < myColors.length; x++) {
  console.log(myColors[x]);
}
for(let y = 0; y < yourColors.length; y++ ) {
  console.log(myColors[y]);
}
```

Example D
```js
let myColors = ['blue', 'yellow', 'red']
for(let x = 0; x < 10; x++) {
  for(let y = 0; y < 10; y++ ) {
    console.log(y);
  }
}

```
Answers -
<br/>
a)<br/><br/>
b)<br/><br/>
c)<br/><br/>
d)<br/>
## Question 5 - Stacks vs Queues
How is the stack data structure different from the queue? Explain in terms of FIFO or FILO.
Answer:
<br/><br/><br/><br/><br/><br/><br/><br/><br/>
## Question 6 - Queues
Explain how the typical customer service call center is actually an implementation of two queues. (hint: when you call the same call center, do you ever really get the same person helping you again?)
<br/><br/><br/><br/><br/><br/><br/><br/><br/>
## Question 7 - Recursion
Fill in the space to generate a recursive multiplication function.
```js
recursiveMultiply([]) // returns undefined
recursiveMultiply([1, 2, 3]) // returns 6
recursiveMultiply([1, 2, 3, 4]) // returns 24
```
```js
const recursiveMultiply = array => {
  if (array.length === 1) {
    return array[0]
  } else {
    //write code here







  }
}
```
## Question 8 - Functional Programming
Are the following functions pure? Why or why not?

Question A:
```js
let sodas = ['coke', 'sprite', 'fanta']
function addSoda() {
  sodas.push('dr. pepper');
}
addSoda();
```

Question B:
```js
function logToTen() {
  for(var i = 0; i < 10; i++){
    console.log(i)
  }
}
```

Question C:
```js
var sum = 0;
function add(a, b) {
  return a + b;
}
sum += add(10, 20);
```
Answers -
<br/>
a)<br/><br/><br/><br/><br/>
b)<br/><br/><br/><br/><br/>
c)<br/><br/><br/><br/><br/>

## Question 9
```js
myMin([4, 6, 7, 3, 1, 6, 3]) //returns 1
```
Write two `myMin()` functions: one that is O(n) and the other that is O(n^2).
<br/><br/><br/><br/><br/>
<br/><br/><br/><br/><br/>
<br/><br/><br/><br/><br/>
## Question 10
A palindrome is a word or phrase that is spelled the same forwards and backwards. Some examples of palindromes are 'mom', 'level', 'noon', and 'racecar'. Write a function called palindrome that takes in a string as an argument and returns true if it is a palindrome and false if it isn't. Do NOT use the `.reverse` method. Explain the time complexity of your solution in bigO notation.
```js
palindrome('mom'); //true
palindrome('airplane'); //false
palindrome('kayak'); //true
```
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
