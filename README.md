**🧠 What is Complexity?**

✅ Time Complexity

- Measures how long an algorithm takes to run as a function of input size n.
- Focuses on the number of operations performed.

✅ Space Complexity

- Measures the amount of memory used by an algorithm.
- Includes memory for variables, data structures, function call stacks, etc.


📚 Types of Complexity

**🔹 1. Time Complexity**

| Notation       | Meaning                                  | Example                                  |
| -------------- | ---------------------------------------- | ---------------------------------------- |
| **O(1)**       | Constant time – does not depend on input | Accessing array by index                 |
| **O(log n)**   | Logarithmic – input divided each time    | Binary Search                            |
| **O(n)**       | Linear – grows with input size           | Traversing an array                      |
| **O(n log n)** | Linearithmic – log operation per element | Merge Sort, Heap Sort                    |
| **O(n²)**      | Quadratic – nested loops                 | Bubble Sort, Insertion Sort              |
| **O(2ⁿ)**      | Exponential – doubles with input         | Recursive Fibonacci                      |
| **O(n!)**      | Factorial – very slow                    | Solving Traveling Salesman (brute force) |

##

**🔹 2. Space Complexity**

| Algorithm      | Space Complexity |
| -------------- | ---------------- |
| Iterative Loop | O(1)             |
| Merge Sort     | O(n)             |
| Recursive DFS  | O(h)             |


**🔹 Visual Representation**
Growth rate as n increases:
O(1) < O(log n) < O(n) < O(n log n) < O(n²) < O(2ⁿ) < O(n!)

##


**📈 Common Complexity Notations**

1. Big O (O) – Worst-case scenario (most commonly used)
2. Omega (Ω) – Best-case scenario
3. Theta (Θ) – Average-case or tight bound


**📦 1. Array**
| Operation         | Time Complexity  | Space Complexity |
| ----------------- | ---------------- | ---------------- |
| Access            | O(1)             | O(n)             |
| Search (Unsorted) | O(n)             | -                |
| Search (Sorted)   | O(log n)         | -                |
| Insert (end)      | O(1) (amortized) | -                |
| Insert (middle)   | O(n)             | -                |
| Delete            | O(n)             | -                |


**🧵 2. Linked List**
| Operation         | Singly LL | Doubly LL | Space Complexity |
| ----------------- | --------- | --------- | ---------------- |
| Access (by index) | O(n)      | O(n)      | O(n)             |
| Insert at head    | O(1)      | O(1)      | -                |
| Insert at tail    | O(n)      | O(1)\*    | -                |
| Delete head       | O(1)      | O(1)      | -                |
| Delete tail       | O(n)      | O(1)      | -                |


*Assumes tail pointer exists.

**🗃️ 3. Stack / Queue**
| Operation      | Stack (Array/LL) | Queue (Array/LL) | Space |
| -------------- | ---------------- | ---------------- | ----- |
| Push / Enqueue | O(1)             | O(1)             | O(n)  |
| Pop / Dequeue  | O(1)             | O(1)             | -     |
| Peek           | O(1)             | O(1)             | -     |


**🌳 4. Binary Tree**
| Operation           | Time       | Space    |
| ------------------- | ---------- | -------- |
| Insert / Delete     | O(log n)\* | O(n)     |
| Search (BST)        | O(log n)\* | O(log n) |
| Traversal (DFS/BFS) | O(n)       | O(n)     |


* For balanced trees like AVL, Red-Black Tree. Worst case for unbalanced BST: O(n)

**📊 5. Heap (Min/Max Heap)**
| Operation        | Time Complexity | Space |
| ---------------- | --------------- | ----- |
| Insert           | O(log n)        | O(n)  |
| Delete (min/max) | O(log n)        | -     |
| Peek             | O(1)            | -     |
| Heapify (build)  | O(n)            | -     |


**🕸️ 6. Hash Table / Map / Set**
| Operation | Average Time | Worst Time | Space |
| --------- | ------------ | ---------- | ----- |
| Insert    | O(1)         | O(n)       | O(n)  |
| Delete    | O(1)         | O(n)       | -     |
| Search    | O(1)         | O(n)       | -     |

Worst case occurs with hash collisions (poor hash functions).

**🧮 7. Graph (Adjacency List)**
| Operation       | Time Complexity  | Space    |
| --------------- | ---------------- | -------- |
| Add Vertex      | O(1)             | O(V + E) |
| Add Edge        | O(1)             | -        |
| DFS / BFS       | O(V + E)         | O(V)     |
| Dijkstra's (PQ) | O((V + E) log V) | O(V)     |
| Floyd-Warshall  | O(V³)            | O(V²)    |


**📌 8. String Algorithms**
| Algorithm      | Time Complexity | Space |
| -------------- | --------------- | ----- |
| Naive Search   | O(n \* m)       | O(1)  |
| KMP            | O(n + m)        | O(m)  |
| Rabin-Karp     | O(n + m) avg    | O(1)  |
| Trie Insertion | O(L)            | O(nL) |
| Trie Search    | O(L)            | -     |


n = text length, m = pattern length, L = word length in Trie

📘 Bonus: Complexity Notations
O(1): Constant – best performance (e.g., Hash lookup)

O(log n): Logarithmic – e.g., Binary Search

O(n): Linear – e.g., Loop over array

O(n log n): e.g., Merge Sort, Heap Sort

O(n²): Quadratic – nested loops (e.g., Bubble Sort)

O(2ⁿ), O(n!): Exponential – very inefficient (e.g., brute-force DP)

