**✅ What is Memory Management in DSA?**
Memory Management in Data Structures and Algorithms (DSA) refers to how memory (RAM) is allocated, used, and freed during program execution.

#

**📌 Key Concepts:**
| Concept                |Description                                                                                           |
| ---------------------- | ----------------------------------------------------------------------------------------------------- |
| **Memory Allocation**  | Reserving space in memory for variables, arrays, objects, etc.                                        |
| **Static Allocation**  | Memory is allocated at **compile time** (e.g., arrays in C). Size must be known in advance.           |
| **Dynamic Allocation** | Memory is allocated at **runtime** using functions like `malloc`, `calloc` in C or `new` in C++/Java. |
| **Garbage Collection** | Automatic memory release for unused data (common in Java, Python).                                    |
| **Memory Leak**        | When memory is allocated but never freed, leading to wastage.                                         |
| **Stack vs Heap**      | Stack is used for function calls and local variables; Heap is used for dynamically allocated memory.  |

#

**💡 Stack vs Heap**

| Feature    | Stack               | Heap                      |
| ---------- | ------------------- | ------------------------- |
| Allocation | Static              | Dynamic                   |
| Speed      | Faster              | Slower                    |
| Lifetime   | Until function ends | Until manually freed / GC |
| Size       | Limited             | Large                     |


#

**🧠 Why It Matters in DSA?**

- Efficient use of memory leads to better performance.
- Poor memory management leads to crashes, slowness, or leaks.
- Some DSA problems require manual control of memory (e.g., custom linked lists, trees).
