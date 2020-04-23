# Functions


## Function

**A simple function using parameter x**

```javascript
const square = function(x) {
  return x * x;
};

console.log(square(12));
// → 144
```


**Calling functions from functions**

```javascript
function chicken() {
  return egg();
}
function egg() {
  return chicken();q/rwq  0}
console.log(chicken() + " came first.");
// → ??
```


**Rest parameters** \
when the number of parapeters is unknown
```javascript
function max(...numbers) {
  let result = -Infinity;
  for (let number of numbers) {
    if (number > result) result = number;
  }
  return result;
}
console.log(max(4, 1, 9, -2));
// → 9
```

## Arrow Functions

**Instead of using the function keyword you can use =>**

```javascript
const power = (base, exponent) => {
  let result = 1;
  for (let count = 0; count < exponent; count++) {
    result *= base;
  }
  return result;
};
```


**Making arrow function shorter**

```javascript
const square1 = (x) => { return x * x; };
const square2 = x => x * x;
```


**If function has no paremeter**

```javascript 
const horn = () => {
  console.log("Toot");
};
```


## Ternary operator
```javascript
let status = (age >= 18) ? true : false;
```
