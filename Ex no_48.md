# EX 48 C functions to traverse a double linked list
## AIM:
To write a C functions to traverse a double linked list

## Algorithm
1. Start with the head pointer of the doubly linked list.

2. If head is NULL:
   - The list is empty; exit traversal.

3. Set a temporary pointer (temp) to head.

4. While temp is not NULL:
   a. Print the data in temp.
   b. Move temp to the next node (temp = temp->next).

5. End traversal when temp becomes NULL.


## Program:
```
/*
C functions to traverse a double linked list

Developed by: Mariam Sherin
RegisterNumber: 212222060143
struct Node
{
    struct Node *prev;
    struct Node *next;
    char data;
}*head;
void display()
{
    struct Node *ptr;
    ptr=head;
    while(ptr!=NULL)
    {
        printf("%c\n",ptr->data);
        ptr=ptr->next;
    }
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/533afc5f-a2bd-43c9-a3f2-a285eae90727)


## Result:
Thus the program was executed and the output was verified successfully.
