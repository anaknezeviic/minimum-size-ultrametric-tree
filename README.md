# Minimum size ultrametric tree
## Overview
A minimum-size ultrametric tree, also known as a minimum spanning tree, is a tree data structure where all leaf nodes are at the same distance from the root node. In other words, it's a hierarchical structure that minimizes the total distance between all leaf nodes while ensuring that they are equidistant from the root. This type of tree is commonly used in various fields such as computational biology, clustering analysis, and evolutionary biology. It's often employed to represent relationships or similarities between objects or data points, where the goal is to construct a tree that optimally captures these relationships while minimizing the overall distance.

## Problem definition
INSTANCE:  $n\times n$ matrix M of positive integers.
SOLUTION: An ultrametric tree, i.e., an edge-weighted tree T(V,E) with n leaves such that, for any pair of leaves i and j, $d_{ij}^T \geq M[i,j]$ where $d_{ij}^T$ denotes the sum of the weights in the path between i and j.
MEASURE: The size of the tree, i.e., $\sum_{e \in E} w(e)$ where w(e) denotes the weight of edge e. 

## Optimization Techniques
**1. Brute force:** Exhaustive search algorithm evaluating all possible solutions.
**2. Hierarchical Clustering:** 1. single linkage clustering method, 2. union find data structure. 
**3. The Minimum Spanning Tree (MST):** Algorithm finds the minimum-weight tree that spans all nodes in a connected, undirected graph.
**4. Simulated Annealing:** Finding approximate solutions to combinatorial optimization problems involving iteratively exploring the solution space by making random changes to a current solution.

