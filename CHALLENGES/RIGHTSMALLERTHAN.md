# Right Smaller Than


Write a function that takes in an array of integers and returns an array of the same length, where each element in the output array corresponds to the number of integers in the input array that are to the right of the relevant index and that are strictly smaller than the integer at that index.

## Sample Input

```js

array = [ 8, 5, 11, -1, 3, 4, 4 ]

```

## Sample Output

```js

[ 5, 4, 4 , 0, 1, 1, 0 ]
// There are 5 integers smaller than 8 to the right of it.
// There are 4 integers smaller than 4 to the right of it.
// There are 4 integers smaller than 11 to the right of it.

```
### Sample Test Caese

1. 
```js

input array = [ 8, 5, 11, -1, 3, 4, 4 ]

output answer = [ 5, 4, 4 , 0, 1, 1, 0 ]

```

2. 
```js

input array = [ 15, 1, 72, 8, 11, 68, -6 ]

output answer = [ 4, 1, 4, 1, 1, 1, 0 ]

```

3. 
```js

input array = [ 5, 1, 0, 10, 22, 5, 3]

output answer = [ 3, 1, 0, 2, 2, 1, 0 ]

```