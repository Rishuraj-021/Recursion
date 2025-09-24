# Recursion
## Aim:

To study and implement recursion in C++ programming and understand how a function can call itself to solve problems effectively.

## Theory:

Recursion is a powerful concept in programming where a function calls itself directly or indirectly to solve a problem. In C++, recursion helps break down complex problems into smaller, more manageable sub-problems.

A recursive function typically has two parts:

Base Case (Stopping Condition):
This prevents infinite recursion. It defines the smallest instance of the problem that can be solved directly without further recursion.

Recursive Case (Inductive Step):
The function reduces the problem into smaller sub-problems and calls itself to solve them.

### Types of Recursion

Direct Recursion – Function directly calls itself.

Indirect Recursion – Function A calls Function B, which again calls Function A.

Tail Recursion – The recursive call is the last statement in the function.

Head Recursion – The recursive call happens at the beginning of the function.

Tree Recursion – A function makes multiple recursive calls.

#### Advantages of Recursion

Simplifies code by replacing loops with self-calls.

Provides elegant solutions for problems like factorial, Fibonacci series, Tower of Hanoi, quicksort, mergesort, binary search, etc.

Natural fit for problems defined in terms of smaller subproblems (divide and conquer).

#### Disadvantages of Recursion

Uses more memory (stack space) compared to iteration.

Slower execution due to repeated function calls.

Risk of stack overflow if base case is missing or poorly defined.

Examples of Recursive Problems

Factorial of a number (n! = n × (n-1)!).

Fibonacci series.

Greatest Common Divisor (GCD) using Euclid’s algorithm.

Tree traversal in data structures.

Mathematical sequences and combinatorial problems.

## Algorithm:

Start

Define the problem in terms of smaller sub-problems.

Identify the base case (stopping condition).

Identify the recursive case (smaller problem to solve).

Write a function that:

Checks the base case → returns the solution directly.

Otherwise, calls itself with modified parameters (recursive case).

Continue until the base case is reached.

End
## Conclusion:

Recursion in C++ is a fundamental technique where a problem is solved by breaking it into smaller sub-problems. It provides elegant and simplified code for problems like factorial, Fibonacci, and tree traversals. However, recursion should be used carefully because it consumes more memory and can lead to stack overflow if not designed with a proper base case. Understanding recursion is essential for learning advanced concepts like divide-and-conquer algorithms, dynamic programming, and data structures.
