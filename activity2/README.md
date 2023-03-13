# Activities

## Task 1

- Refer to the following link. Discuss the characteristics of Greedy approach:
  https://www.geeksforgeeks.org/greedy-approach-vs-dynamic-programming/
  the answer:
  A problem that can be solved using the Greedy approach follows the below-mentioned properties:

Optimal substructure property.
Minimization or Maximization of quantity is required.
Ordered data is available such as data on increasing profit, decreasing cost, etc.
Non-overlapping subproblems.

## Task 2

- Explain how the code in `./src/fkp.cp`p works. Refer to the following link:
  https://www.geeksforgeeks.org/fractional-knapsack-problem/

## Task 3

- Explain how the code in `./src/asp.cpp` works. Refer to the following link:
  https://www.geeksforgeeks.org/activity-selection-problem-greedy-algo-1/

## Task 4: Individual (at home)

- Refer to the following link. Explain the differences between Greedy Algorithm and Dynamic Programming
  https://www.geeksforgeeks.org/greedy-approach-vs-dynamic-programming/
  the answer:
  Feature

Greedy method Dynamic programming
Feasibility
In a greedy Algorithm, we make whatever choice seems best at the moment in the hope that it will lead to global optimal solution. In Dynamic Programming we make decision at each step considering current problem and solution to previously solved sub problem to calculate optimal solution .
Optimality
In Greedy Method, sometimes there is no such guarantee of getting Optimal Solution. It is guaranteed that Dynamic Programming will generate an optimal solution as it generally considers all possible cases and then choose the best.
Recursion
A greedy method follows the problem solving heuristic of making the locally optimal choice at each stage. A Dynamic programming is an algorithmic technique which is usually based on a recurrent formula that uses some previously calculated states.
Memoization
Greedy method is more efficient in terms of memory as it never look back or revise previous choices It requires Dynamic Programming table for Memoization and it increases it’s memory complexity.
Time complexity
Greedy methods are generally faster. For example, Dijkstra’s shortest path algorithm takes O(ELogV + VLogV) time. Dynamic Programming is generally slower. For example, Bellman Ford algorithm takes O(VE) time.
Fashion
The greedy method computes its solution by making its choices in a serial forward fashion, never looking back or revising previous choices. Dynamic programming computes its solution bottom up or top down by synthesizing them from smaller optimal sub solutions.
Example
greedy method: Fractional knapsack .
dynamic programming: 0/1 knapsack problem

## Link(s)

- https://cpp.sh/
