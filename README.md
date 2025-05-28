# 🔄 Floyd-Warshall Algorithm Visualization

This is a web-based interactive visualization tool for the **Floyd-Warshall algorithm**, implemented using **HTML5 Canvas and JavaScript**.

With this tool, you can:
- Create nodes and edges dynamically on a canvas.
- Assign custom weights to edges.
- Run the Floyd-Warshall algorithm to compute all-pairs shortest paths.
- View the resulting distance matrix.
- Reset the graph and try different configurations.

---

## 🧠 What is the Floyd-Warshall Algorithm?

The **Floyd-Warshall algorithm** is a dynamic programming algorithm used to find the **shortest paths between all pairs of vertices** in a weighted graph (directed or undirected).

### 📌 Key Features:
- Works for graphs with **positive or negative edge weights** (no negative cycles).
- Time complexity: **O(V³)** where `V` is the number of vertices.
- Uses a distance matrix `dist[][]`, where `dist[i][j]` is updated if a shorter path is found via an intermediate vertex.

### 📘 Formula:

For each pair (i, j) and an intermediate vertex k:

