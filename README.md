# Series: LeetCode

Part 1

How to Become a Cracked LeetCoder?

1. Pattern Recognition, Pick DSA

Learn to quickly identify the pattern of a problem. Knowing only brute force isn’t enough; you must know when and why to use a specific DSA. So check constraints before deciding.

For example, if n = 10⁵ and you need repeated subarray sums, O(n²) brute force will time out. Use Fenwick Tree (BIT) if updates, Prefix Sum if static to get sums efficiently. (Part 2: check it out)

2. Solve problems from the last 25-30 contests.

3. Use fast I/O templates if doing contests in C++ or Java.

Keep ready templates for:

• Fast I/O

• BFS / DFS

• DSU (Union Find)

• Binary Search

• Prefix Sum / Hash / Map / Set

4. Early Problems First

Solve easy & medium problems ASAP (within 10-20 mins).

5. Don’t get stuck in hard problem initially — waste of time.

6. Speed + Accuracy

First 2 problems must be solved within 10-15 mins.

But for beginners: Try to solve the first 2 problems within 10-15 mins.

7. Aim for full solve or 3/4 solves to gain significant rating.

8. Debugging Skills

Practice finding bugs quickly.

9. One wrong submission can kill your rank — test locally if possible.

10. After Contests

• Read editorials for unsolved problems.

• Analyze your mistakes. Check why you failed a problem: Was it logic, speed or implementation?

• Don’t stop just because your solution got accepted. If your solution is O(n²), see if it can be improved to O(n log n).

11. Master These Topics

To reach 2500+, You need to be fast in:

• Prefix Sum / Binary Search / Sliding Window

• Two Pointers / Stack & Queue / Monotonic Stack

• Hashing / Maps / Sets

• DFS/BFS / Union-Find / Graph

• DP — must-do!

• Greedy + Heap + Backtracking

• Tree Algorithms

• Segment Tree / Fenwick Tree (optional)

• Math / Combinatorics

• Bit Manipulation


Part 2

Must-know 14 LeetCode Patterns

1. Sliding Window

Problem Keywords: subarray, substring, contiguous elements, window size k, longest / shortest substring.

Example use:

• Longest substring without repeating characters

• Maximum sum subarray of size k

2. Two Pointers

Problem Keywords: sorted array, pair sum, remove duplicates, opposite direction scanning, left/right pointer.

Example use:

• Pair with target sum

• Remove duplicates

• Container with most water

3. Prefix Sum

Problem Keywords: range sum, subarray sum, subarray sum equals k, cumulative sum.

Example use:

• Range sum queries

• Subarray sum equals k

4. Binary Search

Problem Keywords: sorted array, find target, minimum / maximum possible value, search space, monotonic condition, search on answer.

Example use:

• Search in sorted array

• Minimum feasible value problems

5. Fast & Slow Pointers (also called Floyd's cycle detection)

Problem Keywords: linked list cycle, find middle node, detect loop, remove cycle.

Example use:

• Linked list cycle detection

• Find middle of linked list

6. DFS (Depth First Search)

Problem Keywords: graph traversal, tree traversal, recursion / stack, connected components, backtracking, island problems.

Example use:

• Graph traversal

• Tree recursion

7. BFS (Breadth First Search)

Problem Keywords: shortest path in unweighted graph, minimum steps, level order traversal, queue, grid traversal.

Example use:

• Shortest path in unweighted graph

• Tree level order traversal

8. Backtracking

Problem Keywords: all combinations, all permutations, generate subsets, sudoku / n-queens, word search.

Example use:

• Subsets

• Permutations

• N-Queens

9. Dynamic Programming (DP)

Problem Keywords: maximum / minimum, count number of ways, optimal solution, overlapping subproblems.

Example use:

• Fibonacci

• Longest Increasing Subsequence

• Knapsack

10. Greedy

Problem Keywords: minimum number, maximum activities, interval selection, sorting + choose.

Example use:

• Interval scheduling

• Minimum number of arrows to burst balloons

11. Monotonic Stack

Problem Keywords: next or previous greater / smaller element, largest rectangle in histogram, sliding window maximum / minimum, monotonic property.

Example use:

• Next greater element

• Largest rectangle in histogram

12. Heap / Priority Queue

Problem Keywords: kth largest / smallest, top k / bottom k, merge k sorted lists / arrays, stream of numbers / running median, minimum / maximum repeatedly.

Example use:

• Kth largest element

• Merge k sorted lists

13. Union-Find (Disjoint Set)

Problem Keywords: graph / connected components, cycle detection in undirected graph, friend groups / social network connections, union / merge / find operations, queries like “are x and y connected?”.

Example use:

• Detect cycle in graph

• Number of connected components

14. Topological Sort

Problem Keywords: Directed Acyclic Graph (DAG), dependencies / prerequisites, course schedule / task scheduling, order of execution / linear ordering, no cycles / detect impossibility.

Example use:

• Course schedule

• Dependency resolution


# If you want to solve problems based on the patterns most frequently asked in tech company interviews, then "Blind 75 & NeetCode 150" are for you.

1. Blind 75: List of the 75 essential LeetCode algorithms problems.(Curated by Yangshun, a former Meta staff engineer)
   Easy: 19,
   Medium: 49,
   Hard: 7.
2. NeetCode 150: Expands on Blind 75 with 75 more problems.
   Easy: 28,
   Medium: 101,
   Hard: 21.

"Blind 75" vs "NeetCode 150" -> Blind 75 offers a solid foundation with essential LeetCode problems But "NeetCode 150" expands this palette, covering a wider array of patterns and topics!

Recommended YouTube Channel for solving tutorials: "NeetCode"

Standard Time for Solving LeetCode Problems:
1. Easy: 15-20 minutes
2. Medium: 30 minutes
3. Hard: 40-60 minutes
   
# DSA Topics and Problem Distribution:

1. Arrays & Hashing: NeetCode (9), Blind (8)
2. Two Pointers: NeetCode (5), Blind (3)
3. Sliding Window: NeetCode (6), Blind (4)
4. Stack: NeetCode (7), Blind (1)
5. Binary Search: NeetCode (7), Blind (2)
6. Linked List: NeetCode (11), Blind (6)
7. Trees: NeetCode (15), Blind (11)
8. Tries: NeetCode (3), Blind (3)
9. Heap / Priority Queue: NeetCode (7), Blind (1)
10. Backtracking: NeetCode (9), Blind (2)
11. Graphs: NeetCode (13), Blind (6)
12. Advanced Graphs: NeetCode (6), Blind (1)
13. 1-D Dp: NeetCode (12), Blind (10)
14. 2-D Dp: NeetCode (11), Blind (2)
15. Greedy: NeetCode (8), Blind (2)
16. Intervals: NeetCode (6), Blind (5)
17. Math & Geometry: NeetCode (8), Blind (3)
18. Bit Manipulation: NeetCode (7), Blind (5)

-> Here the problem topics are listed along with the number of problems in each topic. For example, there are 9 problems in Arrays & Hashing where Blind has 8, but NeetCode has 9, that means there are 8 common problems.


Important DSA: BFS & DFS, Sliding window, Top K elements, Linked list, Stack, Queue, DP, Array, String, Searching, Sorting, Backtracking, Trie, Bit manipulation, Graph, BST.


# Some of the Most Important patterns that are frequently asked in Interviews and OAs:

1. Sliding Window (Fixed sized window and variable sized window questions on array and string)
2. Island problems(DFS/BFS or different traversals on grid)
3. Two Pointers, Fast and Slow pointer 
4. Merge Intervals
5. Cyclic Sort(Very important)
6. DFS and BFS
7. Two Heaps Problems(Find median in a stream problem)
8. Subset Problems
9. Subarray/Substring problems using Hashing
10. Binary Search
11. Bitwise XOR(Common asked question in many OAs)
12. Top k elements
13. K way merge
14. Topological Sort
15. Bit Manipulation
16. Number Theory


# Best Books for DSA
1. Data Structures & Algorithms:
   
Computer Science Distilled - https://amzn.to/39jYZ0S​

Grokking Algorithms - https://amzn.to/2JcBrjS​

Introduction to Algorithms - https://amzn.to/2V03JRb​

Elements of Programming Interviews (Python) - https://amzn.to/35XPQJw​

Elements of Programming Interviews (Java) - https://amzn.to/374W5KT​

2. Software Engineering & Architecture:
   
Clean Code - https://amzn.to/3nHNtAC​

Clean Architecture - https://amzn.to/3kZ7UqR​

Refactoring - https://amzn.to/377VXdM​

The Productive Programmer - https://amzn.to/33aMeSE​

Pragmatic Thinking & Learning - https://amzn.to/2J5IfzM​

3. Distributed Systems:
   
Web Scalability for Startup Engineers - https://amzn.to/39c55QV​

Designing Data Intensive Applications - https://amzn.to/3fxgOLm​

Understanding Distributed Systems - https://amzn.to/3cjChr5​

Software Engineering at Google - https://amzn.to/3rfJc8L​

Building Microservices - https://amzn.to/2UUPsFi​

