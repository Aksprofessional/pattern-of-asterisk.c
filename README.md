# pattern-of-asterisk.c
// C program  to print pattern with asterisk   * 
// C program  to print pattern with asterisk 

*
**
***
****
*****

#include <stdio.h>
int main() {
    int i,j,a=0;
    for(i=0;i<5;i++)
    {
        for(j=0;j<=i;j++)
         printf("*");
        printf("\n");
    }
    return 0;
}
