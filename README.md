# Binary Search Tree (BST) is a special kind of binary tree, which has an efficient structure to organize data for quick search as well as quick update.
So, the tree is a collection of nodes with edges that connect them. The nodes are organized in two levels, and the top level is called the __root node__. Each node can have __up to 2__ child nodes, being a parent node. Those child nodes are called __siblings__, because they share the same parent. If such nodes have no childs, they are called __leaf nodes__. Nodes under the root node are called __descendants__. And for instance, node '1', has __ancestors__, which are every node between itself and the root node.
 
There's also a __subtree__, which is a tree in itself under the root node. 

<a href="https://www.youtube.com/watch?v=rRH-zvM3FAI" rel="Video Tutorial">![Foo](https://i.imgur.com/ajT3XjI.jpg)</a>

In BST, each node is greater than every node in its left subtree. And each node is less than every node in its right subtree. Adding is always started from the root node and we're always gonna add a node as a leaf one.

__It's all a theory part.__

So, in project we can practice. There's an inserting, searching, deleting operations. There's also function to make a whole tree of random nodes, and the 'Clear' button, which deletes a tree.
