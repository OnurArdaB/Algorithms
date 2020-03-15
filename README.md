# Algorithms
 
## Sabancı University CS-301 Algorithms

### Course Project:k-Clique

#### Problem Description:
Clique as a word means a small group of people, with shared interests or other features in common, who spend time together and do not readily allow others to join them.

In the context of computer science, clique is a subset of vertices in an undirected graph that has all the vertices adjacent to each other which means they are all connected by edges to each other.

k-Clique problem is the computational problem of finding k number of elements within a clique. Based on the need and given parameters, there may be different formulations in the problem.

#### Algorithm Description:
There is not an exact algorithm to solve the k-Clique problem but there are some possible heuristics that can be implemented such as the greedy algorithm of Grimmett- McDiarmid’s to find cliques which works with a high probability but still there can be errors due to all possible vertex can be form different cliques with all its adjacent. Our algorithm approaches in a greedy way. Basically, the greedy approach is if there is an adjacency it must be in a clique relationship with given vertex. 

However, if that adjacent vertex cannot form a clique with size k, then the algorithm gives an erroneous result. 
But with this approach of not considering all cliques of a given graph, the algorithm finds the solution in a shorter time than Non-Polynomial algorithms.
