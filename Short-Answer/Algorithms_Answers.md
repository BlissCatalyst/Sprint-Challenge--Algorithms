Add your answers to the Algorithms exercises here.

## Exercise I

a) is Linear time: O(n) because it counts upwards but only executes a constant time line. As (n) increases, time increases. Technically, we are multiplying n\*n in the constant assignment for a, but that only gets added to a. That comes to a + whatever number, which is still linear.

b) is quadradic time: O(n^2). Every time the outer loop executes, the loops on the inside keep running for every (n) that the outer loop executes.

c) is Linear time: O(n) because we are doing n-1, but that is the same as incrementing by 1 in a for loop. There are no internal loops.

## Exercise II

Because we are dropping eggs from floors, I'd start from the bottom floor `n[0]` first, throw the egg, then check to see if it broke. `if egg != broken: go up one floor and throw again`. `else: set f to current floor`.
