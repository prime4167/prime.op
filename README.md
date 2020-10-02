# prime.op
c programming

#include <stdio.h>
#include <stdlib.h>
void push();
void pop();
void display();
struct node
{
int a;
struct node *next;
};
struct node *head;

void main ()
{
    int choice=0;
    printf("\n$$$$$$$$$ Stack operations using linked list $$$$$$$$$\n");
    printf("\n----------------------------------------------\n");
    printf("\nShubham Pawaskar 1912065 b3 \n");
    while(choice != 4)
    {
        printf("\n\nChose one from the below options...\n");
        printf("\n1.Push\n2.Pop\n3.Show\n4.Exit");
        printf("\n Enter your choice \n");
