# Big-O Notation

## O (1)
### Constant Time
examples: 
* arithmetic operations
* varialbe assignment 
* accessing elements in an array (by index) or an object (by key)

code example: 
```javascript
function addUpTo(n) {
    return n * (n+1) / 2;
}
```

## O (log n)
### Logarithmic Time

## O (n)
### Linear Time

```javascript
function addUpTo(n) {
    let total = 0;
    for (let i = 0; i <= n; i++>) {
        total += 1;
    }
    return total;
}
```

## O (n^2)
### Quadratic Time

```javascript
function printAllPairs(n) {
    for (let i = 0; i < n; i++>) {
        for (let j = 0; j < n; j++>) {
            console.log(i, j);
        }
    }
}
```