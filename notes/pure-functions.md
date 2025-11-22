# Pure Functions & Immutability Problems

## Basic Pure Functions (1-10)

### 1. Circle Area Calculator

**Problem**: Write a pure function to calculate the area of a circle given its radius.
**Sample Input 1**: `radius = 5`  
**Expected Output 1**: `78.53981633974483`
**Sample Input 2**: `radius = 3`  
**Expected Output 2**: `28.274333882308138`

### 2. Fibonacci Number

**Problem**: Create a pure function that returns the nth Fibonacci number (0-indexed).
**Sample Input 1**: `n = 5`  
**Expected Output 1**: `5`
**Sample Input 2**: `n = 10`  
**Expected Output 2**: `55`

### 3. Palindrome Checker

**Problem**: Implement a pure function to check if a string is a palindrome (case-insensitive).
**Sample Input 1**: `str = "racecar"`  
**Expected Output 1**: `true`
**Sample Input 2**: `str = "hello"`  
**Expected Output 2**: `false`

### 4. Array Maximum

**Problem**: Write a pure function to find the maximum value in an array without using built-in max.
**Sample Input 1**: `nums = [3, 7, 2, 9, 1]`  
**Expected Output 1**: `9`
**Sample Input 2**: `nums = [-5, -2, -10, -1]`  
**Expected Output 2**: `-1`

### 5. Vowel Counter

**Problem**: Create a pure function that counts vowels in a string (case-insensitive).
**Sample Input 1**: `str = "hello world"`  
**Expected Output 1**: `3`
**Sample Input 2**: `str = "AEIOU"`  
**Expected Output 2**: `5`

### 6. String Reverser

**Problem**: Implement a pure function to reverse a string without mutation.
**Sample Input 1**: `str = "hello"`  
**Expected Output 1**: `"olleh"`
**Sample Input 2**: `str = "functional"`  
**Expected Output 2**: `"lanoitcnuf"`

### 7. Factorial Calculator

**Problem**: Write a pure function to calculate factorial of a number.
**Sample Input 1**: `n = 5`  
**Expected Output 1**: `120`
**Sample Input 2**: `n = 0`  
**Expected Output 2**: `1`

### 8. Prime Checker

**Problem**: Create a pure function that checks if a number is prime.
**Sample Input 1**: `n = 17`  
**Expected Output 1**: `true`
**Sample Input 2**: `n = 15`  
**Expected Output 2**: `false`

### 9. GCD Calculator

**Problem**: Implement a pure function to find GCD of two numbers.
**Sample Input 1**: `a = 48, b = 18`  
**Expected Output 1**: `6`
**Sample Input 2**: `a = 17, b = 13`  
**Expected Output 2**: `1`

### 10. Temperature Converter

**Problem**: Write a pure function to convert Celsius to Fahrenheit.
**Sample Input 1**: `celsius = 0`  
**Expected Output 1**: `32`
**Sample Input 2**: `celsius = 25`  
**Expected Output 2**: `77`

## Avoiding Mutation (11-20)

### 11. Array Insert

**Problem**: Implement array insertion at specific index without mutating original array.
**Sample Input 1**: `arr = [1, 2, 4, 5], index = 2, value = 3`  
**Expected Output 1**: `[1, 2, 3, 4, 5]`
**Sample Input 2**: `arr = ['a', 'c'], index = 1, value = 'b'`  
**Expected Output 2**: `['a', 'b', 'c']`

### 12. Array Remove

**Problem**: Create a function to remove element at index without mutating original array.
**Sample Input 1**: `arr = [1, 2, 3, 4, 5], index = 2`  
**Expected Output 1**: `[1, 2, 4, 5]`
**Sample Input 2**: `arr = ['a', 'b', 'c'], index = 0`  
**Expected Output 2**: `['b', 'c']`

### 13. Object Property Update

**Problem**: Write a function to update object property without mutation (return new object).
**Sample Input 1**: `obj = {name: 'John', age: 25}, key = 'age', value = 26`  
**Expected Output 1**: `{name: 'John', age: 26}`
**Sample Input 2**: `obj = {x: 1, y: 2}, key = 'z', value = 3`  
**Expected Output 2**: `{x: 1, y: 2, z: 3}`

### 14. Array Sort

**Problem**: Implement array sorting without mutating the original array.
**Sample Input 1**: `arr = [3, 1, 4, 1, 5]`  
**Expected Output 1**: `[1, 1, 3, 4, 5]`
**Sample Input 2**: `arr = ['banana', 'apple', 'cherry']`  
**Expected Output 2**: `['apple', 'banana', 'cherry']`

### 15. Array Merge

**Problem**: Create a function to merge two arrays without mutation.
**Sample Input 1**: `arr1 = [1, 2, 3], arr2 = [4, 5, 6]`  
**Expected Output 1**: `[1, 2, 3, 4, 5, 6]`
**Sample Input 2**: `arr1 = ['a'], arr2 = ['b', 'c']`  
**Expected Output 2**: `['a', 'b', 'c']`

### 16. Array Prepend

**Problem**: Write a function to add element to beginning of array without mutation.
**Sample Input 1**: `arr = [2, 3, 4], element = 1`  
**Expected Output 1**: `[1, 2, 3, 4]`
**Sample Input 2**: `arr = ['b', 'c'], element = 'a'`  
**Expected Output 2**: `['a', 'b', 'c']`

### 17. Nested Object Update

**Problem**: Implement nested object update without mutation.
**Sample Input 1**: `obj = {user: {name: 'John', age: 25}}, path = ['user', 'age'], value = 26`  
**Expected Output 1**: `{user: {name: 'John', age: 26}}`
**Sample Input 2**: `obj = {a: {b: {c: 1}}}, path = ['a', 'b', 'c'], value = 2`  
**Expected Output 2**: `{a: {b: {c: 2}}}`

### 18. Remove Duplicates

**Problem**: Create a function to remove duplicates from array without mutation.
**Sample Input 1**: `arr = [1, 2, 2, 3, 3, 3, 4]`  
**Expected Output 1**: `[1, 2, 3, 4]`
**Sample Input 2**: `arr = ['a', 'b', 'a', 'c', 'b']`  
**Expected Output 2**: `['a', 'b', 'c']`

### 19. Array Flatten

**Problem**: Write a function to flatten nested array without mutation.
**Sample Input 1**: `arr = [1, [2, 3], [4, [5, 6]]]`  
**Expected Output 1**: `[1, 2, 3, 4, 5, 6]`
**Sample Input 2**: `arr = [[1, 2], [3, 4]]`  
**Expected Output 2**: `[1, 2, 3, 4]`

### 20. Array Rotation

**Problem**: Implement array rotation (right) without mutation.
**Sample Input 1**: `arr = [1, 2, 3, 4, 5], k = 2`  
**Expected Output 1**: `[4, 5, 1, 2, 3]`
**Sample Input 2**: `arr = ['a', 'b', 'c'], k = 1`  
**Expected Output 2**: `['c', 'a', 'b']`

## Referential Transparency (21-25)

### 21. Pure Random Number Generator

**Problem**: Refactor an impure random function to be pure by accepting a seed value.
**Sample Input 1**: `seed = 12345, min = 1, max = 10`  
**Expected Output 1**: `{value: 6, nextSeed: 1406932606}`
**Sample Input 2**: `seed = 54321, min = 0, max = 100`  
**Expected Output 2**: `{value: 42, nextSeed: 470211272}`

### 22. Logger Function

**Problem**: Convert a function that uses console.log to return result instead.
**Sample Input 1**: `operation = 'add', a = 5, b = 3`  
**Expected Output 1**: `{result: 8, log: 'Adding 5 + 3 = 8'}`
**Sample Input 2**: `operation = 'multiply', a = 4, b = 7`  
**Expected Output 2**: `{result: 28, log: 'Multiplying 4 * 7 = 28'}`

### 23. Pure Counter

**Problem**: Refactor a function that modifies global state to be pure.
**Sample Input 1**: `currentCount = 5, operation = 'increment'`  
**Expected Output 1**: `6`
**Sample Input 2**: `currentCount = 10, operation = 'decrement'`  
**Expected Output 2**: `9`

### 24. Time-based Calculation

**Problem**: Convert a function that uses Date.now() to accept timestamp parameter.
**Sample Input 1**: `timestamp = 1609459200000, days = 30`  
**Expected Output 1**: `1612137600000`
**Sample Input 2**: `timestamp = 1609459200000, days = -7`  
**Expected Output 2**: `1608854400000`

### 25. Pure Data Processor

**Problem**: Refactor a function that reads from external API to accept data parameter.
**Sample Input 1**: `userData = [{name: 'John', age: 25}, {name: 'Jane', age: 30}], minAge = 26`  
**Expected Output 1**: `[{name: 'Jane', age: 30}]`
**Sample Input 2**: `userData = [{name: 'Bob', score: 85}, {name: 'Alice', score: 92}], minScore = 90`  
**Expected Output 2**: `[{name: 'Alice', score: 92}]`

## Persistent Data Structures (26-30)

### 26. Immutable Stack

**Problem**: Implement a simple immutable stack with push/pop operations.
**Sample Input 1**: `stack = [1, 2, 3], operation = 'push', value = 4`  
**Expected Output 1**: `{newStack: [1, 2, 3, 4], originalStack: [1, 2, 3]}`
**Sample Input 2**: `stack = [1, 2, 3], operation = 'pop'`  
**Expected Output 2**: `{newStack: [1, 2], poppedValue: 3, originalStack: [1, 2, 3]}`

### 27. Immutable Queue

**Problem**: Create an immutable queue with enqueue/dequeue operations.
**Sample Input 1**: `queue = [1, 2, 3], operation = 'enqueue', value = 4`  
**Expected Output 1**: `{newQueue: [1, 2, 3, 4], originalQueue: [1, 2, 3]}`
**Sample Input 2**: `queue = [1, 2, 3], operation = 'dequeue'`  
**Expected Output 2**: `{newQueue: [2, 3], dequeuedValue: 1, originalQueue: [1, 2, 3]}`

### 28. Immutable Binary Tree

**Problem**: Implement an immutable binary tree with insert operation.
**Sample Input 1**: `tree = {value: 5, left: {value: 3}, right: {value: 7}}, newValue = 6`  
**Expected Output 1**: `{value: 5, left: {value: 3}, right: {value: 7, left: {value: 6}}}`
**Sample Input 2**: `tree = {value: 10}, newValue = 5`  
**Expected Output 2**: `{value: 10, left: {value: 5}}`

### 29. Immutable Linked List

**Problem**: Create an immutable linked list with append/prepend operations.
**Sample Input 1**: `list = {value: 1, next: {value: 2, next: null}}, operation = 'append', value = 3`  
**Expected Output 1**: `{value: 1, next: {value: 2, next: {value: 3, next: null}}}`
**Sample Input 2**: `list = {value: 2, next: null}, operation = 'prepend', value = 1`  
**Expected Output 2**: `{value: 1, next: {value: 2, next: null}}`

### 30. Immutable Map

**Problem**: Implement an immutable map/dictionary with set/get operations that preserves previous versions.
**Sample Input 1**: `map = {a: 1, b: 2}, operation = 'set', key = 'c', value = 3`  
**Expected Output 1**: `{newMap: {a: 1, b: 2, c: 3}, originalMap: {a: 1, b: 2}}`
**Sample Input 2**: `map = {x: 10, y: 20}, operation = 'set', key = 'x', value = 15`  
**Expected Output 2**: `{newMap: {x: 15, y: 20}, originalMap: {x: 10, y: 20}}`
