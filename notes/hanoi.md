# Hanoi Tower

```javascript
function hanoi(source, aux, dest, level) {
  // caso base: cuando tiene uno
  if (level == 1) {
    dest.push(source.pop());
    return;
  }

  hanoi(source, dest, aux, level - 1);
  dest.push(source.pop());
  hanoi(aux, source, dest, level - 1);
}

var source = [1, 2, 3, 4];
var aux = [];
var dest = [];
hanoi(source, aux, dest, source.length);
```

Mover las dos primeras de `source` a `aux`
Mover el tercer disco
Mover las dos primeras de `aux` a `dest`


Mover la primera de `aux` a `source`
Mover el segundo disco
Mover la primera de `source` a `dest`
