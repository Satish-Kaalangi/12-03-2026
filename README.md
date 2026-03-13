# 12-03-2026
C programming 
//12-03-2026//Thursday
//To print an integer reverse
#include <stdio.h>
void main()
{
int n,rev=0;
scanf("%d",&n);
while(n!=0)
{
int digit=n%10;
rev=rev*10+digit;
n=n/10;
}
printf("reversed=%d",rev);
}

//To print a number is palindrome
#include <stdio.h>
void main()
{
int n,O,remainder,rev=0;
scanf("%d",&n);
O=n;
while (n!=0)
{
remainder=n%10;
rev=rev*10+digit;
n=n/10;
}
if (O==rev)
printf("palindrome");
else 
printf("not");
}

//To print a number is amstrong number or not
#include <stdio.h>
void main()
{
int n,O,rev=0;
scanf("%d",&n);
O=n;
while(n!=0)
{
int digit=n%10;
rev=rev+digit*digit*digit;
n=n/10;
}
if (rev==O)
printf("amstrong no."rev);
else 
printf("not",rev);
}

//To print sum of digits
#include <stdio.h>
void main()
{
int n,digit,sum=0;
scanf("%d",&n);
while (n!=0)
{
digit=n%10;
sum=sum+digit;
n=n/10;
}
printf("sum=%d",sum);
}

//To print a number is happy number
#include <stdio.h>
int main()
{
int n,O,digit,sum;
scanf("%d",&n);
O=n;
while (O!=1&&O!=4)
{
sum=0;
while (O>0)
{
digit=O%10;
sum=sum+digit*digit;
O=O/10;
}
O=sum;
}
if (O==1)
printf("%d id happy number",n);
else
printf("%d is not happy number",n);
return 0;
}

//To print a number is automorphic
#include <stdio.h>
int main()
{
int n,sq,O;
scanf("%d",&n);
sq=n*n;
O=n;
while (O>0)
{
if (O%10!=sq%10)
{
printf("not");
return 0;
}
O=O/10;
sq=sq/10;
}
printf("automorphic");
return 0;
}

//To print a number is harshad number or not
#include <stdio.h>
void main()
{
int n,O,digit,sum=0;
scanf("%d",&n);
O=n;
while(n!=0)
{
digit=n%10;
sum=sum+digit;
n=n/10;
}
n=sum;
if(O%sum==0)
{
printf("harshad no.");
}else{
printf("not")
}
}

//To print a number is magic number or not
#include <stdio.h>
int main()
{
int n,O,digit,sum;
scanf("%d",&n);
O=n;
while(n>9)
{
sum=0;
while(n!=0)
{
digit=n%10;
sum=sum+digit;
n=n/10;
}
n=sum;
}
if(n==1)
printf("magic no.");
else 
printf("not");
return 0;
}

//To print even number using for loop
#include <stdio.h>
void main()
{
for (int i=1;i<=10;i++)
{
if(i%2==0)
{
printf("%d\n",i);
}
}
}

//To find sum of n-natural numbers using for loop
#include <stdio.h>
void main()
{
int i,sum,=0,n;
scanf("%d",&n);
for (i=1;i<=10;i++)
{
sum=sum+i;
}
printf("sum=%d\n",sum);
}

//to print first n even numbers using for loop
#include <stdio.h>
void main()
{
int i,sum=0,n;
scanf("%d",&n);
for (i=1;i<=n;i++)
{
if (i%2==0)
{
sum=sum+i;
}
}
printf("%d\n",i);
}

//To find factorial using for loop
#include <stdio.h>
void main()
{
int i,fact=1,n;
scanf("%d",&n);
for (i=1;i<=10;i++)
{
fact=fact*i;
}
printf("fact=%d\n",fact);
}

//To print multiplication table
#include <stdio.h>
void main()
{
int i,n,m;
scanf("%d",&n);
for (i=1;i<=10;i++)
{
m=n*i
}
printf("%dX%d=%d\n",i,n,m);
}

//To print factors of given number
#include <stdio.h>
void main()
{
int i,n;
scanf("%d",&n);
for (i=1;i<=n;i++)
{
if (n%i==0)
printf("factors=%d\n",i);
}
}

//To find given number is perfect or not
#include <stdio.h>
void main()
{
int i,n,sum=0,t;
scanf("%d",&n);
for (i=1;i<=n;i++)
{
if (n%i==0)
{
sum=sum+i;
}
}
if(t==sum)
{
printf("%d is perfect",t);
}else{
printf("%d is not perfect",t);
}
}
