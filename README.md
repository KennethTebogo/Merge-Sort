## Merge Sort Algorithm in Python
This repository contains an implementation of the Merge Sort algorithm in Python. Merge Sort is a divide-and-conquer algorithm that divides an array into two halves, recursively sorts them, and then merges the sorted halves.

## Features:

Efficient Sorting: Merge Sort works in O(n log n) time, making it one of the most efficient general-purpose sorting algorithms.
Stable Sort: It maintains the relative order of equal elements, making it stable.
Recursive Approach: It uses the divide-and-conquer approach to recursively split the array into smaller sub-arrays, and then merge them back into a sorted array.
## Algorithm Explanation

# 1. Divide:
The array is recursively split into two halves until each sub-array contains only one element (which is trivially sorted).

# 2. Merge:
The two sorted halves are merged back together into a single sorted array. Elements are compared, and the smaller element from either sub-array is placed in the merged array.

# 3. Combine:
Once all sub-arrays are merged, we obtain the fully sorted array.

# Time Complexity:
Best, Worst, and Average Case: O(n log n)
Merge Sort performs well even for large arrays and guarantees an O(n log n) time complexity in all cases, unlike algorithms like Quick Sort, which can degrade to O(n²) in the worst case.

# Usage
Clone the repository:
```
git clone https://github.com/yourusername/merge-sort-python.git
```
Navigate to the project directory:

```
cd merge-sort-python
```

# License
This project is licensed under the MIT License - see the LICENSE file for details.


