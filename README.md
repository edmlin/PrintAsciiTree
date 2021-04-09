# PrintAsciiTree
Used to print a tree structure to console for debug purpose.  
Copied from(with minimum changes): http://web.archive.org/web/20071224095835/http://www.openasthra.com/wp-content/uploads/2007/12/binary_trees1.c  
## Output
```
./main

After inserting element 10..
10

After inserting element 5..
 10
 /
5

After inserting element 15..
 10
 / \
5  15

After inserting elements 9, 13..
   10
   / \
  /   \
 /     \
5      15
 \     /
  9   13

After inserting elements 2, 6, 12, 14, ..
     10
     / \
    /   \
   /     \
  5      15
 / \     /
2   9   13
   /   / \
  6   /   \
     12   14


After deleting a node (14) with no child..
     10
     / \
    /   \
   /     \
  5      15
 / \     /
2   9   13
   /   /
  6   12


After deleting a node (13) with left child..
     10
     / \
    /   \
   /     \
  5      15
 / \     /
2   9   12
   /
  6


After deleting a node (5) with left and right children..
     10
     / \
    /   \
   /     \
  6      15
 / \     /
2   9   12


After deleting a node (10, root node) with left and right children..
   12
   / \
  6  15
 / \
2   9
```
