
# Graphs – Traversals & Weighted Graphs (Theory Notes)

Today I studied **graph traversal techniques**, **weighted graphs**, and **minimum spanning tree (MST)** concepts.

---

## Graph Traversals

Graph traversal means **visiting all vertices of a graph** in a systematic way.

---

## Breadth First Search (BFS)

### Core Idea

Traverse the graph **level by level**, visiting all neighbors before moving deeper.

### Key Points

* Uses a **queue**
* Starts from a source node
* Explores all immediate neighbors first

### When to Use

* Shortest path in **unweighted graphs**
* Level-based exploration
* Finding minimum steps

---

## Depth First Search (DFS)

### Core Idea

Traverse the graph by going **as deep as possible** before backtracking.

### Key Points

* Uses **recursion or stack**
* Explores one path fully before moving to next

### When to Use

* Path existence
* Cycle detection
* Connected components

---

## BFS vs DFS (Conceptual Difference)

* BFS explores **wide first**
* DFS explores **deep first**
* BFS uses queue
* DFS uses recursion / stack

---

## Weighted Graphs

### What Is a Weighted Graph?

A graph where each edge has an associated **weight (cost, distance, time, etc.)**.

---

### Key Points

* Edge weights affect shortest path and spanning tree problems
* Cannot use simple BFS for shortest path
* Special algorithms are needed

---

## Minimum Spanning Tree (MST)

### Core Idea

A **spanning tree** that connects all vertices with **minimum total edge weight**.

---

### Properties of MST

* Contains exactly `V - 1` edges
* No cycles
* Includes all vertices
* Total weight is minimum

---

### Common MST Algorithms (Theory)

* **Prim’s Algorithm** – grows tree from a starting node
* **Kruskal’s Algorithm** – sorts edges and adds smallest edges first

---

## When MST Is Used

* Network design
* Connecting cities with minimum cost
* Cable and road layout problems

---

## Key Learning

* BFS and DFS are core graph traversal techniques
* Weighted graphs require special handling
* MST focuses on minimizing total connection cost
* Understanding theory is essential before implementation

---

## Topics Covered Today

* BFS (Breadth First Search)
* DFS (Depth First Search)
* Weighted Graphs
* Minimum Spanning Tree (MST)


![WhatsApp Image 2026-02-06 at 11 10 08 PM](https://github.com/user-attachments/assets/6f10bef4-92fb-42c5-a558-378345cc11c7)
![WhatsApp Image 2026-02-06 at 11 10 08 PM (1)](https://github.com/user-attachments/assets/948e28e0-f4f2-4824-8711-0358684b5356)
![WhatsApp Image 2026-02-06 at 11 10 14 PM](https://github.com/user-attachments/assets/9193c75c-2530-4959-ba40-8c58cec39e36)
![WhatsApp Image 2026-02-06 at 11 10 39 PM](https://github.com/user-attachments/assets/86aaab15-8581-4078-982a-ff8552393372)
![WhatsApp Image 2026-02-06 at 11 10 49 PM](https://github.com/user-attachments/assets/c360fed0-c15e-491c-bab7-90d5000e2f2b)
