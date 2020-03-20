#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) `O(n)` : the loop condition compares with n^3 but increment is by n^2  so we get linear scaling


b) `O(n log(n))` : Outer loop is O(n) because it iterates for every element in n and inner loop is log n because it's scalse logarithmically
since the loops are nested (inner is run for every iteration of outer) we multiply our run time


c) `O(n)` : we are calling `bunnieEars` n times since we are only decrementing by 1 and checking when it reaches zero to terminate.

## Exercise II

Binary search!
We start halfway up the building and drop an egg. If it breaks, disregard the upper floors, go lower by half the number of floors of interest.
If it doesn't break go up instead and disregard the lower floors, keep repeating until you reach the final floor.

Time complexity: `O(log n)`
