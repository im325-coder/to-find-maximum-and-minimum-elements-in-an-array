** to-find-maximum-and-minimum-elements-in-an-array**



#include<stdio.h>
int main()
{
int i,n,min=0,max=0;
int arr[10];
printf("enter the number of elemets in an array");
scanf("%d",&n);
for(i=0;i<n;i++)
{
scanf("%d",&arr[i]);
}
min=arr[0];
max=arr[0];
for(i=0;i<n;i++)
{
if(arr[i]>max)
{
max=arr[i];
}
if(arr[i]<min)
{
arr[i]=min;
}
}
printf("the maximum elemet is %d,max);
printf("the minimum elemet is %d,min);
return 0;
}
