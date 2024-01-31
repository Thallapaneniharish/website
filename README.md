Selecton sort correctness:

Base Case: The algorithm starts with an empty sorted portion and the entire array in the unsorted portion. The smallest element from the unsorted portion (the entire array) is moved to the sorted portion.

Inductive Step: Assume that after k iterations, the first k elements of the array are in their final sorted order. In the (k+1)th iteration, the smallest element from the remaining unsorted portion is selected and swapped with the first element of the unsorted portion. Now, the first (k+1) elements are in their final sorted order.

Termination: After n-1 iterations (where n is the length of the array), the entire array is in its final sorted order.
