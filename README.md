#include <stdio.h>
#include <math.h>

int add(int num1, int num2);
int divide (int num1, int num2);

int main (void)
{
  int a = 100;
  int b = 7;
  int ret;

  ret = add(a,b);

  printf("a added to b = %d\n", ret);
   
   ret = divide(a,b);

   printf("a divide by b = %d\n", ret);

      return 0;
}

int add (int num1, int num2)
{
  int result;
  result=num1+num2;
  return result;
  }

int divide (int num1, int num2)
{
  int result;
  result=num1/num2;
  return result;
}
