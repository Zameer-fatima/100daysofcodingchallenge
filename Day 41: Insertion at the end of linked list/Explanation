In order to insert a node at the last, there are two following scenarios which need to be mentioned.

 ■ The node is being added to an empty list

 ■ The node is being added to the end of the linked list



In the first case, 

■ The condition (head == NULL) gets satisfied. Hence, we just need to allocate the space for the node.

like in java, we use 

node newNode = new node(data);

to allocate space for newnode.

As newnode that is created will act as head and tail so we will appoint newnode as head and tail.

head=newNode
tail=newNode

In the second case,
 ■ The condition Head = NULL would fail, since Head is not null.
 Now, we need to declare a temporary pointer current in order to traverse through the list. current is made to point the first node of the list.

current = head 

■ Then, traverse through the entire linked list using the statements:

while (current→ next != NULL) 

        current = current → next

At the end of the loop, the current will be pointing to the last node of the list. 

■ Now, allocate the space for the new node, and assign the item to its data part. 

■ Since, the new node is going to be the last node of the list hence, the next part of this node needs to be pointing to the null.

■ We need to make the next part of the current node (which is currently the last node of the list) point to the new node.

This is how node is inserted at the end.
