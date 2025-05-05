# CMPS 2200 Recitation 09

## Answers

**Name:** Dylan Mondrus
**Name:**_________________________


Place all written answers from `recitation-09.md` here for easier grading.



- **2)**
Since Prim's algorithm per component uses a priority queue(min-heap), and for each node and edge, it may perform a heap operation. The work of a single Prim run on a component with V nodes and E edge is O(E log V). 

- **4)**
The work is O(n^2 log n). Calculating the euclidean distance for each pair of points costs O(n^2). Prims algorithm with a min heap costs O(log n). So the full work is O(n^2 log n). 
