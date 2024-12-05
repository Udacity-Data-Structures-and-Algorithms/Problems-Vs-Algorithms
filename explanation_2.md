# Problem 2: Search in Rotated Sorted Array

## Explanation

The problem is to search for a target element in a rotated sorted array. The array is rotated at an unknown pivot point, and the elements are sorted in ascending order. The problem can be solved using a modified binary search algorithm. The idea is to find the pivot point of the rotated array and then perform a binary search on the appropriate half of the array based on the target element.


### Time Complexity

The time complexity of the binary search algorithm is O(log n), where n is the number of elements in the array.

### Space Complexity

The space complexity is O(1) as the algorithm uses only a constant amount of space.