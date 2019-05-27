```Java
/**
 * Time 1ms
 * @author wowpH
 * @version 1.0
 */
#include<stdio.h>
int main()
{
     int a,b,c;
      
     while(scanf("%d%d",&a,&b)!=EOF)
     {
          if(a==0&&b==0)
          break;
          printf("%d\n",a+b);
     }
     return 0;
}
```