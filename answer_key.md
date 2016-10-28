# Weekend Assignments
* Read Chapter 1 of [Learning SQL](http://www.r-5.org/files/books/computers/languages/sql/mysql/Alan_Beaulieu-Learning_SQL-EN.pdf)
* Complete tutorials 0, 1, 2, 3 of [SQL Zoo](http://sqlzoo.net/)
* Find the definition of the following vocabulary words:
  - MongoDB: What good things do people have to say about Mongo? What bad things?
  - PostgreSQL: What good things do people have to say about Mongo? What bad things?
  - SQL - What does SQL stand for?
  - table - What is a database table?
  - schema - What is a database schema?
  - model  - What is a database model?
Write your answers in this [google form](https://docs.google.com/forms/d/e/1FAIpQLSetj9G1dm4k1UUHnvZM1w6S4igJfSD0TxPUJPYgeNZ6Reit2g/viewform).

# Computer Science Quiz Answer Key

## Question 1
Answer: [3, 15]

## Question 2
Answer: {a: true, b: true, c: true}

## Question 3
Answer: As the input size increases, the relationship between the input and run time is linear. With bigO notation, coefficients can be ignored because it doesn't affect the actual relationship.

## Question 4
Answer:
a) O(1) - indexing into an array is constant time.
b) O(n^2) - nested loops are O(n^2)
c) O(n) - side by side loops are O(2n), which evaluates to O(n)
d) O(1) - trick question: there are only 100 operations occurring in the function.

## Question 5
Stacks are first in last out. Queues are first in first out.

## Question 6
The customers are in one queue. The representatives at the call center are also in another queue.

## Question 7
Answer: We're taking off the last element of the array and multiplying it with the first element of the array. The resulting array is then passed into recursive function until it hits the base case of an array with length 1.
```js
const recursiveMultiply = array => {
  if (array.length === 1) {
    return array[0]
  } else {
    var last = array.pop()
    array[0] = array[0] * last
    return recursiveMultiply(array)
  }
}
```

## Question 8
Answer:
a) Impure - mutates the sodas array (side effect)
b) Impure - the console.log() is a side effect
c) Pure - the add function itself always returns the same output and there are no side effects

## Question 9
Answer:
```js
function myMin(arr) {
  var min = arr[0]
  for(var i = 1; i < arr.length; i++) {
    if (min > arr[i]) {
      min = arr[i]
    }
  }

  return min
}
```

## Question 10
```js
function isPalindrome(string) {
  var reversed = ""
  for (var i = string.length - 1; i < string.length; i--) {
    reversed += string[i]
  }

  return reversed === string

}

```
