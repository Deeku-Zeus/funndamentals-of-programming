### What is an Array?

- **Definition:** An array is a collection of elements, all of the same type, that are stored in contiguous memory locations.
- **Elements:** Each element in an array is accessed using an index, which represents its position within the array.
- **Size:** Arrays have a fixed size, meaning that once declared, the size of an array does not change.
- **Element Access:** Elements in an array are accessed using their index. The index typically starts from 0 for the first element and goes up to size - 1 for the last element.
- **Memory Allocation:** Arrays allocate memory statically (at compile-time) or dynamically (at runtime), depending on the programming language and context.

### Properties of Arrays:

1. **Contiguous Memory:** All elements in an array are stored in adjacent memory locations. This allows for efficient memory access and traversal.
2. **Random Access:** Elements in an array can be accessed directly using their index, allowing for constant-time access.
3. **Fixed Size:** Arrays have a fixed size determined at the time of declaration. Once allocated, the size cannot be changed dynamically.
4. **Homogeneous Elements:** All elements in an array must be of the same data type. This ensures that each element occupies the same amount of memory.

### Common Operations on Arrays:

1. **Accessing Elements:** Get or set individual elements using their indices.
2. **Traversing:** Iterate through all elements of the array, typically using loops like for or while.
3. **Insertion:** Inserting elements into an array involves shifting existing elements to accommodate the new element, which can be inefficient for large arrays.
4. **Deletion:** Removing elements from an array also requires shifting elements to fill the gap left by the deleted element.
5. **Searching:** Find the index of a specific element in the array, often using linear or binary search algorithms.

### Pros and Cons of Arrays:
**Pros:**

- Efficient random access to elements.
- Simple and easy to understand.
- Memory is allocated in a contiguous block, which can improve cache locality.

**Cons:**

- Fixed size, which can lead to memory wastage or insufficient space.
- Inefficient insertion and deletion operations, especially for large arrays.
- Homogeneous data requirement can be restrictive in certain scenarios.