#include<stdio.h>
int a[10],n,b,i,pos,el;

void insert()
{   
    printf("Enter the position you want to insert the element: \n");
    scanf("%d",&pos);
    printf("Enter the element you want to insert: \n");
    scanf("%d",&el);
    for(i=n;i>pos-1;i--)
    {
      a[i]=a[i-1];
    }
    a[pos-1]=el;
    n++;
    printf("The array is: \n");
    for(i=0;i<n;i++)
    {
      printf("%d \n",a[i]);
    }
}
/*void delete()
{
  int a[10],n,b,i,pos,el;
  printf("Enter the position you want to delete*/
  
  
   
int main()
{
  printf("Enter the number of elements: \n");
  scanf("%d",&n);
  printf("Enter the elements: \n");
  for(i=0;i<n;i++)
  {
    scanf("%d",&a[i]);
  }
  for(i=0;i<n;i++)
  {
    printf("%d \n",a[i]);
  }
  insert();
  return 0;
}
