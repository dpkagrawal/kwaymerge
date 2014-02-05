K Way Merge - Using Priority Queue Java
==============================================================

Input to the Program : 

List 1 : 1, 5, 9

List 2 : 2, 4, 12, 14

List 3 : 3, 7, 11


Merged List: [1, 2, 3, 4, 5, 7, 9, 11, 12, 14]

Algorithm to Merge K-Sorted List:

1. Take first element of each list and create a min heap.
2. While the min heap has elements. Remove the data from the node and insert to the output list.
3. And get the list index for the Node(index from which list the data came from initially).
4. From the listIndex get second element and insert into the min heap.
5. Repeat this process till there are elements in the heap.
