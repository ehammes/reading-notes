# Read: 15 - Trees

## Reading

[Trees](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

* **Terminology**
  * **Node** - A Tree node is a component which may contain its own values, and references to other nodes
  * **Root** - The root is the node at the beginning of the tree
  * **K** - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
  * **Left** - A reference to one child node, in a binary tree
  * **Right** - A reference to the other child node, in a binary tree
  * **Edge** - The edge in a tree is the link between a parent and child node
  * **Leaf** - A leaf is a node that does not have any children
  * **Height** - The height of a tree is the number of edges from the root to the furthest leaf
* **Traversals include**:
  * Depth First - Depth first traversal is where we prioritize going through the depth (height) of the tree first. Three methods include: Pre-order (root >> left >> right), in-order (left >> root >> right), post-order (left >> right >> root)
  * Breadth First - Breadth first traversal iterates through the tree by going through each level of the tree node-by-node. Traditionally, breadth first traversal uses a queue (instead of the call stack via recursion) to traverse the width/breadth of the tree.
  * The most common way to traverse through a tree is to use recursion. With these traversals, we rely on the call stack to navigate back up the tree when we have reached the end of a sub-path.
* **Binary Tree** - are restricted to two children per node (left and right children)
* **K-ary Tree** - can have more than 2 child nodes
* **Big 0**
  * For time complexity, inserting nodes Big O is 0(n). If a tree has n nodes, the worst path will look at n items.
  * For space complexity, node insertion using breadth first insertion will be 0(w). w is the largest width of the tree.
* **Binary Search Trees** - a type of tree that does have some structure attached to it. In a BST, nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.
  * Searching a BST can be done quickly, because all you do is compare the node you are searching for against the root of the tree or sub-tree. If the value is smaller, you only traverse the left side. If the value is larger, you only traverse the right side.
  * The Big 0 time of a Binary Search Tree is 0(h), h representing height. The Big 0 space of a BST search is 0(1).
