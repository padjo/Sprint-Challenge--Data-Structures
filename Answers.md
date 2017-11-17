## Questions
1. What are the order of insertions/removals for the following data structures?
   - **Stack**
     A data stack is a linear data structure. It saves data in a sequential order
     An example of a stack in real life is a program call stack . The first function call is added
     to the stack and subsequent function calls are added to the top of the stack after each call. When
     no more functions are called and the last function end or finishes running it is removed or popped from the stack and the same happens with the other function in order. Another common example is adding plates
     to a stack of dishes. plates are added to the top of the stack and maintain their order. plates are taken off the stack in a last in first out fashion (lifo)
   - **Queue**
     A queue is very similar to a stack with one key difference. The oder of retrieval is on a first in first out basis (fifo). It is very similar to a queue in real life. If you are first in a queue at a supermarket
     you will be served first. If you join a queue you will be at the back of the queue. joining a queue is called enqueueing and being served is called dequeuing.
2. What is the retrieval time complexity for the following data structures?
  *** source http://bigocheatsheet.com ***
   - **Linked List** Simple answer is 0(n). A linked list is very similar to an array except items (nodes) can be stored anywhere in memory. The advantage of this is that your linked lists can increase or decrease in size by adding items to the end of the linked list and changing the tail pointer which indicates the end of the list. Removing an item from a linked list means changing the previous nodes pointer to the node after following the removed node. Linked lists need to be searched sequentially , one after the next so retrieval time is n , best case 1, worst n

   - **Hash Table**  O(1). Hash tables or associative dictionaries offer 0(1) insert and retrieval because a hash functions is used to to generate determine the index of the array where the data will be stored on the hash table . So insert is fast and retrieval is also fast because you are pointed to the index of where the data is stored , you don't have to traverse the data structure to find the item.
   - **Binary Search Trees** 0(log n). Binary Trees values are sorted on insertion . A trees left child nodes are always smaller while the right side are always bigger. When you search for an item, on each iteration the data set to be searched is halved (left or right of the tree is cut off and the search repeated). This is algorithmic
2. What are some advantages to using a Hash Tables over an array in JavaScript?
   Hash table lookups are O(1) while for arrays it's n . Retrieval and insertion of data are critical in
   accessing data structures.
