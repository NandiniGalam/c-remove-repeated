# c-remove-repeated
#include <stdio.h>
int remove_elements(int*array,int n, int val)
{
  int i;
  for(i=0;i<n;i++)
  if(array[i]!=val)
  printf(" %d ",array[i]);
}
int main()
{
  int array[6] = {1,2,1,3,1},size = 5,value=1;
  remove_elements(array,size,value);
}
