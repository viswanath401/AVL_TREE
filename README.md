Binary Search Trees (BSTs) are fundamental data structures used to store data in a sorted manner and support efficient searching, insertion, and deletion operations. However, the performance of a BST largely depends on its height. If the tree becomes unbalanced, its efficiency degrades. To overcome this issue, self-balancing trees such as AVL Trees are used, which automatically maintain balance and ensure consistent performance.

**Time Complexity of Major BST Operations**
In a Binary Search Tree (BST), the time complexity of operations depends on the height (h) of the tree.
| Operation | Average Case | Worst Case |
|----------|--------------|------------|
| Search   | O(log n)     | O(n)       |
| Insert   | O(log n)     | O(n)       |
| Delete   | O(log n)     | O(n)       |

**Why Balanced BST Is Needed**
A balanced BST is needed to prevent the tree from becoming skewed like a linked list, so that search, insertion, and deletion operations always remain fast and efficient with logarithmic time complexity.

**How AVL Tree Detects Imbalance**
An AVL tree detects imbalance by checking the balance factor of each node after insertion or deletion.
**Balance Factor = Height of Left Subtree − Height of Right Subtree**
If the balance factor of any node becomes +2 or −2, the tree is considered imbalanced and rotations are performed to restore balance.
