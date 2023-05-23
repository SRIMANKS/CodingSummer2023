in heaps data is stored as binary trees. in queues insertion and deletion takes constant time but when a array is made to act like a priority queue then it takes constant time for insertion but linear time for deletion hence heaps are introduced they make insertion of deletion of priority queues in logrithimic time.
![[Pasted image 20230522235237.png]]
![[Pasted image 20230522233844.png]]

### Insertion in heap
during insertion the data is first inserted at the last position in the array and later its bubbled up to take its place. takes O(logn).
![[Pasted image 20230522233913.png]]

so for inserting one element it takes roughly O(logn) time and for inserting n elements it takes O(nlogn) time.

Heapify
	so since creation takes O(nlog(n)) time. a newer method was considered. here all the elements are inserted into the array intiallly. then we traverse the array from right side to left side checking each node with its children for possible swaps if needed.



### Deletion in heap
in heaps deletion only takes place at the root node either a max element or a min element is deleted. after deletion the last node is swaped at the root node and bubbled down the tree. to take its place, this method takes O(logn).



### Problems




