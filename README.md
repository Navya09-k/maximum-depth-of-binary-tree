# maximum-depth-of-binary-tree
Uses a recursive Depth-First Search (DFS). If the root is null, the depth is 0. Otherwise, it recursively calculates the maximum depth of the left and right subtrees, takes the maximum of the two, and adds 1 for the current root node. Time: $O(n)$, Space: $O(h)$.
