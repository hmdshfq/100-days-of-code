# 100 Days Of Code - Log

### Day 029: November 29, Sunday

**Today's Progress**: Today I learned about useReducer() function in React. I also learned about the reducer() function in JavaScript.

**Thoughts** Althought I've learned the basic concept of useReducer() hook *function* in React, I still have to practice it a lot. 

The reduce() method in JavaScript on the other hand is very easy to understand. It executes a reducer function on each element of an array. This functions churns out a single value output. The reducer function takes four arguments:

- Accumulator
- Current Value
- Current Index
- Source Array

Your reducer function's returned value is assigned to the accumulator, whose value is remembered across each iteration throughout the array, and ultimately becomes the final, single resulting value.

```js
const reducer = (accumulator, currentValue) => accumulator + currentValue;
```
Following is an example of the complete code from Mozilla Developers blog
```js
const array = [1, 2, 3, 4, 5]
const reducer = (accumulator, currentValue) => accumulator + currentValue;

console.log(array.reduce(reducer)); // Outputs 15

console.log(array.reduce(reducer, 10)); // Outputs 25
```

**Link(s) to work**
1. [GitHub repository for React's Context API and useReducer() Hook](https://github.com/hmdshfq/React-Context-API-and-useReducer)
