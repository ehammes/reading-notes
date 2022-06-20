# Read: 05 - Linked Lists

## Reading

* Read and save for reference: [Big O: Analysis of Algorithm Efficiency](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html) (Up through the section titled “Linear Complexity Growth”)
  * Big O(oh) notation is used to describe the efficiency of an algorithm or function. This efficiency is evaluated based on 2 factors:
    * Running Time (also known as time efficiency / complexity)
      * The amount of time a function needs to complete.
    * Memory Space (also known as space efficiency / complexity)
      * The amount of memory resources a function uses to store data and instructions.
  * 4 key areas include: Input Size, Units of Measurement, Orders of Growth, Best Case, Worst Case, and Average Case  

* Read: [Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)

  * A **Linked List** is a sequence of Nodes that are connected/linked to each other. The most defining feature of a Linked List is that each Node references the next Node in the link. A data structure that contains nodes that links/points to the next node in the list.
  * **Singly** - Singly refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.
  * **Doubly** - Doubly refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.
  * **Node** - Nodes are the individual items/links that live in a linked list. Each node contains the data for each link.
  * **Next** - Each node contains a property called Next. This property contains the reference to the next node. When traversing a linked list, you are not able to use a foreach or for loop. We depend on the Next value in each node to guide us where the next reference is pointing. The best way to approach a traversal is through the use of a while() loop. This allows us to continually check that the Next node in the list is not null. If we accidentally end up trying to traverse on a node that is null, a NullReferenceException gets thrown and our program will crash/end.
  * **Head** - The Head is a reference of type Node to the first node in a linked list.
  * **Current** - The Current is a reference of type Node to the node that is currently being looked at. When traversing, you create a new Current variable at the Head to guarantee you are starting from the beginning of the linked list.
  * There are two types of Linked List - Singly and Doubly. 
* Read: [What’s a Linked List, Anyway pt1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)
* Read: [What’s a Linked List, Anyway pt2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)

### Review

1. How do you grow a linked list?
2. What is the best approach for traversing through a linked list? What should not be used?
3. What is the main difference between arrays and linked lists?
4. A linked list is made up of a series of ________.
5. What does a node contain?
6. What are the different types of linked lists?
7. What are the differences between singly linked lists and doubly linked lists?
8. What is the Big O Notation?
9. Show an example of a linked list and adding a node to the linked list - either by pseudo code or diagram.
10. A circular linked list does not end with a node containing a  ______ value.
