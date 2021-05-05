# Linked lists

> *It is a sequence od `nodes` and each node references the next node in line.*

## Types of linked Lists
![img](https://miro.medium.com/max/700/1*AeMDLFUjR0w0J4n8CP4H6g.jpeg)
> **Singly:** *It refers to the number of references the node has. A Singly linked list means that there is only one reference, and the reference points to the Next node in a linked list.*

> **Doubly:** *It refers to there being two (double) references within the node. A Doubly linked list means that there is a reference to both the Next and Previous node.*

> **Circular:** *It has no ending node, it basicaly has a tail node at the beginning of the list. It is really easy to add anything to the end useing the traversal advantage.*

## Creation of Linked list
> *A linked list is created by using the node class. We create a Node object and create another class to use this ode object. We pass the appropriate values thorugh the node object to point to the next data elements*

## Big O

![Img](https://miro.medium.com/max/500/1*FC0XX0-9Vx7yCS0dTS2Zrw.jpeg)

> *The **Big O** of time for Includes would be O(n). This is because, at its worse case, the node we are looking for will be the very last node in the linked list. n represents the number of nodes in the linked list.*

> *The Big O of space for Includes would be O(1). This is because there is no additional space being used than what is already given to us with the linked list input.*

# Non-linear data structures
> *Linked lists are considered so, and here items don't have to be arranged in order.*

**Linked Lists can grow dynamiccaly in memory**

**A node only knows about what data it contains, and who its neighbor is.**


![img](https://miro.medium.com/max/700/1*K0_eV07tJtKQSVGKfP18bw.jpeg)


## Growing a Linked List 


![Img](https://miro.medium.com/max/700/1*Jy5tjwrMdtpGl2ceq4f94A.jpeg)

1. **Find** *the head node.*
2. **Make** *the new node.*
3. **Set** *the new node pointers to the wanted index node.*
4. **Rearrange** *the previos node to point at the new node.*

## Linked list advantages
![Img](https://miro.medium.com/max/700/1*cUehR5S18XSoVLaPNfNzlA.jpeg)


