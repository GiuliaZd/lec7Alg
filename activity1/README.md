# Activities

## Task 1:

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Graph/GraphIntroSumm.html
  the answer:
  What is the in degree of vertex 3? - 1
  A complete graph is a clique of size: IVI
  What is the degree of Vertex 3? - 2
  Given a subset S of the vertices in a graph, when all vertices in S connect to all other vertices in S, this is called a: clique
  A graph containing all possible edges is a **\_** graph - complete

> You can refer to [link #2](#links) below for more info.

## Task 2

- Discuss how depth-first search works by experimenting with the following link. Try both directed and undirected graphs and write a short summary.
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/DFSAV.html
  answer:

Depth-first search (DFS) is yet another technique used to traverse a tree or a graph.

DFS starts with a root node or a start node and then explores the adjacent nodes of the current node by going deeper into the graph or a tree. This means that in DFS the nodes are explored depth-wise until a node with no children is encountered.

Once the leaf node is reached, DFS backtracks and starts exploring some more nodes in a similar fashion.

> You can refer to [link #3](#links) below for more info.

## Task 3

- Discuss how breadth-first search works by experimenting with the following link. Try both directed and undirected graphs and write a short summary.
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/BFSAV.html
  the answer:
  Breadth-first algorithm starts with the root node and then traverses all the adjacent nodes. Then, it selects the nearest node and explores all the other unvisited nodes. This process is repeated until all the nodes in the graph are explored.

> You can refer to [link #4](#links) below for more info.

## Task 4:

- Reproduce the behavior of the BFS algorithm for the following graph:
  https://opendsa-server.cs.vt.edu/OpenDSA/AV/Graph/BFSPE.html

  the answer:
  Given below is the algorithm for BFS technique.
  there is a graph which we are going to traverse using the BFS algorithm.

Let A be the root/starting node of the graph.

Step 1: Start with node A and enqueue it to the queue.
Step 2: Repeat the following steps for all the nodes in the graph.
Step 3: Dequeue A and process it.
Step 4: Enqueue all the adjacent nodes of S and process them.
[END OF LOOP]
Step 6: EXIT

> You can refer to [link #4](#links) below.

## Task 5: Individual (at home)

- There are two traditional approaches to representing graphs: The adjacency matrix and the adjacency list. What are the main differences in term of space/time complexity. You can refer to following link:
  https://www.baeldung.com/cs/adjacency-matrix-list-complexity
  the answer:

## Links

1. https://cpp.sh/
2. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphIntro.html
3. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphTraversal.html#depth-first-search
4. https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/GraphTraversal.html#breadth-first-search
