# Insertion Sort Project

## Project 1

### [22,27,16,2,18,6] -> Insertion Sort

1. Write the stages of the above given array according to the sort type

2. Write the Big-o notation

3. Time Complexity: average case: The number we are looking for is in the middle, Worst case: The number we are looking for is at the end, Best case: The number we are looking for is at the beginning of the array

4. After the Array is Sorted, write which case does the 18th number fall into?

### [7,3,5,8,2,9,4,15,6] of the array write the first 4 steps for Insertion Sort
---

## Answers

1. **First step** -> [2,27,16,22,18,6] we found the smallest number and we brought it to the head of the array

**Second Step** -> [2,6,16,22,18,27] after the first step we found second smallest number and we brought 2. row. Do not touch if already 2. row the smallest 2nd element of the array

**Third Step** -> [2,6,16,22,18,27] we looked 3rd element of the array and 3rd number already 3rd smallest number then we do not touch now go to step4

**Fourth Step** -> [2,6,16,18,22,27] we looked 4th element of the array and we changed it with the number that came before it and we sorted by Insertion sorting logic thats all

---

2. Big-o notation

[22,27,16,2,18,6] -> n

[2,27,16,22,18,6] -> n-1

[2,6,16,22,18,27] -> n-2

[2,6,16,18,22,27] -> 1

n+(n-1)+(n-2)+.....+1 = n.(n+1)/2 

**O(n2)**

---

3. [22,27,16,2,18,6] Time complexity for this array we expect it to happen **avarage case**

4. [2,6,16,18,22,27] after the array is sorted, the number 18 is in the middle of the array, so it enters the average case

---

### [7,3,5,8,2,9,4,15,6] of the array write the first 4 steps for Insertion Sort

1. [2,3,5,8,7,9,4,15,6]

2. [2,3,4,8,7,9,5,15,6]

3. [2,3,4,5,7,9,8,15,6]

4. [2,3,4,5,7,6,8,15,7]
---
[patika.dev](https://app.patika.dev/)


