# EX 46 C function to traverse the linked list and display it in the following format.
## AIM:
To write a C function to traverse the linked list and display it in the following format.

## Algorithm
1. Define a node structure with two fields: 
   - data (char)
   - next (pointer to next node).

2. Initialize head pointer to NULL (empty list).

3. For each insert operation:
   a. Create a new node with the given character.
   b. If the list is empty (head == NULL), set head to new node.
   c. Else, traverse to the last node and set its next to the new node.

4. For display operation:
   a. Start from the head node.
   b. While the current node is not NULL:
      i. Print the data of the current node.
      ii. Move to the next node.
  

## Program:
```
/*
C function to traverse the linked list and display it in the following format.

Developed by: Mariam Sherin
RegisterNumber: 212222060143
struct Node
{
    char data;
    struct Node *next;
}*head;
void display()
{
    struct Node *temp;
    temp = head;
    while(temp!=NULL)
    {
        printf("%c\n",temp->data);
        temp = temp->next;
    }
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/5328ef7e-e9c0-4a9f-bb21-02153d45615b)


## Result:
Thus the program was executed and the output was verified successfully.
