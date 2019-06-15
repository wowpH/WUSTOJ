```c
#include<stdio.h>
int main()
{
     int i,n,a;
      
     while(scanf("%d",&n)!=EOF)
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
/**************************************************************
    Problem: 1006
    User: jk4167166
    Language: C
    Result: Accepted
    Time:1 ms
    Memory:1088 kb
****************************************************************/
```