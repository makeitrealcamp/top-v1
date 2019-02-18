# Árboles

Implementa un árbol binario que tenga los siguientes métodos:

* `add` - agrega un elemento en la ubicación correcta
* `traverseDFS` - recorre el árbol utilizando Depth First Search
* `traverseBFS` - recorre el árbol utilizando Breadth First Search
* `reverse` -

```javascript
const tree = new BinaryTree();
tree.add(4);
tree.add(2);
tree.add(7);
tree.add(1);
tree.add(3);
```

El árbol debe queda de la siguiente forma:

```
     4
   /   \
  2     7
 / \
1   3
```

```javascript
tree.add(5);
```

```
     4
   /   \
  2     7
 / \   /
1   3 5
```

```javascript
tree.traverseDFS(function(e) { console.log(e); });
// 4
// 2
// 1
// 3
// 7
// 5

tree.traverseBFS(function(e) { console.log(e); });
// 4
// 2
// 7
// 1
// 3
// 5
```

Al reversar el árbol debería quedar de la siguiente forma:

```
    4
  /   \
 7     2
  \   / \
   5 3   1
```

## Sudoku

Write a function called `sudoku` that receives a string representing a sudoku board and return true if it can be solved, false otherwise.

You must divide the string in groups of 9 that represent each row of the board. Spaces are represented with the dash character (`.`).

```javascript
var board = "...26.7.168..7..9.19...45..82.1...4...46.29...5...3.28..93...74.4..5..367.3.18...";
sudoku(board); // true

board = "..9.287..8.6..4..5..3.....46.........2.71345.........23.....5..9..4..8.7..125.3.."
sudoku(board); // false
```

# Gráfos

1. Write a function called `shortestPath` that receives three arguments: a graph (adjacency matrix), source node, and destination node. The function must return the value of the shortest path between the two nodes, or -1 if there is no route.

```javascript
const mat = [
  [0, 10, 15, 20],
  [5, 0, 9, 10],
  [6, 13, 0, 12],
  [8, 8, 9, 0],
]
shortestPath(mat); //
```

2. Write a function called `travelSalesman` that receives a graph (adjacency matrix) and a source node. The function must return the minimum cost of of visiting all the nodes.

```javascript

```
