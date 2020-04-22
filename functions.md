# Functions

Ternary operator
let status = (age >= 18) ? true : false;

use === and !== to also comp


combine strigns and variables usign ``
`Hi! I'm ${myName}!`


for loop
for(i of cats) {
  console.log(i);
}


Functions

This
const array1 = [1, 2, 3, 4];
let sum = array.reduce(function(a, b) {
  return a + b;  
});

could be this
const array = [1, 2, 3, 4];
let sum = array.reduce((a, b) =>
  a + b
);


More arrow functions
const square1 = (x) => { return x * x; };
const square2 = x => x * x;
When an arrow function has no parameters at all, its parameter list is just an empty set of parentheses.

const horn = () => {
  console.log("Toot");
};



Workign with arrays

pushes to the end of the array
pets.push('cat');

pets.pop()

pets.shift()

pets.unshift()

pets.splice()

