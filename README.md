#include<stdio.h>
 
int main() {
   int i, arr[100], sum, num;
 
   printf("\nEnter no of elements :");
   scanf("%d", &num);
 
   
   printf("\nEnter the values :");
   for (i = 0; i < num; i++)
      scanf("%d", &arr[i]);
 
   
   sum = 0;
   for (i = 0; i < num; i++)
      sum = sum + arr[i];
 
   //Printing of all elements of array
   for (i = 0; i < num; i++)
      printf("\na[%d]=%d", i, arr[i]);
 
   //Printing of total
   printf("\nSum=%d", sum);
 
   return (0);
}
