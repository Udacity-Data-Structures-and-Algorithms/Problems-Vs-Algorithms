# Problem 3: Rearrange Array Elements

## Explanation

The problem is to rearrange the elements of an array to form the largest possible number. The input is an array of positive integers and the output is the largest number that can be formed by rearranging the elements of the array into two numbers. The two numbers are formed by concatenating the elements of the array in such a way that the sum of the two numbers is the largest possible number.

The solution is to sort the array in descending order and then form two numbers by concatenating the elements of the array. The first number is formed by concatenating the elements at even indices and the second number is formed by concatenating the elements at odd indices. The two numbers are then returned as a tuple.

## Time Complexity

The time complexity of the solution is O(n log n) because the array is sorted using the merge sort algorithm.

## Space Complexity

The space complexity of the solution is O(n) because the array is sorted in place.