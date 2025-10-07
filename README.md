Program 1 – Selection Sort
Aim:

To sort an array of elements using the Selection Sort algorithm.

Software Used:

Visual Studio Code (VS Code)

Theory:

Selection Sort is a simple, comparison-based sorting technique.
It works by dividing the array into a sorted and an unsorted part.
In each iteration, it selects the minimum element from the unsorted portion and swaps it with the first unsorted element, gradually expanding the sorted portion.

Best suited for small datasets

Time Complexity: O(n²)

Does not require extra space (in-place sort)

Algorithm:

Start

Assume the first element is the minimum

Traverse the unsorted part to find the actual minimum

Swap the found minimum with the first unsorted element

Move the sorted/unsorted boundary forward

Repeat steps 2–5 until the entire array is sorted

Stop

Conclusion:

Implemented Selection Sort successfully

Easy to understand and code

Suitable for small datasets

Not efficient for large arrays due to quadratic time complexity

Program 2 – Bubble Sort
Aim:

To sort an array of elements using the Bubble Sort algorithm.

Software Used:

Visual Studio Code (VS Code)

Theory:

Bubble Sort is a simple sorting algorithm that repeatedly compares and swaps adjacent elements if they are in the wrong order.
With each pass, larger elements "bubble up" to their correct position at the end of the array.

Ideal for small or nearly sorted arrays

Time Complexity: O(n²) in worst and average cases

Space Complexity: O(1) (in-place sorting)

Algorithm:

Start

Compare adjacent elements

If the first is greater than the second, swap them

Continue this for all elements in the array

After each pass, the largest unsorted element moves to its correct position

Repeat the process until no swaps occur in a pass

Stop

Conclusion:

Bubble Sort was successfully implemented

Very easy to code and understand

Inefficient for large datasets due to high time complexity

Program 3 – Quick Sort
Aim:

To sort an array of elements using the Quick Sort algorithm.

Software Used:

Visual Studio Code (VS Code)

Theory:

Quick Sort is an efficient, divide-and-conquer sorting algorithm.
It works by selecting a pivot element and partitioning the array such that elements smaller than the pivot are placed on the left, and elements greater than the pivot are on the right.
The process is then recursively applied to the subarrays.

Much faster than Bubble and Selection Sort for large arrays

Average Time Complexity: O(n log n)

Worst-case Time Complexity: O(n²) (rare, can be avoided with good pivot selection)

In-place algorithm, does not need extra storage

Algorithm:

Start

Select a pivot element

Partition the array so that:

Elements less than pivot → left

Elements greater than pivot → right

Recursively apply Quick Sort on the left and right subarrays

Stop recursion when subarrays have one or zero elements

Stop

Conclusion:

Successfully implemented Quick Sort

Highly efficient for large datasets

Demonstrates the effectiveness of the divide-and-conquer approach

Preferred over simpler sorts for performance-critical applications
