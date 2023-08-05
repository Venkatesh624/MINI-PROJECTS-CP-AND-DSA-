#include<stdio.h>
#include<stdlib.h>
#include<time.h>
void main() 
{
    int letters,numbers,symbols;
    printf("Welcome to the password generator\n");
    
    char let[] = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ";
    printf("How many letters do you want in your password? ");
    scanf("%d", &letters);
    
    char no[] = "0123456789";
    printf("How many numbers do you want in your password? ");
    scanf("%d", &numbers);
    
    char sym[] = "!@#$%^&*?";
    printf("How many symbols do you want in your password? ");
    scanf("%d", &symbols);
    
    srand(time(NULL));
    
    printf("This is your password as per your requirements:\n ");
    for (int i = 0; i < letters; i++) 
    {
        printf("%c",let[rand()%(sizeof(let)-1)]);
    }
    for (int i = 0; i < numbers; i++)
    {
        printf("%c",no[rand()%(sizeof(no)-1)]);
    }
    for (int i = 0; i < symbols; i++) 
    {
        printf("%c",sym[rand()%(sizeof(sym)-1)]);
    }
    printf("\n");
}
