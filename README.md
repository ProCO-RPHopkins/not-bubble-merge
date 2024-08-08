# Merge Sort not Bubble Sort - W12D2

## Solution and Analysis

Sort array of integers in ascending order using merge sort. This approach is known for ability to sort large datasets quickly.

## Merge Sort

Divide-and-conquer algorithm that divides array into smaller sub-arrays, sorts sub-arrays, then merges them back together in sorted order. Process involves two main functions
    - merge_sort: Recursively splits the array and calls itself on the halves.
    - merge: Combines two sorted arrays into one sorted array.

Merge Sort Time Complexity: O(nlogn)
Array is split into halves (which takes logn splits) and each of the n
 elements is looked at during each merge step.

Space Complexity: O(n)
Additional space is needed for the temporary arrays used during the merging process.

## Bubble Sort

Time Complexity: O(n2)
In worst case, each element is compared with every other element.

Space Complexity: O(1)
Bubble Sort is an in-place sorting algorithm.

## Bubble Sort Does Not Work

Bubble sort cannot achieve required O(nlogn) time complexity. It has average and worst-case time complexity of O(n2)
, making it inefficient for sorting large arrays. Optimizations can improve performance but does not change overall time complexity of algorithm.
