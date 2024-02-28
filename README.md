# Merge Sort

This Python script implements the merge sort algorithm, a popular and efficient sorting technique that follows the divide and conquer strategy. It is particularly effective for sorting large datasets. The algorithm divides the unsorted list into n sublists, each containing one element (a list of one element is considered sorted), then repeatedly merges sublists to produce new sorted sublists until there is only one sublist remaining, which is the sorted list.

## How It Works

The `merge_sort` function recursively splits the array into two halves, sorts each half, and then merges the two sorted halves back together. 

Here is a breakdown of its process:

1. **Base Case**: If the array has 0 or 1 element, it is already sorted, so the function returns immediately.
2. **Divide**: The array is split into two halves.
3. **Conquer**: Recursively apply merge sort to each half.
4. **Combine**: Merge the two halves to produce a single sorted array.

## Usage

Simply run the script with Python. Before sorting, the script will print the unsorted array. After applying the merge sort algorithm, it will print the sorted array.