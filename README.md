# Competitive-Coding-1

### Problem 1:
Provide an array of n-1 integers in the range of 1 to n with no duplicates in list, One of the integers is missing in the list. Write a code to find the missing integer.<br>
Examples:<br>
Input : arr[] = [1, 2, 3, 5, 6, 7, 8]<br>
Output : 4<br>
Input : arr[] = [1, 2, 4, 5, 6, 7, 8, 9]<br>
Output : 3<br>

### Problem 2:
#### Min Heap
A Min-Heap is a complete binary tree in which the value in each internal node is less than or equal to the values in the children of that node.<br>
Mapping the elements of a heap into an array is trivial: if a node is stored a index k, then its left child is stored at index 2k + 1 and its right child at index 2k + 2.<br><br>

Operations on Min Heap:<br>

getMin(): It returns the root element of Min Heap. O(1)<br>
extractMin(): Removes the minimum element from MinHeap. O(log N) as this operation needs to maintain the heap property after removing root.<br>
insert(): We add a new key at the end of the tree. If new key is larger than its parent, then we don’t need to do anything. Otherwise, we need to traverse up to fix the violated heap property. O(log N)<br>
Example of Min Heap:<br>
<pre>

         5                      11





         /      \               /       \  





       9        13           13         25 





      /                      /  \        /  \





    20                     32    45    95    40
    </pre>
