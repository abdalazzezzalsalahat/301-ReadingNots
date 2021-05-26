# trees


1. Node - A Tree node is a component which may contain it’s own values, and references to other nodes
2. Root - The root is the node at the beginning of the tree
3. K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
4. Left - A reference to one child node, in a binary tree
5. Right - A reference to the other child node, in a binary tree
6. Edge - The edge in a tree is the link between a parent and child node
7. Leaf - A leaf is a node that does not have any children
8. Height - The height of a tree is the number of edges from the root to the furthest leaf


### Traversals

> *Traversing a tree allows us to search for a node and mutch more.*

## Depth First  

> *There are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root.*

**Methods of Depth First:**

* **Pre-order:** root >> left >> right

* **In-order:** left >> root >> right

* **Post-order:** left >> right >> root

**The most common way to traverse through a tree is to use recursion. With these traversals, we rely on the call stack to navigate back up the tree when we have reached the end of a sub-path.**



## Breadth First

> *Breadth first traversal iterates through the tree by going through each level of the tree node-by-node.*


## K-ary Trees

> *In this type of tree we use K to refer to the maximum number of children that each Node is able to have.*


## Binary Search Trees (BST)
> *Nodes are organized in a manner where all values that are smaller than the root are placed to the left, and all values that are larger than the root are placed to the right.*

**We can find values queckly**

> **Big O(log n)**


