***Linked List Implementation in Python***
This Python script demonstrates a simple implementation of a singly linked list using object-oriented programming. 
A linked list is a fundamental data structure where each element, known as a node, consists of two parts: data and a reference (or link) to the next node in the sequence.

**Node Class:**
The Node class represents an individual element in the linked list. Each node contains:

# data: This holds the actual value or data stored in the node.
# next: This points to the next node in the sequence. Initially set to None, it gets updated to link to subsequent nodes.

**linkedlist Class:**

The linkedlist class is the core of the linked list structure. It manages the nodes and operations on them:

# head: This attribute points to the first node in the linked list.

**Methods:**

# inserthead(newdata): Adds a new node containing newdata at the beginning of the linked list. It updates self.head to point to this new node.

# insertMid(Midnode, newdata): Inserts a new node with newdata after the node Midnode. It adjusts the next references to maintain the sequence.

# remove(removedata): Removes the node containing removedata from the linked list. It traverses the list to find the node and adjusts the references to skip over the removed node.

show(): Displays all nodes in the linked list starting from self.head. It iterates through each node, printing its data value sequentially.
