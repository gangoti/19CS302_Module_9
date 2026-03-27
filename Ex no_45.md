# EX 45 C program that implements a queue using an array, and performs insertion (enqueue) and display operations.
## DATE:
## AIM:
To write a C program that implements a queue using an array, and performs insertion (enqueue) and display operations. 

## Algorithm
Start. Define a variables. Write a functions to traverse the linked list and display it in the following format. Read the value using scanf. Ask the user to make an input. Print out the answer. End   

## Program:
```
struct Node{ 
char data; 
struct Node *next; 
}*head; 
 void display() 
{ 
struct Node *temp; 
temp=head; 
while(temp!=NULL) 
{ 
printf("%c\n",temp->data); 
temp=temp->next; 
} 
 
} 
```
## Output:
<img width="1063" height="543" alt="image" src="https://github.com/user-attachments/assets/f13f6800-c367-4394-8d40-7da777e18e08" />

## Result:
Thus the program was executed and the output was verified successfully.
