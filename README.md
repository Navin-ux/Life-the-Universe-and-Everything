# Life-the-Universe-and-Everything
#Your program is to use the brute-force approach in order to find the Answer to Life, the Universe, and Everything. More precisely… rewrite small numbers from input to output.
#Stop processing input after reading in the number 42. All numbers at input are integers of one or two digits. 
#Sample Input:
1
2
88
42
99 
#Sample Output: 
1
2
88

#include <stdio.h>
int main(void)
{
    int i;
    while (1) {
        scanf("%d", &i);
        if (i == 42)
            break;
        printf("%d\n", i);
    }
    return 0;
}
