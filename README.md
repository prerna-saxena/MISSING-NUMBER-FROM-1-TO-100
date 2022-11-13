# MISSING-NUMBER-FROM-1-TO-100



#include <stdio.h>
void main()
{
int i, n, sum=0, missing, arr[n-1];
printf("ENTER A NO\n");
scanf("%d", &n);
printf("ENTER THE NO TO INSERT IN AN ARRAY\n");
for(i=0; i<n-1; i++)
{
    scanf("%d", &arr[i]);
    sum=sum+arr[i];
}
missing=(n*(n+1))/2-sum;
printf("missing number is = %d", missing);

}
