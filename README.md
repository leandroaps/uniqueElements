# uniqueElements
This snippet uses ES6 Set and the …rest operator to get every element only once.

```
const uniqueElements = arr => [...new Set(arr)];
```

**Usage:**
```
uniqueElements([1, 2, 2, 3, 4, 4, 5]); // [1, 2, 3, 4, 5]
```
