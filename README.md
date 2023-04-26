# Linked-List  
A linked list is a linear data structure that includes a series of connected nodes. Here, each node stores the data and the address of the next node.  
![image](https://cdn.programiz.com/sites/tutorial2program/files/linked-list-concept.png)  
### Syntax:  
struct Node { int Data; Struct Node *next; };  
The code will create a data type Node, which will be able to store two values-: int value – data pointer value – address of the next node

### Insertion of a node  
struct node
{
int data;
struct node *next;
};
struct node *head, *ptr;
ptr = (struct node *)malloc(sizeof(struct node *));
There are three common types of Linked List.  

1) Singly Linked List  
2) Doubly Linked List  
3) Circular Linked List  

#### Singly Linked List  
It is the most common. Each node has data and a pointer to the next node.  
![image](https://user-images.githubusercontent.com/91966613/234319219-ba10e1b4-7984-4692-b980-d48d40bb1b5a.png)

#### Doubly Linked List  
We add a pointer to the previous node in a doubly-linked list. Thus, we can go in either direction: forward or backward.  
![image](https://user-images.githubusercontent.com/91966613/234319734-7045bca4-29a8-4cba-bcdd-713f9d0ab19e.png)

#### Circular Linked List
A circular linked list is a variation of a linked list in which the last element is linked to the first element. This forms a circular loop.  
![image](https://user-images.githubusercontent.com/91966613/234320027-9b4dd83b-6474-4238-8ae2-6c7f8d7afad6.png)
