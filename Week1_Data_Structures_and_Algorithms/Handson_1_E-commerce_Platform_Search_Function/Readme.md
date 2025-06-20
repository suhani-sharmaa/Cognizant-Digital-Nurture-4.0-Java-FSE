Week 1 - Data Structures and Algorithms  
Exercise 2: E-commerce Platform Search Function

Linear Search and Binary Search:
These are fundamental searching techniques used to locate elements within data structures like arrays.

Linear Search
Iterates through each element in the array.
Compares each element with the target value.
Returns the index if found. Otherwise, continues until the end.

Works on both sorted and unsorted arrays.
Simple but inefficient for large datasets.


Binary Search
Efficient search algorithm for sorted arrays.
Repeatedly divides the search space in half.
Compares the target value with the middle element.

Steps:
1. Find the middle element.
2. If it matches the target, return it.
3. If the target is smaller, search the left half.
4. If the target is larger, search the right half.

Time Complexities:
| Algorithm      | Best Case | Average Case | Worst Case |
|----------------|-----------|--------------|------------|
| Linear Search  | O(1)      | O(n)         | O(n)       |
| Binary Search  | O(1)      | O(log n)     | O(log n)   |