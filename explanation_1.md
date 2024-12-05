# Problem 1: Square Root of an Integer

## Explanation

The problem is to find the square root of a given integer. 

The problem can be solved using a binary search algorithm. The idea is to find the square root of the given number by searching for it in the range [0, number]. The search space is reduced by half in each iteration by comparing the square of the mid-point of the range with the given number. If the square of the mid-point is equal to the given number, then the mid-point is the square root of the number. If the square of the mid-point is less than the given number, then the square root lies in the right half of the range. If the square of the mid-point is greater than the given number, then the square root lies in the left half of the range.

### Time Complexity

The time complexity of the binary search algorithm is O(log n), where n is the given number. 

### Space Complexity
The space complexity is O(1) as the algorithm uses only a constant amount of space.
