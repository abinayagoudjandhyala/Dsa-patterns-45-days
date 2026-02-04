
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

<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/ac63497c-90ea-4e59-8029-dddab5b8e551" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/63296689-e3b2-40cc-b442-c84046dbb16d" />
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/2f6dc474-caf7-4631-9461-a576d2bb2e5d" />

