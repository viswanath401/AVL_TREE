Time Complexity of Major BST Operations 

In a Binary Search Tree (BST), the time complexity of operations depends on the height (h) of the tree.

Operation	Average Case	Worst Case
Search	O(log n)	O(n)
Insert	O(log n)	O(n)
Delete	O(log n)	O(n)

A balanced BST is needed to prevent the tree from becoming skewed like a linked list, so that search, insertion, and deletion operations always remain fast and efficient with logarithmic time complexity.

An AVL tree detects imbalance by checking the balance factor of each node after insertion or deletion.
The balance factor is calculated as:

**Balance Factor = Height of Left Subtree − Height of Right Subtree**

If the balance factor of any node becomes +2 or −2, the tree is considered imbalanced at that node and needs rotation to restore balance.

