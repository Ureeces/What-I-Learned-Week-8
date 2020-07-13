# What I Learned Week 8

## For-of

The for-of loop is another way of using a for loop. It works similarly to a for-loop, with the following differences:
* It requires a string, array, or object
* It will directly loop through each element/character in said variable, rather than using an index
* Allows for easy reading and tracking of variables

Syntax: `for(let char of str) {}`

## Array filtering

Array filtering is basically what it sounds like - filtering an array to find the elements that match a certain condition.

Syntax: `arr.filter(element => condition)`

## Math.random()

This makes a random number. It is possible to create a random number using this syntax:

`(Math.random * max) + (min + 1);

*Note that `Math.floor` is necessary to make a non-decimal number in some cases