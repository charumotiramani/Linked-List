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
