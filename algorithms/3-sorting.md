# Sorting algorithms

Implement the following sorting algorithms based on the description shown [here](https://guias.makeitreal.camp/algoritmos/ordenamiento).

* Selection sort
* Insertion sort
* Bubble sort
* Merge sort
* Quick sort

## Exercises

1. Modify the insertion sort algorithm to sort an array in descending order.

```javascript
descendingInsertionSort([1, 2, 3, 4]); // [4, 3, 2, 1]
descendingInsertionSort([5, 3, 8, 1]); // [8, 5, 3, 1]
```

2. There are `N` people in a queue. Each person wears a sticker with their initial position in the queue starting from `1` to `N`. Any person in the queue can bribe the person directly in front of them to swap positions. One person can bribe at most two others. Even if they swap positions they will keep their original sticker.

For example, if `N` is 8 and person 5 bribes person 4, the queue will look like this: 1, 2, 3, 5, 4, 6, 7, 8.

Given a queue determine the minimum number of bribes that took place to get the queue to the current state. If the configuration is not possible return -1.

```javascript
numberOfBribes([2, 1, 5, 3, 4]); // 3
numberOfBribes([2, 5, 1, 3, 4]); // -1
```
