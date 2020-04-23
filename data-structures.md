# Data structures

## Working with Objects
sample object 
```javascript
let list = {
  value: 1,
  rest: {
    value: 2,
    rest: {
      value: 3,
      rest: null
    }
  }
};
```

**Getting information from the Object**
```javascript
console.log(list.value);
// → 1
```

## For loops
**Basic for loop over an array**
```javascript
for (let i = 0; i < arr.length; i++) {
  let entry = arr[i];
  // Do something with entry
}
```

**A simpler way to write a for loop in modern JavaScript**
```javascript
for (let entry of arr) {
  console.log(entry);
}
```


## Working with Arrays

## Add an item to the end of an Array
```javascript
arr.push('item');
```

### Remove first item from an Array
```javascript
arr.shift()
```

### Add one or more elements to the start of an Array
```javascript
arr.unshift('item1', 'item2')
```

### Removes last item from an Array
```javascript
arr.pop()
```

### Add or remove an item in an Array**
```javascript
arr.splice('spot in array', 'amount to remove', 'item to add')
```

**Examples**
Add item to array on position 1
```javascript
arr.splice(1, 0, 'item')
```

Replace item 2 in the array with a rocket
```javascript
arr.splice(2, 1, 🚀)
```
