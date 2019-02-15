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

# Gráfos

Implementa un gráfo 
