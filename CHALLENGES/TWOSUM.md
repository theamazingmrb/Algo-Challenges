# TWO SUM

Write a function that takes in a non-empty array of distinct integers and an integer representing a target sum. If any two numbers in the input array sum up to the target sum, the function should return them in an array, in any order. If no two numbers sum up to the target sum, the function should return an empty array.


Note that the target sum has to be obtained by summing two different integers in the array; you can't add a single integer to itself in order to obtain the target sum.

You can assume that there will be at most one pair of numbers summing up to the target sum.


## Sample Input

```js

aarray = [ 3, 5, -4, 8, 11, 1, -1, 6 ]
targetSum = 10

```

## Sample Output

```js

[-1, 11]
// the numbers could be in reverse order

```
### Sample Test Caese

1. 
```js

aarray = [ 3, 5, -4, 8, 11, 1, -1, 6 ]
targetSum = 10

output answer = [ -1, 11 ]

```

2. 
```js

aarray = [ 2, 8, 3, 7, 6, 0, -1 ]
targetSum = 7

output answer = [ 8, -1 ]

```

3. 
```js

input array = [ 5, 8, 0, 10, 22, 5, 3 ]
targetSum = 18

output answer = [ 10, 8 ]

```