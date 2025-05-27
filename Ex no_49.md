# EX 49 C function to search an element in the doubly linked list.
## AIM:
To write a C function to search an element in the doubly linked list.

## Algorithm
1. Initialize a pointer `temp` to the head of the list.
2. Initialize a counter `position` to 1.
3. While `temp` is not NULL:
   a. If `temp->data` is equal to the search value:
      - Print "item <value> found at location <position>".
      - Exit the function.
   b. Move `temp` to the next node.
   c. Increment `position` by 1.
4. If the end of the list is reached and no match was found:
   - Print "Item not found".
 

## Program:
```
/*
C function to search an element in the doubly linked list.

Developed by: Mariam Sherin
RegisterNumber: 212222060143
struct Node
{
    struct Node *prev;
    struct Node *next;
    float data;
}*head;

void search(float data)
{
    struct Node *temp=head;
    int i=1,flag=0;
    if(head==NULL)
    {
        printf("List is empty\n");
    }
    else
    while(temp!=NULL)
    {
         if(temp->data==data)
         {
             printf("item %.2f found at location %d\n",temp->data,i);
             flag=0;
             break;
         }
         else
         flag=1;
        i++;
        temp=temp->next;
    }
    if(flag==1)
    printf("Item not found\n");
    
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/3c5366d8-095b-4bc1-9d8d-e3f43dd53fde)


## Result:
Thus the program was executed and the output was verified successfully.
