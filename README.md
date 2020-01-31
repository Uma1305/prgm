//sum of n numbers
#include <stdio.h>

int main()
{
    int n,a[10],i,sum=0;
    float avg;
    printf("enter the number:");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    
    for(i=0;i<n;i++)
    {
        sum=sum+a[i];
    
        avg=sum/n;
        
        
    }
    printf("sum=%d",sum);
    printf("avg=%f",avg);
        
    return 0;
}
output:
enter the number:3
12
12
12
sum=36avg=12
