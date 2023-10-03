# Introduction to Data Structure

> Data Structure + Algorithms = Programs

## What is a Data Structure?

A Data Structure is a collection of values the values can have relationships among them and they can have functions applied to them. Each one is different in what it can do and what it is best used for. Important thing to take away is that each data structure is good and is specialized for its own thing.

Here is a list of different Data Stucture [DS_list]

## How Computer Store Data?


Computers store and work with data using several key components, including the CPU (Central Processing Unit), RAM (Random Access Memory), and storage memory (typically a hard drive or solid-state drive). Here's a simplified explanation of how these components interact to store and process data:

1. **Storage Memory (Hard Drive or SSD)**:
   - This is like the computer's long-term memory. It stores all your data, including the operating system, programs, files, and more.
   - Data on storage memory is stored persistently, meaning it stays even when the computer is turned off.

2. **RAM (Random Access Memory)**:
   - RAM is like the computer's short-term memory. It stores data that is currently being used or processed by the CPU.
   - When you open a program or file, the data is loaded from storage memory into RAM for quick access. This makes tasks much faster because RAM is much faster to read from and write to than storage memory.

3. **CPU (Central Processing Unit)**:
   - The CPU is the brain of the computer. It performs calculations and executes instructions.
   - When you run a program, the CPU fetches instructions and data from RAM to perform tasks.
   - The CPU processes data by performing operations like addition, subtraction, and more complex calculations.

Here's a simplified step-by-step process of how a computer works with data:

1. **Loading Data**: When you open a program or file (e.g., a document or a video), the necessary data is loaded from the storage memory (hard drive or SSD) into RAM. This data includes both the program's instructions and the actual content you want to work with.

2. **Processing Data**: The CPU receives instructions from RAM and processes them. For example, if you're editing a document, the CPU performs operations like changing text or formatting.

3. **Storing Changes**: As you make changes to your document or data, the CPU writes these changes back to RAM. This allows you to see the results of your actions in real-time.

4. **Saving Changes**: Eventually, you'll want to save your work. When you do, the changes are written back to the storage memory (e.g., hard drive or SSD). This ensures your changes are preserved even after you turn off the computer.

The arrangement of data in RAM (Random Access Memory) can be considered a form of data structure. A data structure, in a general sense, is a way of organizing and storing data so that it can be efficiently accessed, modified, and processed. RAM itself can be thought of as a fundamental data structure, as it provides a way to store and access data quickly.

However, when people typically refer to data structures, they are often talking about more specific and complex ways of organizing data within RAM or other forms of storage. These data structures include arrays, linked lists, stacks, queues, trees, graphs, and more. These structures are designed to serve specific purposes and optimize various operations on the data they contain, such as searching, sorting, insertion, and deletion.

So, while RAM itself is a basic form of data structure by providing a place to store data in a computer's memory, when discussing data structures in computer science, it usually refers to more intricate and purpose-specific arrangements of data within RAM or other storage media.

- Learn more about [Computer_Memory]
- Get a crash course on [RAMs_&_Registers]

## Operations On Data Structures

 Here are some common operations that can be performed on various data structures:

1. **Access (or Retrieval)**:
   - Retrieving a specific element or data item from the data structure, often using an index, key, or some identifier.
   - Examples: Accessing an element in an array, finding a node in a linked list, or retrieving a value from a dictionary using a key.

2. **Insertion (or Addition)**:
   - Adding a new element or data item to the data structure.
   - Examples: Adding an item to the end of an array, inserting a node into a linked list, or adding a key-value pair to a hash table.

3. **Deletion (or Removal)**:
   - Removing a specific element or data item from the data structure.
   - Examples: Removing an element from an array, deleting a node from a linked list, or removing a key-value pair from a hash table.

4. **Search (or Lookup)**:
   - Finding a particular element or data item within the data structure, often to determine if it exists.
   - Examples: Searching for a value in an array, looking up a node in a binary search tree, or checking if a key exists in a set.

5. **Traversal (or Iteration)**:
   - Visiting and processing all elements or nodes in the data structure in a specific order.
   - Examples: Iterating through all elements in an array, traversing a binary tree in-order, or looping through the elements in a linked list.

6. **Sorting**:
   - Arranging the elements in a specific order, such as ascending or descending.
   - Examples: Sorting an array of numbers, sorting a list of names, or sorting data in a binary search tree.

7. **Merging and Combining**:
   - Combining two or more data structures into a single data structure or merging sorted data structures.
   - Examples: Merging two sorted arrays, combining two linked lists, or merging two binary search trees.

8. **Finding Minimum and Maximum**:
   - Locating the smallest and largest elements within the data structure.
   - Examples: Finding the minimum and maximum values in an array or searching for the smallest and largest nodes in a binary tree.

9. **Counting**:
   - Determining the number of elements or nodes in the data structure.
   - Examples: Counting the elements in an array, calculating the size of a linked list, or counting the nodes in a graph.

10. **Modifying Elements**:
    - Changing or updating the value of an existing element in the data structure.
    - Examples: Updating an element in an array, modifying the data in a node of a linked list, or changing the value associated with a key in a dictionary.



[Computer_Memory]:(https://statmath.wu.ac.at/courses/data-analysis/itdtHTML/node55.html)
[RAMs_&_Registers]:(https://www.youtube.com/watch?v=fpnE6UAfbtU)
[DS_list]: (https://en.wikipedia.org/wiki/List_of_data_structures)