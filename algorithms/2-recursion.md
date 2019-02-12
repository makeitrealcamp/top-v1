# Recursion

1. Write a function called `factorial` that receives a number and returns the factorial of the number. The factorial is the multiplication of every positive number up to the number. For example, the factorial of 5 is 120 because `5 * 4 * 3 * 2 * 1 = 120`.

```javascript
console.log(factorial(4)); // 24
console.log(factorial(5)); // 120
console.log(factorial(6)); // 720
console.log(factorial(9)); // 362880
```

2. Write a function called `fibonacci` that receives a number and returns the `n` number of the [fibonacci](https://en.wikipedia.org/wiki/Fibonacci_number) sequence.

```javascript
console.log(fibonacci(0)); // 1
console.log(fibonacci(1)); // 1
console.log(fibonacci(4)); // 5
console.log(fibonacci(5)); // 8
```

3. Write a function called `flatten` that receives an array of arrays and returns a flattened array.

```javascript
console.log(flatten([[1, 2, 3], [4, 5]])); // [1, 2, 3, 4, 5]
console.log(flatten([[[1, [1.1]], 2, 3], [4, 5]])); // [1, 1.1, 2, 3, 4, 5]
```

4. Write a function called `collatz` that receives a number and returns the number of steps it takes to reach 1. The Collatz Conjecture (also called 3x + 1 problem) is the following:

Take any positive integer n. If n is even, divide n by 2 to get n / 2. If n is odd, multiply n by 3 and add 1 to get 3n + 1. Repeat the process indefinitely. The conjecture states that no matter which number you start with, you will always reach 1 eventually.

```javascript
console.log(collatz(12)); // 9
console.log(collatz(19)); // 20
console.log(collatz(27)); // 111
console.log(collatz(837799)); // 524
```

5. Write a function called `pascal` that receives a number and returns a string with a Pascal triangle.

```javascript
console.log(pascal(2));
// 1
// 1 1

console.log(pascal(5));
// 1
// 1 1
// 1 2 1
// 1 3 3 1
// 1 4 6 4 1
```
