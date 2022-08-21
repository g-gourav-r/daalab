# Desing and Analysis of Algorithms

[Program 1 - Quick Sort](https://github.com/g-gourav-r/daalab/blob/main/P1-%20Quciksort.java)

OUTPUT:

*************QUICK SORT************

Enter Max array size: 15

Input Array:

94 85 23 71 10 87 93 19 26 3 28 1 12 29 12 

Sorted Array:

1 3 10 12 12 19 23 26 28 29 71 85 87 93 94 

Time Complexity in ms for n=15 is: 0.0115

---

[Program 2 - Merge Sort](https://github.com/g-gourav-r/daalab/blob/main/P2%20-%20Mergesort.java)

OUTPUT: 

*************MERGE SORT************

Enter Max array size: 20

Input Array:

852 760 817 249 115 353 101 183 74 465 242 554 311 145 395 758 574 713 
307 815 

Sorted Array (Merge Sort):
74 101 115 145 183 242 249 307 311 353 395 465 554 574 713 758 760 815 
817 852 

Time Complexity (ms) for n = 20 is : 0.6351

---

[Program 3 - Warshall's algorithm](https://github.com/g-gourav-r/daalab/blob/main/P3%20-%20Warshalls.java)


OUTPUT:

*********WARSHALL'S ALGORTIHM**********

Enter the number of vertices
4

Enter the Adjacency Matrix (1 if there is edge and 0 if there is no 
direct edge) 

0 0 1 0

1 0 0 1

0 0 0 0

0 1 0 0

The Transitive Closure Matrix is:

0 0 1 0

1 1 1 1

0 0 0 0

1 1 1 1

---


[Program 4 - Dijkstra’s algorithm](https://github.com/g-gourav-r/daalab/blob/main/P4%20-%20Dijkstras.java)

OUTPUT:

*****DIJKSTRA'S ALGORTIHM*****

Enter the number of vertices:

5

Enter the cost adjacency matrix:

0 4 8 999 999

4 0 2 5 999

8 2 0 5 9

999 5 5 0 4

999 999 9 4 0

Enter starting vertex: 

1

The shortest distance from source vertex 1 to all other vertices are:

2:4

3:6

4:9

5:13

---

[Program 5 - Kruskal's](https://github.com/g-gourav-r/daalab/blob/main/P5%20-%20Krukals.java)

OUTPUT:

*****KRUSKAL'S ALGORTIHM*****

Enter the no. of vertices

5

Enter the cost adjacency matrix

0 10 0 30 100

10 0 50 0 0

0 50 0 20 10

30 0 20 0 60

100 0 10 60 0

The edges of Minimum Cost Spanning Tree are

Edge 1:(1,2) =10

Edge 2:(3,5) =10

Edge 3:(3,4) =20

Edge 4:(1,4) =30

Minimum cost for the Spanning Tree is:70

---

[Program 6 - Greedy Knapsack](https://github.com/g-gourav-r/daalab/blob/main/P6%20-%20Knapsack%20greedy.java)

OUTPUT:

********* KNAPSACK USING GREEDY METHOD*******

Enter the max capacity of the Knapsack :
15
Enter the weights of the object
2 3 5 7 1 4 1
Enter the profits of the object
10 5 15 7 6 18 3
The Solution vector, x[]: 
1.0 1.0 1.0 1.0 1.0 0.6666667 0.0 
Total profit is = 55.333332
---

[Program 7 - Dynamic Kanpsack](https://github.com/g-gourav-r/daalab/blob/main/P7%20-%20Knapsack%20Dynamic.java)

OUTPUT:

*****KNAPSACK USING DYNAMIC PROGRAMMING*****

Enter number of objects: 
4

Enter the max capacity of knapsack: 
15

Enter Weights: 
9 3 2 5

Enter Profits: 
20 30 25 45

Items selected are = 
4 
3 
2 

Optimal solution (Maximum Profit) = 100

---

[Program 8 - Sum of subsets](https://github.com/g-gourav-r/daalab/blob/main/P8%20-%20Sum%20of%20subsets.java)

OUTPUT:

*****SUBSET SUM PROBLEM USING BACKTRACKING*****

Enter number of elements: 
5

Enter the set in increasing order: 
1 2 5 6 8

Enter the max. subset value(d): 
9

The subsets are: 
1 2 6 
1 8

---

[Program 9 - Prims algorithm](https://github.com/g-gourav-r/daalab/blob/main/P9%20-%20Prims%20algo.java)

OUTPUT:

*****PRIM'S ALGORTIHM*****

Enter the number of nodes:
5

Enter the adjacency (weight) matrix:

0 10 0 30 100

10 0 50 0 0

0 50 0 20 10

30 0 20 0 60

100 0 10 60 0

Edge1:(1,2)cost:10

Edge2:(1,4)cost:30

Edge3:(4,3)cost:20

Edge4:(3,5)cost:10

Minimun cost of the Spanning Tree is:70

---

[Program 10 - Floyds](https://github.com/g-gourav-r/daalab/blob/main/P10%20-%20Flyods.java)

OUTPUT:

*********FLOYD'S ALGORTIHM**********

Enter the number of vertices
5

Enter the Cost Matrix (999 for infinity) 
0 3 8 999 -4

999 0 999 1 7

999 4 0 999 999

2 999 -5 0 999

999 999 999 6 0

The All Pair Shortest Path Matrix is:

0 1 -3 2 -4

3 0 -4 1 -1

7 4 0 5 3

2 -1 -5 0 -2

8 5 1 6 0

---
