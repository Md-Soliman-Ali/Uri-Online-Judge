#include <stdio.h>
#include <string.h>
int main()
{
    char str[1500];
    while(1)
    {
        gets(str);
        if(str[0]=='*') break;
        else
        {
            int lnth, i,j,cndtn=1;
            char cse[2];
            lnth=strlen(str);
            if(str[0]>=65 && str[0]<=90)
                cse[0]=str[0]+32;
            else if(str[0]>=97 && str[0]<=122)
                cse[0]=str[0]-32;
            for(i=1; i<lnth; i++)
            {
                if(str[i]==' ')
                {
                    if(str[i+1]==str[0] || str[i+1]==cse[0])
                        continue;
                    else{
                        cndtn=0;
                        break;
                    }
                }
            }
            if(cndtn==1) printf("Y\n");
            else printf("N\n");
        }
    }
    return 0;
}
