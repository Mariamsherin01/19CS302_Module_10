# EX 47 C function to insert a node in a linked list.
## AIM:
To write a C function to insert a node in a linked list.

## Algorithm
1. Create a new node with the given character and set its next to NULL.
2. If the list is empty (head == NULL), set head to new node.
3. Else, traverse the list to the last node.
4. Set the last node's next to the new node.


## Program:
```
/*
C function to insert a node in a linked list.

Developed by: Mariam Sherin
RegisterNumber: 212222060143
struct Node{
    char data;
    struct Node *next;
}*head;

void insert(char data)
{
    struct Node *n=(struct Node*)malloc(sizeof(struct Node));
    struct Node *temp;
    if(head==NULL)
    {
        head = n;
        head->data=data;
        n->next=NULL;
        return;
    }
    temp=head;
    while(temp->next!=NULL)
    {
        temp=temp->next;
    }
    n->data=data;
    n->next=NULL;
    temp->next=n;
}

*/
```

## Output:

![image](https://github.com/user-attachments/assets/0f3732e8-cc0c-4bec-85f9-86beaf2b2c44)


## Result:
Thus the program was executed and the output was verified successfully.
