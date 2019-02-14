# Data structures

Implement the following data structures:

### Linked list

```javascript
const list = new LinkedList();
list.add('a');
list.add('b');
list.add('d');
list.addAt(2, 'c');

list.valueAt(0); // 'a'

list.size(); // 4

list.forEach((val, i) => {
  console.log(`Value at position ${i}: ${val}`);
});

list.removeAt(0);
```

### A queue

```javascript
const queue = new Queue();
queue.push('a');
queue.push('b');
queue.push('c');

queue.get(); // "a"
queue.get(); // "b"
queue.get(); // "c"
```

### A stack

```javascript
const stack = new Stack();
queue.push('a');
queue.push('b');
queue.push('c');

stack.pop(); // "c"
stack.pop(); // "b"
stack.pop(); // "a"
```

### Trees and Graphs

Investigate how to implement a tree and a graph in JavaScript.

## Exercises

1. Add a method to the `LinkedList` called `reverse` that reverses all the nodes ()

2. Add a method called `middle` to the `LinkedList` that returns the value at the middle of the list.

3. Write a function called `isBalanced` that receives a string and returns true if the parenthesis are balanced, or false otherwise.

```javascript
isBalanced("(((())))"); // true
isBalanced("(((()))"); // false
isBalanced("())(()"); // false
```

4. Solve the [Tower of Hanoi](https://en.wikipedia.org/wiki/Tower_of_Hanoi) problem starting with three stacks of numbers.

The rules are the following:

1. Only one disk can be moved at a time.
2. Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or on an empty rod.
3. No larger disk may be placed on top of a smaller disk.

```javascript
const a = [4, 3, 2, 1];
const b = [];
const c = [];

// your code here

// a: []
// b: []
// c: [4, 3, 2, 1]
```

**Note:** You can also use the `Stack` data structure you created.
