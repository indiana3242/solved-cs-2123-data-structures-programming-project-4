Download Link: https://assignmentchef.com/product/solved-cs-2123-data-structures-programming-project-4
<br>
In this project, we will be implementing the basic functionality of a Binary Search Tree.




<strong>Files provided in the project: </strong>

<ul>

 <li>h. This file contains the structs needed for the BinarySearchTree as well as the prototypes for several functions that you will need to implement.  In</li>

</ul>

particular you need to implement the following functions in the file BinarySearchTree.c:

<ol>

 <li><strong>BinarySearchTree newBinarySearchTree()</strong> which should allocate the memory for a new binary search tree, initialize the variables, and return the address.</li>

 <li><strong>void freeBinarySearchTree(BinarySearchTree tree)</strong> which should free the tree (including any nodes currently in the tree).</li>

 <li><strong>NodeT *allocateNode(Element value) </strong>which should allocate memory for a new node, store “value” inside this node, and return the address of the node.</li>

 <li><strong>NodeT *search(NodeT *p, int searchValue) </strong>which should <strong>recursively</strong> search the subtree rooted at p for a node containing a key value equal to searchValue. If such a node exists, return a pointer to the node.  If no such node exists, return NULL.  Note that to search the entire tree, we would call this function with search(tree-&gt;pRoot, searchValue).</li>

 <li><strong>int insert(BinarySearchTree tree, Element value) </strong>which will insert a node with the element value into the tree as a leaf node if it does not already exist in the tree. If the node is inserted then return true.  If the node already exists, return false.</li>

 <li><strong>void printInOrder(NodeT *p) </strong>which will recursively print the values of the nodes in the tree in increasing order. We would call this function with printInOrder(tree-&gt;pRoot).</li>

 <li><strong>void printPreOrder(NodeT *p) </strong>which will recursively print the values of the nodes in the tree according to a preorder traversal (discussed in class on Thursday). We would call this function with printPreOrder(tree-&gt;pRoot).</li>

</ol>

<strong> </strong>




<ul>

 <li>txt. This file contains a sample input file that you should process.  Each line will contain either INSERT X, SEARCH X, PRINT INORDER, or PRINT PREORDER.  If the line contains</li>

</ul>

INSERT X, then you should insert a new node into the binary search tree containing the value X.

If the value inserted correctly, print “Inserted X into tree”.  If the node was already in the tree, print “X already is in the tree”.  If the line contains SEARCH X, you should search the tree for a node containing X.  Print “Found X” if it exists and print “X not in tree” if it does not exist.  If the line contains PRINT INORDER or PRINT PREORDER then print the contents of the tree with an inorder traversal or a preorder traversal respectively.

<ul>

 <li>c. Rename this file to your abc123.  This file is mostly empty right now.  It contains the main() function that you should complete.  In main, you should create a new</li>

</ul>

BinarySearchTree, read a line from p4Input.txt (you can do this however you would like), and perform the appropriate operation on the tree.

5) Makefile.  Update the makefile to reflect your abc123.  Compile using <strong>make p4</strong>. Execute the program using <strong>./p4 &lt; p4Input.txt </strong>










<strong>Submitting: </strong>

Please submit to the blackboard dropbox a zipped folder containing each of the files we have provided you along with the new DoublyLinkedList.c and BrowserList.c files that you create.





