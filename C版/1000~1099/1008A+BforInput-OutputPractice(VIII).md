```c
#include<stdio.h>
int main()
{
     int i,j,m,n,a;
      
     scanf("%d",&m);
     for(i=1;i<=m;i++)
     {
          int sum=0;
           
          scanf("%d",&n);
          for(j=1;j<=n;j++)
          {
               scanf("%d",&a);
               sum+=a;
          }     
          printf("%d\n\n",sum);
     }
     return 0;
}
/**************************************************************
    Problem: 1008
    User: jk4167166
    Language: C
    Result: Accepted
    Time:1 ms
    Memory:1088 kb
****************************************************************/
```