```C
/**
 * Time 1ms
 * @author wowpH
 * @version 1.0
 */

#include<stdio.h>
int main()
{
     int i,n,a;
      
     while(scanf("%d",&n)!=EOF&&n!=0)
     {
          int sum=0;
          for(i=1;i<=n;i++)
          {
               scanf("%d",&a);
               sum+=a;              
          }
          printf("%d\n",sum);
    }
     return 0;
}
```