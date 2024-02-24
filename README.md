## Data Structures Agenda

### Arrays and Strings:

- **Definition:** Arrays and strings are fundamental data structures used to store collections of elements or characters, respectively, in contiguous memory locations.
- **Operations:** 
  - Accessing elements by index.
  - Modifying elements.
  - Concatenation (for strings).
- **Complexity Analysis:** 
  - Access: O(1).
  - Insertion/Deletion (at end): O(1) if amortized.
- **Common Problems:** 
  - Reversing an array/string.
  - Finding duplicates or unique characters.
  - Implementing substring or pattern matching algorithms.

### Linked Lists:

- **Definition:** A linked list is a linear data structure where elements are stored in nodes. Each node contains a data element and a reference to the next node in the sequence.
- **Types:** 
  - Singly linked lists.
  - Doubly linked lists.
  - Circular linked lists.
- **Operations:** 
  - Insertion.
  - Deletion.
  - Traversal.
- **Complexity Analysis:** 
  - Access: O(n).
  - Insertion/Deletion (at beginning): O(1).
- **Common Problems:** 
  - Detecting cycles in a linked list.
  - Reversing a linked list.
  - Implementing various algorithms like merge sort or quicksort using linked lists.

### Stacks and Queues:

- **Definition:** Stacks and queues are abstract data types (ADTs) that operate on the Last-In-First-Out (LIFO) and First-In-First-Out (FIFO) principles, respectively.
- **Operations:** 
  - Stack: Push, pop, peek.
  - Queue: Enqueue, dequeue, peek.
- **Complexity Analysis:** 
  - All operations: O(1).
- **Common Problems:** 
  - Parenthesis matching.
  - Implementing a stack using queues and vice versa.
  - Solving problems related to nested structures.

### Trees and Binary Trees:

- **Definition:** A tree is a hierarchical data structure consisting of nodes connected by edges. A binary tree is a special type of tree in which each node has at most two children.
- **Operations:** 
  - Traversal (in-order, pre-order, post-order).
  - Insertion.
  - Deletion.
- **Complexity Analysis:** 
  - Access: O(log n) for balanced trees; O(n) for unbalanced trees.
- **Common Problems:** 
  - Finding the height or depth of a tree.
  - Checking if a tree is balanced.
  - Implementing tree traversal algorithms (in-order, pre-order, post-order).

### Graphs:

- **Definition:** A graph is a collection of nodes (vertices) and edges that connect pairs of nodes. Graphs can be directed or undirected.
- **Representations:** 
  - Adjacency matrix.
  - Adjacency list.
- **Operations:** 
  - Traversal (DFS, BFS).
  - Finding shortest paths.
  - Minimum spanning trees.
- **Complexity Analysis:** 
  - Traversal: O(V + E).
  - Shortest paths: Depends on algorithm (e.g., Dijkstra's algorithm, Bellman-Ford algorithm).
- **Common Problems:** 
  - Finding the shortest path between two nodes.
  - Detecting cycles in a graph.

### Hash Tables:

- **Definition:** A hash table is a data structure that stores key-value pairs, allowing for fast retrieval of values based on their associated keys.
- **Operations:** 
  - Insertion.
  - Deletion.
  - Search.
- **Complexity Analysis:** 
  - All operations: O(1) on average, O(n) worst-case.
- **Common Problems:** 
  - Solving problems utilizing hash tables for fast data retrieval, such as two-sum problems or group anagrams.
  - Implementing algorithms like two-pointer or sliding window using hash tables.

### Heaps and Priority Queues:

- **Definition:** A heap is a specialized binary tree-based data structure where the parent node is either greater than or less than its child nodes, depending on whether it's a max heap or min heap.
- **Operations:** 
  - Insertion.
  - Deletion.
  - Heapify.
- **Complexity Analysis:** 
  - All operations: O(log n).
- **Common Problems:** 
  - Finding the kth largest/smallest element.
  - Heap-based sorting algorithms like heap sort.
  - Implementing priority queue operations.

### Tries:

- **Definition:** A trie (pronounced "try") is a tree-like data structure used to store a dynamic set of strings. Each node represents a single character of the string.
- **Operations:** 
  - Insertion.
  - Deletion.
  - Search.
- **Complexity Analysis:** 
  - All operations: O(n), where n is the length of the key.
- **Common Problems:** 
  - Implementing autocomplete systems.
  - Solving problems involving prefix search or dictionary implementations.
