# EX 50 C function to delete a node from a Doubly Linked List at the beginning of the list.
## AIM:
To write a C function to delete a node from a Doubly Linked List at the beginning of the list.

## Algorithm
1. If head is NULL:
   - Print "UNDERFLOW" (the list is empty).
   - Exit the function.

2. Create a temporary pointer `temp` and set it to head.

3. If temp->next is NULL (only one node in the list):
   - Free the node.
   - Set head to NULL.
   - Print "Node deleted".
   - Exit the function.

4. Else (more than one node in the list):
   - Set head to head->next.
   - Set head->prev to NULL.
   - Free temp.
   - Print "Node deleted".


## Program:
```
/*
C function to delete a node from a Doubly Linked List at the beginning of the list.

Developed by: Mariam Sherin
RegisterNumber: 1212222060143
struct Node
{
    struct Node *prev;
    struct Node *next;
    float data;
}*head;

void delete()
{
    struct Node *ptr;
    if(head == NULL)
    {
        printf("UNDERFLOW\n");
    }
    else if(head->next == NULL)
    {
        head = NULL;
        free(head);
        printf("Node deleted\n");
    }
    else
    {
        ptr = head;
        head = head -> next;
        head -> prev = NULL;
        free(ptr);
        printf("Node deleted\n");
    }

}

*/
```

## Output:

![image](https://github.com/user-attachments/assets/6f84bb43-fe6b-4da3-b28e-964d815db40a)


## Result:
Thus the program was executed and the output was verified successfully.
