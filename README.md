# Basic Data Structures Assignment

In this assignment, we will delve into the basic data structures and perform some algorithms on them to reach our goal in each task.

Your assignment has been divided into two parts. The first part is about arrays, and you have to complete 5 tasks related to them. The second part involves implementing a class for a sparse matrix and creating some methods and operations for it.

## Tasks
The first part of your assignment is described below. Create a file for each task and implement the appropriate algorithm for it.

### 1. Find The Missing Number
Given an array containing n distinct numbers taken from 0, 1, 2, ..., n, find the one that is missing from the array.
```
input: [5, 2, 0, 3, 1] 
output: 4
```

### 2. Rotate Array
Given an array of integers of size n and an integer k, the task is to rotate the array elements to the right by k positions.
```
input: [1, 2, 3, 4, 5], k=2
output: [4, 5, 1, 2, 3]
```

### 3. Remove Duplicates From Sorted Array
Given a sorted array of integers, remove the duplicates in-place such that each element appears only once and returns the new length.
```
input: [1, 1, 2, 2, 3, 4, 5, 5]
output: 5
```

### 4. Merge Sorted Array
Given two sorted integer arrays num1 and num2, merge num2 into num1 as one sorted array.

```
inputs:
    num1 = [1, 2, 3]
    num2 = [2, 5, 6]

output:
    num1 = [1, 2, 2, 5, 6]
```

### 5. Maximum Subarray Sum
Given an integer array nums, find the contiguous subarray (containing at least one number) which has the largest sum and return its sum.
```
input = [-2, -1, -3, 4, -1, 2, 1, -5, 4]
output: 6 
subarray [4, -1, 2, 1] has the largest sum
```

## Sparse Matrix
After finishing the tasks, it's now time to work with a sparse matrix. In this part, you have to create a class for a sparse matrix and implement some methods to handle these items:

First, we will pass a normal matrix to your code, and you have to make that normal matrix a sparse matrix in your constructor. Next, implement the following methods:

### Transpose
This method will transpose your sparse matrix. An important note is that you are not allowed to use pre-built functions in this part.

### Change An Element 
This method takes the address of an element and its new value and changes the value to the new one.
 