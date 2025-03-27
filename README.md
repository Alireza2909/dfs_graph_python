# Depth-First Search (DFS) Algorithm for Graphs in Python

This repository contains the implementation of the Depth-First Search (DFS) algorithm for graphs in Python.

## How to use

1. Clone this repository.
2. Run the `dfs.py` file with Python.
3. Use the `dfs(start)` method to perform a Depth-First Search starting from the specified node.

## Example

```python
graph = Graph()
graph.add_edge(1, 2)
graph.add_edge(1, 3)
graph.add_edge(2, 4)
graph.add_edge(3, 5)

print("Depth-First Search starting from node 1:")
graph.dfs(1)