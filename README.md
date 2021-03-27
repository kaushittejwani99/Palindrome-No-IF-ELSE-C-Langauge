# Palindrome-No-IF-ELSE-C-Langauge
This program is check to whether a given no is palindrome or not using if-else.
#include<stdio.h>
#include<conio.h>
int main()
{
int num,Lastdigit,sum=0,temp;
printf("enter any no:-\n");
scanf("%d",&num);
temp=num;
while(num>0)
{
     Lastdigit=num%10;
     sum=(sum*10)+Lastdigit;
     num=num/10;
}
if (temp==sum)

  printf(" %d is a palindrome no.",temp);

else

   printf("%d is not  a palindrome no.",temp);
   getch();
   return 0;
}
