# BinaryHeap
JavaScript Bynary Heap

## Test

``` javascript
var queue = new BinaryHeap();

var a = ["Vincent", 20];
var b = ["Antonio", 355];
var c = ["Jess", 13];

queue.push(a);
queue.push(b);
queue.push(c);

while (!queue.isEmpty()) {
    console.log(queue.pop());
}

// Output
// Jess
// Vincent
// Antonio
```
