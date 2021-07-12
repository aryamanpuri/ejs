# ejs[https://jovial-montalcini-0f1dd3.netlify.app/]
ECMASCRIPT TO COMMON JAVASCRIPT 

# Input :- 
1. import react from "fs";
2. import {FormGroup,
           FormControl,
           InputGroup, 
           Glyphicon
                  }    from "react-bootstrap";
# Output :- 

1. const react = require("fs").default;
2. const { FormGroup,
           FormControl, 
           InputGroup,
           Glyphicon 
            } =  require("react-bootstrap");   

# Input :-

1. import { resolve as resolvePath } from "path";

# Output :- 

1. const { resolve: resolvePath } = require("path");

# Input :- 
 1. export function Fibonacci() {
    const number = parseInt(prompt('Enter the number of terms: '));
let n1 = 0, n2 = 1, nextTerm;

console.log('Fibonacci Series:');

for (let i = 1; i <= number; i++) {
    console.log(n1);
    nextTerm = n1 + n2;
    n1 = n2;
    n2 = nextTerm;
}

# Output :- 

1. function Fibonacci() {
    const number = parseInt(prompt('Enter the number of terms: '));
let n1 = 0, n2 = 1, nextTerm;

console.log('Fibonacci Series:');

for (let i = 1; i <= number; i++) {
    console.log(n1);
    nextTerm = n1 + n2;
    n1 = n2;
    n2 = nextTerm;
}

module.exports = {
  Fibonacci
}

# Input :- 

1. export function Square(x){
    Return x*x;
}

# Output :- 


1.function Square(x) {
    return x*x
}

module.exports = {
  Fibonacci,
  Square
}
