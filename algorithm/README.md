#### B + tree

- Large number of children by tree
- On root (two or more children, reprenst the whole range of values in the tree) , internal nodes and leaves
- Block-oriented storage context, has very high fanout (# of mopinter to cild nodes) => less I/O operations to find an elemnt
The space required to store the tree is O(n)
Inserting a record requires O(logn) operations
Finding a record requires O(logn) operations