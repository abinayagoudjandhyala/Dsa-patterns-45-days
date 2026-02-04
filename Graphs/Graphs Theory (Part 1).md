
# Graph Basics – Adjacency Matrix (Theory Notes)

Today I studied the **Adjacency Matrix representation of graphs**.

---

## What Is an Adjacency Matrix?

An adjacency matrix is a **2D array** used to represent a graph.

If the graph has `n` vertices, the matrix size is:

```
n × n
```

---

## How It Works

* Row represents **source node**
* Column represents **destination node**

If there is an edge between node `i` and node `j`:

```
matrix[i][j] = 1
```

Otherwise:

```
matrix[i][j] = 0
```

---

## Undirected Graph Representation

For undirected graphs:

```
matrix[i][j] = matrix[j][i]
```

Because the connection works both ways.

---

## Directed Graph Representation

For directed graphs:

```
matrix[i][j] = 1
matrix[j][i] may be 0
```

Edge direction matters.

---

## Weighted Graph Representation

Instead of storing `1`, store the **weight value**:

```
matrix[i][j] = weight
```

---

## Advantages

* Easy to check if an edge exists
* Simple to implement
* Good for dense graphs

---

## Disadvantages

* Uses more memory (O(n²))
* Inefficient for sparse graphs
* Iterating neighbors is slower

---

## When To Use

* Graph is small
* Graph is dense
* Need fast edge lookup

---

## Key Learning

* Matrix representation is index-based
* Memory usage is high compared to adjacency list
* Direction and weight affect matrix values

---

## Topic Covered Today

* Adjacency Matrix representation of Graph

