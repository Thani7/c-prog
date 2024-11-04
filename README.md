#include<stdio.h>
void main()
{
int i,j,n,temp,a[10];
printf("enter the size of the array\n");
scanf("%d",&n);
printf("enter the elements of array\n");
for(i=0;i<n;i++)
scanf("%d",&a[i]);
printf("elements of array before sorting\n");
for(i=0;i<n;i++)
printf("%d",a[i]);
for(i=0;i<n;i++)
{
for(j=i+1;j<n;j++)
{
if(a[i]<a[j])
{
temp=a[i];
a[i]=a[j];
a[j]=temp;
}
}
}
printf("elements of the sorted array are\n");
for(i=o;i<n;i++)
printf("%d",a[i]);
