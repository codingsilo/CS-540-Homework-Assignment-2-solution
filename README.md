# CS-540-Homework-Assignment-2-solution

Download Here: [CS 540 Homework Assignment # 2 solution](https://jarviscodinghub.com/assignment/cs-540-homework-assignment-2-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Question 1: Successor Function [50 points]
This is a programming question. The solution to the programming problem should be coded in Java, and
you are required to use only built-in libraries to complete this homework. Please submit a source
code file named successor.java with no package statements, and make sure your program is runnable
from command line on a department Linux machine. We provide a skeleton successor.java code that you
can optionally use, or you can write your own.
The goal of this assignment is to become familiar with the state space in a real-world problem.
You are given three water jugs with capacity A, B, C liters, respectively. A, B, C are positive integers. At
each step, you can perform one of these actions:
• Empty a jug
• Fill a jug
• Pour water from one jug to another until either the former is empty or the latter is full.
Write a program successor.java to print the successor states of an input state.
• Input: 6 integers A, B, C, a, b, c, where (A, B, C) are the capacity of the jugs, and (a, b, c) are the current
amount of water in each jug. You may assume that the input is valid, namely a ≤ A, b ≤ B, c ≤ C,
and A, B, C are positive integers, and a, b, c are non-negative integers.
• Output: Print the list of successor states reachable in one step from (a, b, c), one one each line. The
lines do not need to be sorted. The successors should not include (a, b, c) itself.
Here are some examples of running the program from the command line. The inputs and outputs are
space-separated with no comma. Please follow the same input/output format.
Example 1:
$java successor 3 2 1 3 2 0
0 2 0
3 0 0
3 2 1
2 2 1
3 1 1
Example 2:
$java successor 11 5 2 6 3 1
0 3 1
6 0 1
6 3 0
11 3 1
6 5 1
6 3 2
9 0 1
7 3 0
4 5 1
6 4 0
5 3 2
6 2 2
Question 2: State Space [50 points]
An (m, n, k)-puzzle is a sliding puzzle with m columns, n rows, and k empty squares, where 1 ≤ k < mn. As usual, one move is to move a single tile to an adjacent (up, down, left, right) empty square, if available. 1. (10 points) How many tiles are there in a (m, n, k)-puzzle in general? For example, there are 8 tiles in a (3, 3, 1)-puzzle. 2. (20 points) Let each tile have a distinct name. How many distinct states are there in the state space? Show your derivation. 3. (20 points) Draw a graph that corresponds to the state space of a (2, 2, 1)-puzzle, and briefly describe your graph. This is not an art project: You may represent the states in ways easy for you to type, and you do not necessarily need drawing programs – you may even use plaintext. You can also hand draw the graph, but please clearly show the nodes and edges.
