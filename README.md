# Assignment-6
Question 1
#include <stdio.h>

int main()
{
    int n,a=0;
    printf("enter a number: ");
    scanf("%d",&n);
    for ( int i=1; n>=i; i++)
    {
        a=a+i;
    }
      printf("%d",a);
    return 0;
}
Question 2
int main()
{
    int n,a=0;
    printf("enter a number: ");
    scanf("%d",&n);
    for ( int i=2; n*2 >=i; i=i+2)
    {
        a=a+i;
    }
      printf("%d",a);
    return 0;
}

Question 3

#include <stdio.h>

int main()
{
    int n,a=0;
    printf("enter a number: ");
    scanf("%d",&n);
    for ( int i=1; (n*2-1) >=i; i=i+2)
    {
        a=a+i;
    }
      printf("%d",a);
    return 0;
}

Question 4

#include <stdio.h>

int main()
{
    int n,a=0;
    printf("enter a number: ");
    scanf("%d",&n);
    for ( int i=1; n >=i; i++)
    {
        a=a+i*i;
    }
      printf("%d",a);
    return 0;
}
Question 5

#include <stdio.h>

int main()
{
    int n,a=0;
    printf("enter a number: ");
    scanf("%d",&n);
    for ( int i=1; n >=i; i++)
    {
        a=a+i*i*i;
    }
      printf("%d",a);
    return 0;
}

Question 6

#include <stdio.h>

int main()
{
    int n,a=1;
    printf("enter a number: ");
    scanf("%d",&n);
    for ( int i=1; n >=i; i++)
    {
        a=a*i;
    }
      printf("%d",a);
    return 0;
}
Question 7

#include <stdio.h>

int main()
{
    int n,a=0;
    printf("enter a number: ");
    scanf("%d",&n);
    while(n>0)
    {
        n=n/10;
        a++;
    }
      printf("%d",a);
    return 0;
}

Question 8

#include <stdio.h>

int main() { 
   int loop, number;
   int prime = 1;
   printf("enter a number: ");
   scanf("%d",&number);

   for(loop = 2; loop < number; loop++) {
      if((number % loop) == 0) {
         prime = 0;
      }
   }

   if (prime == 1)
      printf("%d is prime number.", number);
   else
      printf("%d is not a prime number.", number);
   return 0;
}

Question 9

#include <stdio.h>
int main() {
    int n1, n2, i, gcd, lcm;
    printf("Enter two positive integers: ");
    scanf("%d %d", &n1, &n2);

    for (i = 1; i <= n1 && i <= n2; ++i) {
        
        if (n1 % i == 0 && n2 % i == 0)
            gcd = i;
    }

    lcm = (n1 * n2) / gcd;

    printf("The LCM of two numbers %d and %d is %d.", n1, n2, lcm);
    return 0;
}

Question 10

#include<stdio.h>  
 int main()    
{    
int n, reverse=0, rem;    
printf("Enter a number: ");    
  scanf("%d", &n);    
  while(n!=0)    
  {    
     rem=n%10;    
     reverse=reverse*10+rem;    
     n/=10;    
  }    
  printf("Reversed Number: %d",reverse);    
return 0;  
}   
